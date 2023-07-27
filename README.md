# Directory Structure

```
├───data
│   └───submission
└───output
    ├───genderDomination
    ├───IncumbencyAnalysis
    └───notaAnalysis
```

## Introduction

Welcome to the Indian Elections Analysis project. This is an exhaustive research study examining various aspects of the Indian electoral process. The purpose of this initiative is to cast light on patterns and behaviours manifested by electors, candidates, and political parties across the nation, which may have substantial implications for the democratic process.

This study consists of five distinct analyses:

1. **Gender-Based Voting Analysis**: This analysis investigates how much each state's voting patterns are influenced by gender. It explores which gender receives more votes and whether there are any discernible trends that can explain these patterns. `GenderAnalysis.ipynb` contains the code for this analysis.

2. **Incumbent Party Success Analysis**: This section looks into how often each state re-elects the incumbent party. It offers insights into the conditions that favor the re-election of ruling parties, providing a comprehensive understanding of voter behavior towards political continuity. `IncumbencyAnalysis.ipynb` contains the code for this analysis.

3. **NOTA (None of the Above) Analysis**: Here, we study the prevalence and distribution of NOTA votes across different states. This analysis will provide insights into voter dissatisfaction with the available candidate options and potential electoral apathy. `NotaAnalysis.ipynb` contains the code for this analysis.

4. **Binary Literacy Analysis**: This analysis investigates the proportion of literate versus illiterate candidates in each state's elections. The aim is to provide an overview of the literacy levels among the candidate pool, providing insights into the educational background of our potential leaders. `Literacy_Analysis.ipynb` contains the code for this analysis.

5. **Scaled Literacy Analysis**: Building on the binary literacy analysis, this study further categorizes the candidates into more detailed literacy levels such as 'Illiterate', '8th pass', 'Graduate', and more. This allows us to understand the distribution of candidates' educational qualifications in each state, presenting a clearer picture of the educational diversity among candidates. `Literacy_Analysis.ipynb` contains the code for this analysis.

In the 'output' directory, you'll find three subdirectories - 'genderDomination', 'IncumbencyAnalysis', and 'notaAnalysis'. Each of these directories contains two types of files:

Text Files (.txt): These files contain the raw data used to create the heatmaps. They represent the data in a structured, text-based format that can be easily read and processed by various programs.

Image Files (.png): These are the heatmaps generated from the text files. They provide a visual representation of the data, making it easier to identify patterns and trends.

# Classification Analysis

This project also includes a classification task, conducted in the Jupyter notebook named `classification.ipynb`. In this task, we aim to predict whether a candidate is a 'Turncoat', meaning they have switched parties.

The features used in this classification task are as follows:

- `State_Name`: The name of the state where the election is held.
- `Party`: The political party to which the candidate belongs.
- `No_Terms`: The number of terms the candidate has served previously.

These features were selected as a subset of the original data based on rigorous feature selection procedures, to ensure that our model focuses on the most relevant information.

By predicting 'Turncoat' status based on these features, this classification task helps to shed light on the patterns and behaviors that may influence a candidate's likelihood to switch parties.

The results of this classification task are stored in the notebook itself, and the code for the task is also included in the notebook.

| Model               | Accuracy | Precision (Class 0) | Recall (Class 0) | F1-score (Class 0) | Precision (Class 1) | Recall (Class 1) | F1-score (Class 1) |
| ------------------- | -------- | ------------------- | ---------------- | ------------------ | ------------------- | ---------------- | ------------------ |
| Logistic Regression | 0.751    | 0.70                | 0.88             | 0.78               | 0.84                | 0.62             | 0.71               |
| Decision Tree       | 0.791    | 0.80                | 0.78             | 0.79               | 0.79                | 0.80             | 0.79               |
| Random Forest       | 0.797    | 0.82                | 0.76             | 0.79               | 0.78                | 0.84             | 0.80               |
| Gradient Boosting   | 0.804    | 0.85                | 0.73             | 0.79               | 0.77                | 0.88             | 0.82               |
| SVM                 | 0.634    | 0.60                | 0.77             | 0.68               | 0.68                | 0.50             | 0.58               |
| KNN                 | 0.787    | 0.82                | 0.74             | 0.78               | 0.76                | 0.84             | 0.80               |
| Naive Bayes         | 0.667    | 0.62                | 0.88             | 0.72               | 0.79                | 0.46             | 0.58               |
