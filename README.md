# AIML Case Studies
Covered fundamental case studies from Statistical analysis, EDA, feature engineering to machine learning and deep learning models..

## 01. Applied Statistics
    Statistical analysis using graphs and distributions
    
    Dataset: Insurance

    Data preprocessing
        missing value handling
    EDA
        5-point summary of numerical attributes
        Univariate analysis
            distplot for distribution for numerical attributes
            stripplot for distribution for categorical attributes
        Bivariate analysis
            pairplot for bi-variate analysis

## 02. Supervised Learning
    Classify using supervised learning models on training dataset and evaluate performances on test dataset

    Dataset: users
    
    Data preprocessing
        concatenate 2 datasets
        missing value handling
    EDA
        Univariate analysis
            distplot
            value counts for categorical attributes
        Bivariate analysis
            Pairplot
    Feature engineering
        Drop attributes with most values 0, and so not useful in model training
    Model training
        Prepare training set and test set
        Train models
            Logistic regression
            Naive Bayes
            KNN classifier
            SVC
                linear kernel
                rbf kernel
                poly kernel
                sigmoid kernel
    Performance evaluation on test data
        Model score
        confusion matrix
        Accuracy
        Precision
            class 0
            class 1
        Recall
            class 0
            class 1

## 03. Ensemble Techniques
    Apply ensemble methods on classification models and evaluate performances

    Dataset: bank users

    EDA
        5-point summary of numerical attributes
        Univariate analysis
            distplot
            boxplot
        Bivariate analysis
            pairplot
    Data preprocessing
        outlier handling
        Encoding categorical columns
    Model training
        Standard classification models
            Decision tree classifier
            Regularized decision tree classifier
            Naive Bayes
        Ensemble methods
            Bagging classifier on regularized decision tree model
            Random forest classifier
            Bagging classifier on Naive bayes model
            Adaboost classifier on Naive bayes model
    Performance evaluation on test data
        Confusion matrix
        Accuracy score
        Precision
            class 0
            class 1
        Recall
            class 0
            class 1
        

## 04. Unsupervised Learning
    Perform classification on an unsupervised dataset and evaluate performance

    Dataset: vehicles

    Data preprocessing
        missing value handling

    EDA
        pairplot
        boxplot

    Data preprocessing
        z-score on independent attributes to scale the values
    
    Feature engineering
        PCA
    
    Model Training
        SVC model without PCA
        SVC model with PCA
    
    Performance evaluation
        Accuracy score


## 5. Featurization, Model selection and Tuning

## 6. Recommendation Systems

## 7. Neural Network and Deep Learning

## 8. Computer Vision - Face Detection

## 9. Computer Vision - Face Recognition

## 10. NLP Statistical - Blog authorship corpus

## 11. NLP - Sentiment Classification

## 12. NLP - Sarcasm Detection

## 13. NLP - Automatic Ticket Assignment