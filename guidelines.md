# Evaluation Criterion
The evaluation of the project will mostly focus on the correctness and completeness of the methodology employed, rather than on the accuracy of the trained model or training time. The reproducibility of the results and the quality of the report also play a substantial role in the final evaluation.

# Basic Instructions
+ Besides complying with the project’s specifications, students must follow a sound methodology both in the data preprocessing phase and when running the experiments. In particular, no data manipulation should depend on test set information, and the validation of the performance of each model must use appropriate techniques (e.g., cross-validation).
+ Hyperparameter tuning should focus on regions of values where performance trade-offs are explicit and should be fully automatic. Instead of simply picking the best hyperparameters, you should apply sound techniques (e.g., grid search with cross-validation) to compute the best hyperparameters and describe this process in the report.
+ Any implementation must use Python 3 (any other choice must be preliminarily agreed upon with the teaching assistants). Using Python 3 within Jupyter Notebooks is allowed.
+ The report (in PDF) and the project code must be submitted in a public GitHub/GitLab repository. Length: about 10-15 pages.

# Project Track: [RPS] Building a CNN for Rock-Paper-Scissors Classification
## Objectives
+ Develop a Convolutional Neural Network (CNN) to accurately classify images of hand gestures corresponding to the Rock-Paper-Scissors game.
+ Follow sound statistical and machine learning practices for data preprocessing, model training, hyperparameter tuning, and evaluation.
+ Optionally, assess the generalization capabilities of the model using custom images of your own hand gestures.
+ Given the size of the dataset and the complexity of the task, prioritize achieving a reasonable training time rather than maximizing accuracy.

## Dataset
Use the Rock-Paper-Scissors dataset available on Kaggle: [Rock-Paper-Scissors Dataset](https://www.google.com/url?q=https://www.kaggle.com/datasets/drgfreeman/rockpaperscissors&sa=D&source=editors&ust=1792157933653532&usg=AOvVaw0u6oN0wXVmVChvEPNzz_Zb)

## Requirements
Your assignment submission must include the following:

1. Data Exploration and Preprocessing
+ Explore the dataset thoroughly and provide a summary of your observations.
+ Perform necessary preprocessing steps:
  + Image resizing and normalization.
  + Optionally, data augmentation techniques.
  + Splitting the data into training and test sets appropriately.
2. CNN Architecture and Training
  + Design at least 3 NN architectures with incremental complexity. Evaluate and compare the performance of each one.
  + Clearly define and justify your CNN architectures (number and types of layers, activation functions, pooling methods, dropout layers).
  + Train your CNNs using an appropriate optimizer and loss function.
  + Demonstrate proper hyperparameter tuning (e.g., learning rate, number of epochs, batch size) for at least one of your models.
3. Evaluation and Analysis
  + Evaluate your model performance using suitable metrics such as accuracy, precision, recall, and F1-score.
  + Provide visualizations of training curves (loss and accuracy).
  + When reasonable, conduct an analysis of misclassified examples to understand potential model limitations.
  + Discuss the presence or absence of overfitting and underfitting at any point in the training pipeline.
