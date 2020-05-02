# H6751-Final-Project---Group_4---Funtextic
1. Code
   - Machine learning methods : real_disaster_classifier_machinelearning.ipynb
      - Validation variable
        - 'test_size'  : size of test splitting
      - Preprocessing control variable
        - 'remove_url'
        - 'remove_non_ascii'
        - 'lemmatize_verbs' 
        - 'remove_punctuation'
        - 'remove_stopwords'
        - 'replace_numbers'
        - 'stem_text'
   - Deep learning methods : real_disaster_classifier_deeplearning.ipynb
      - GloVe related variable:
        - 'use_glove'         : control if GloVe vectors should be used
        - 'train_glove'       : control if GloVe embedding layer will be trained
      - Training related variable:
        - 'maxlen'            : maximum length of input sequence
        - 'embedding_size'    : word embedding dimension
        - 'kernel_size'       : CNN kernal size
        - 'filters'           : CNN filters size
        - 'lstm_output_size'  : LSTM output dimension
        - 'batch_size'        : training batch size
        - 'dropout'           : dropout rate
2. Data 
   - train.csv and test.csv can be found under data folder
   - GloVe file can be downloaded from GloVe official website https://nlp.stanford.edu/projects/glove/
