# AIML Case Studies
Covered fundamental case studies from Statistical analysis, EDA, feature engineering to machine learning and deep learning models..

## 01. Applied Statistics
    Statistical analysis using graphs and distributions
    
    Dataset: Insurance (1000 x 7)

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

    Dataset: users (48k x 15)
    
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
            76% (Naive Bayes) to 83% (SVC)
        Precision
            class 0
            class 1
        Recall
            class 0
            class 1

## 03. Ensemble Techniques
    Apply ensemble methods on classification models and evaluate performances

    Dataset: bank users (45k x 17)

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
            62% to 87%
        Precision
            class 0
            class 1
        Recall
            class 0
            class 1
        

## 04. Unsupervised Learning
    Perform classification on an unsupervised dataset and evaluate performance

    Dataset: vehicles (~1000 x 19)

    Data preprocessing
        missing value handling

    EDA
        pairplot
        boxplot

    Data preprocessing
        z-score on independent attributes to scale the values
    
    Feature engineering
        PCA
            features reduced to 6
    
    Model Training
        SVC model without PCA
        SVC model with PCA
    
    Performance evaluation
        Accuracy score
            92% without PCA
            78% with PCA


## 5. Featurization, Model selection and Tuning

## 6. Recommendation Systems

## 7. Neural Network and Deep Learning

## 8. Computer Vision - Face Detection

## 9. Computer Vision - Face Recognition

## 10. NLP Statistical - Blog authorship corpus

## 11. NLP - Sentiment Classification

## 12. NLP - Sarcasm Detection

## 13. NLP - Automatic Ticket Assignment