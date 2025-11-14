Naive Bayes Text Classification – 5-Fold Cross-Validation

This project implements Multinomial Naive Bayes and Bernoulli Naive Bayes models for text classification using the dataset data.tsv.
The notebook used for this task is 2312res547_Code.ipynb.

The goal is to perform 5-fold cross-validation and report:

Accuracy for each fold

F1-score for each fold

Average Accuracy

Average F1-score

📂 Project Files

2312res547_Code.ipynb — contains all code for preprocessing, model training, and evaluation.

data.tsv — dataset containing text samples and labels.

README.md — documentation (this file).

📊 Methodology

Load the dataset from data.tsv.

Split the data into 5 folds.

Train the following models on each fold:

Multinomial Naive Bayes

Bernoulli Naive Bayes

Compute:

Accuracy

F1-score

Report per-fold metrics and averages.

✅ Results
Multinomial Naive Bayes

Accuracy (5 folds):
0.65625, 0.6625, 0.675, 0.675, 0.68125

Average Accuracy: 0.67

F1-scores (5 folds):
0.74178, 0.74528, 0.73469, 0.74509, 0.70857

Average F1-score: 0.73508

Summary:
Multinomial Naive Bayes performed consistently well, achieving 67% accuracy and a strong average F1-score of 0.735. This indicates good precision-recall balance for this text classification task.

Bernoulli Naive Bayes

Accuracy (5 folds):
0.60625, 0.63125, 0.58125, 0.68125, 0.60625

Average Accuracy: 0.62125

F1-scores (5 folds):
0.73191, 0.75105, 0.71489, 0.78661, 0.71748

Average F1-score: 0.74039

Summary:
Bernoulli Naive Bayes shows slightly lower accuracy (62.1%) but surprisingly achieves a higher average F1-score (0.740). This suggests the model handles class balance well despite lower accuracy.

📌 Conclusion

Multinomial NB gives the best accuracy (0.67).

Bernoulli NB has a slightly better F1 score (0.740).

Both models perform reliably for this dataset, each with different strengths.

This project demonstrates how Naive Bayes models behave differently depending on text representation and provides a clear comparison using 5-fold cross-validation.
