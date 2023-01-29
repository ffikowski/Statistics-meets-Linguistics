# Statistics meets Linguistics (01/23)
- This code is partly a result of the equaly named university course "Statistics meets Linguistics"
- The goal is to classify whether a speaker has a singaporean origin or a canadian origin
- It is based on the corpus data from the candian and singaporean ICE corpus
- ICE (International Corpus of English) is a collection of written and spoken English language corpora
- The main challange was the data preprocessing
- We extracted the spoken text from each speaker in each conversation transcript via regex and performed a tfidf-vectorization
- The Classification task was solved by a simple Linear Support Vector Classifier
