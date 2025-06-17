# Home_assignment_3
Student Name: Alchuri Nikhitha
Student ID: 700764794

1. Text Generation using RNN (LSTM):
   
Loads a character-level dataset (Shakespeare).

Converts text into sequences.

Trains an LSTM-based RNN to predict the next character.

Generates new text based on a starting string.

Includes temperature scaling to control randomness during generation.

Libraries Used:
tensorflow, numpy

Key Concepts:
Character encoding

Sequence modeling

Temperature scaling for diversity

2. NLP Preprocessing Pipeline:
   
Tokenizes a sentence into words.

Removes English stopwords.

Applies stemming using the Porter Stemmer.

Prints:

Original tokens

Tokens without stopwords

Final stemmed tokens

Libraries Used:
nltk

Sample Sentence:
"NLP techniques are used in virtual assistants like Alexa and Siri."

3. Named Entity Recognition (NER) with spaCy:
   
Uses spaCy to identify and classify named entities.

Outputs:

Entity text

Entity label (e.g., PERSON, DATE)

Start and end character indices

Libraries Used:
spacy (en_core_web_sm model)

Sample Sentence:
"Barack Obama served as the 44th President of the United States and won the Nobel Peace Prize in 2009."

4. Scaled Dot-Product Attention:
   
Implements the attention mechanism as used in Transformer architectures.

Computes:

Dot product of Query and Key matrices

Scaled scores

Softmax attention weights

Final attention output

Libraries Used:
numpy

Test Matrices:
python
Copy
Edit
Q = [[1, 0, 1, 0], [0, 1, 0, 1]]
K = [[1, 0, 1, 0], [0, 1, 0, 1]]
V = [[1, 2, 3, 4], [5, 6, 7, 8]]

5. Sentiment Analysis using HuggingFace Transformers:
   
Uses a pre-trained distilbert-base-uncased-finetuned-sst-2-english model.

Classifies sentence sentiment.

Prints:

Sentiment label (e.g., POSITIVE)

Confidence score

Libraries Used:
transformers

 Sample Sentence:
"Despite the high price, the performance of the new MacBook is outstanding."

