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
