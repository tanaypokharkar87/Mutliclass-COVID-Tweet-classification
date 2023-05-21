# Mutliclass-COVID-Tweet-classification

• Text mining analysis using Natural Language Processing—Twitter:COVID-19 Multi-Label Classifying tweets:
• Pre-processed the Twitter data (labeled + unlabeled) using extending contractions, removing punctuations, stopwords, data
augmentation to transform it into a more uniform form.
• Analyzed the data with a combination of feature extraction and classification techniques like TF-IDF features and Linear
SVM, Word2Vec, Word Embedding in Deep Neural Network, using Random Forest Classifier, xgBoost Classifier,
Logistic Regression and a reported each of the accuracy after hyperparameter tuning.
• Explored BERT classification using the BertTokenizer in a bidirectional manner which exponentially improved the accuracy.
• A combination of weakly supervised + semi-supervised model initiated to utilize the unlabeled dataset. Random forest
predicted the multi-class labels (unlabeled data) to generate the pseudo-labels. Distant supervision technique has also been
explored to train the model into a to learn patterns and features from unlabeled data to classify it further.
• Used semi-supervised learning algorithms like Label Propagation, Label Spreading or Co-Training, to incorporate the
pseudo-labels generated from the weakly supervised model to improve model’s generalization for an improved accuracy.
