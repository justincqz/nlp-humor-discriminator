# README

Each cell is labelled/grouped using the text cells above them. This README hopefully allows you to reproduce our results by running the stated cells in that specific order.

## GLoVe

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Training - Models (Approach 1) - GLoVe Models - GLoVe-specific Training
- GLoVe Testing


## BERT Single w/ Attention

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Bert and RoBerta specfic Preprocessing
- BERT Testing
- Training - Models (Approach 1) - Bert Training with Single Sentence


## BERT Single w/ Attention, Freeze

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Bert and RoBerta specfic Preprocessing
- BERT Testing
- Training - Models (Approach 1) - Bert Training with Single Sentence and Freezing


## BERT Double

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Bert and RoBerta specfic Preprocessing
- BERT Testing
- Training - Models (Approach 1) - Bert Training with Double Sentences


## BertForSequenceClassification

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Bert and RoBerta specfic Preprocessing
- BERT Testing
- Training - Models (Approach 1) - Bert with Sequence Classification with Both Sentences


## RoBERTa

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Bert and RoBerta specfic Preprocessing
- RoBERTa Testing
- Training - Models (Approach 1) - RoBERTa Single


## RoBERTa Double

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Bert and RoBerta specfic Preprocessing
- RoBERTa Testing
- Training - Models (Approach 1) - RoBERTa Double


## Multi-Model RoBERTa + BERT single parallel training

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Bert and RoBerta specfic Preprocessing
- Multi-Model Testing
- Training - Models (Approach 1) - Multi-Model Parallel


## Multi-Model RoBERTa + BERT single individual + concat training

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Bert and RoBerta specfic Preprocessing
- Multi-Model Testing
- Training - Models (Approach 1) - Multi-Model Individual + Concat


## Word2Vec + BiLSTM

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Word Embeddings
- Training - Models (Approach 2) - Word2Vec + BiLSTM

## Handcrafted + LinearRegressor

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Feature Extraction
- Initialisation & Processing - Text Preprocessing
- Training - Models (Approach 2) - Regression model on extracted features


## Handcrafted + TF-IDF + FNN

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Feature Extraction
- Initialisation & Processing - Text Preprocessing
- Training - Models (Approach 2) - Handcrafted + TF-IDF + RNN


## Handcrafted (orig + FunLines) + FNN

- Start
- Load Data
- Training and Evaluation Helpers
- Helper Functions
- Models
- Initialisation & Processing - Prepare the data for training, assign hyperparameters, initialise the models.
- Initialisation & Processing - Extract and parse the edited words and sentences
- Initialisation & Processing - Prepare Feature Extraction
- Initialisation & Processing - Text Preprocessing
- Training - Models (Approach 2) - FNN on additional FunLines dataset
