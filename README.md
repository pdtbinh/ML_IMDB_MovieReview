# Machine Learning Project

# Serie 1: IMDB movie review sentiment classification

Welcome to my personal machine learning project serie!

This machine learning project will explore the IMDB movie review sentiment classification dataset and try out a few different machine learning approaches to find out which perform the best on such problem. The first episode will focus on training and testing (non-recurrent) neural netowrk models with 3 simple neural networks. This is a naive approach since there are many other state-of-the-art techniques to handle Natural Language Processing problems like this one. However, I find it reasonable to start with such simple approach to get a better sense on the data first and also see how much other techniques designed for NLP could do better. The project will develop models to improve initial Testing Accuracy from 79% (episode 1) to approximately 89% (episode 5).

All detailed info is included within the Jupiter notebook. There is also a PDF version in case the notebook file does not work.

### Overview project structure:
- Investigating datasets
- Data preprocessing
- Creating Neural Network models
- Training and Validating models
- Testing models with test set
- Model problem analysis

### Notes: 
- Techniquely, while creating models, I should have fed the models with parameters 'X_train_input', 'Y_train_input', and then input the parameters with datasets 'x_train_new', 'y_train_new', instead of feeding directly the models with the datasets. However, since there're only 1 training set in this episode, it does not make any difference.
- Folders 'm1', 'm2', 'm3' are to store weight and bias parameters from the networks that I have trained.
