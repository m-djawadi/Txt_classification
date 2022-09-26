"" The goal is to predict the category of scientic research papers. 
There are 40 each givena numerical id. The labels correspond to categorisation into different subject areas. 
For each paper we are given an id, the title, and the abstract.""


Datasets
• train.csv: This file provides the training nodes (label, node id).
• test.csv: This file provides the test nodes (node id,).
• text.csv: This file provides the features, i.e. the paper title and abstract (paper id, title, abstract).
• nodeid2paperid.csv: This file provides the map from nodes to papers(node id, paperid).
• sample.csv: This file provides a sample submission file in the correct format (node id, label).


Here are some general suggestions (not specic to this problem):
• Split your training data into train, validation, and test sections so that you can evaluate your model before testing it on test.csv with Kaggle.
• Data augmentation and regularization.
• Cross-validation and hyperparameter tuning.( Learning rate decay, Early stopping on the validation set).
• Model ensemble.