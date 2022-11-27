# Context based Sarcasm Detection on News Headlines Dataset

The database used in this project can be found [here](https://github.com/rishabhmisra/News-Headlines-Dataset-For-Sarcasm-Detection).

The json file obtained from this dataset was used to fetch article text and stored in `combined.csv`. The code to perform this extraction can be found in `Sarcasm Detection-Preprocessing.ipynb`.

The `combined.csv` file is then used as input for the models executed in `Sarcasm Detection-LSTM.ipynb` and `Sarcasm Detection-RoBERTa.ipynb`.

The file `Sarcasm Detection-LSTM.ipynb` implements two approaches (model without article text and with article text) using LSTM and GLoVe Embeddings.

The file `Sarcasm Detection-RoBERTa.ipynb` implements two approaches (model without article text and with article text) using RoBERTa.
