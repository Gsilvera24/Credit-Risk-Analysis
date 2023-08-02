## Background

Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. In this repository we will use various techniques to train and evaluate models with imbalanced classes. We will use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Using knowledge of the imbalanced-learn library, we will use a logistic regression model to compare two versions of the dataset. First, we will use the original dataset. Second, we will resample the data by using the `RandomOverSampler` module from the imbalanced-learn library.

For both cases, we'll get the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.
