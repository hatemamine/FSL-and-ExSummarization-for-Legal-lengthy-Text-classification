Algeria :algeria: 
# Few-Shot learning and Extractive Summarization for Legal lengthy Text classification 

:warning: The code was split on unit to fit the limit of [Kaggle](https://www.kaggle.com/) 👍 batch sessions running time < 9 hours
# Preprocessing and generate dataset for training the Siamese BERT-Networks
## SCOTUS 
[SCOTUS preprocessing long text with keybert & generate dataset for training Siamese BERT-Networks](https://github.com/hatemamine/Siamese_BERT_LegalTexts_Classification/blob/main/scotuslexglue-preprocesslongtextwithkeybert.ipynb)


## LEDGAR
[preprocessing short text **without keybert** and generate dataset for training Siamese BERT-Networks](https://github.com/hatemamine/Siamese_BERT_LegalTexts_Classification/blob/main/ledgarlexglue-preprocess-and-generate-dataset.ipynb)

# Training the Siamese BERT-Networks **Bi-Encoder LEGAL-BERT**
[Training the Siamese BERT-Networks **SCOTUS preprocessed with KeyBERT**](https://github.com/hatemamine/Siamese_BERT_LegalTexts_Classification/blob/main/scotuslexgluesiamesebert-training.ipynb)

[Training the Siamese BERT-Networks **SCOTUS preprocessed without KeyBERT**](https://github.com/hatemamine/Siamese_BERT_LegalTexts_Classification/blob/main/nokeybertscotuslexgluesiamesebert-training.ipynb)

[Training the Siamese BERT-Networks **LEDGAR**](https://github.com/hatemamine/Siamese_BERT_LegalTexts_Classification/blob/main/ledgarlexgluesiamesebert-training.ipynb)

# Inference and Evaluation
[generate embedding using the trained model **SCOTUS dataset preprocessed with KeyBERT**](https://github.com/hatemamine/Siamese_BERT_LegalTexts_Classification/blob/main/scotus-generate-embeddings.ipynb)

[generate embedding using the trained model **SCOTUS dataset**](https://github.com/hatemamine/Siamese_BERT_LegalTexts_Classification/blob/main/nokeybertscotus-generate-embeddings.ipynb)

[generate embedding using the trained model **LEDGAR dataset**](https://github.com/hatemamine/Siamese_BERT_LegalTexts_Classification/blob/main/ledgar-generate-embeddings.ipynb)

## Evaluation
[KeyBERT SCOTUS prediction using KNN and SVM + evaluation F1 score + plot results, visualisation UMAP, Confusion Matrix](https://github.com/hatemamine/Siamese_BERT_LegalTexts_Classification/blob/main/keybertscotus-inference-and-evaluation.ipynb)

[LEDGAR prediction using KNN and SVM + evaluation F1 score + plot results, visualisation UMAP, Confusion Matrix](https://github.com/hatemamine/Siamese_BERT_LegalTexts_Classification/blob/main/ledgarinference-and-evaluation.ipynb)
