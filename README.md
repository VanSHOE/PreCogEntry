# Output Directory Structure

```
│
└───output
    ├───genderDomination
    ├───IncumbencyAnalysis
    └───notaAnalysis
```

## Introduction

Welcome to the Indian Elections Analysis project. This is an exhaustive research study examining various aspects of the Indian electoral process. The purpose of this initiative is to cast light on patterns and behaviours manifested by electors, candidates, and political parties across the nation, which may have substantial implications for the democratic process.

# Analysis

This study consists of five distinct analyses:

1. **Gender-Based Voting Analysis**: This analysis investigates how much each state's voting patterns are influenced by gender. It explores which gender receives more votes and whether there are any discernible trends that can explain these patterns. `GenderAnalysis.ipynb` contains the code for this analysis.

2. **Incumbent Party Success Analysis**: This section looks into how often each state re-elects the incumbent party. It offers insights into the conditions that favor the re-election of ruling parties, providing a comprehensive understanding of voter behavior towards political continuity. `IncumbencyAnalysis.ipynb` contains the code for this analysis.

3. **NOTA (None of the Above) Analysis**: Here, we study the prevalence and distribution of NOTA votes across different states. This analysis will provide insights into voter dissatisfaction with the available candidate options and potential electoral apathy. `NotaAnalysis.ipynb` contains the code for this analysis.

4. **Binary Literacy Analysis**: This analysis investigates the proportion of literate versus illiterate candidates in each state's elections. The aim is to provide an overview of the literacy levels among the candidate pool, providing insights into the educational background of our potential leaders. `Literacy_Analysis.ipynb` contains the code for this analysis.

5. **Scaled Literacy Analysis**: Building on the binary literacy analysis, this study further categorizes the candidates into more detailed literacy levels such as 'Illiterate', '8th pass', 'Graduate', and more. This allows us to understand the distribution of candidates' educational qualifications in each state, presenting a clearer picture of the educational diversity among candidates. `Literacy_Analysis.ipynb` contains the code for this analysis.

In the 'output' directory, you'll find three subdirectories - 'genderDomination', 'IncumbencyAnalysis', and 'notaAnalysis'. Each of these directories contains two types of files:

Text Files (.txt): These files contain the raw data used to create the heatmaps. They represent the data in a structured, text-based format that can be easily read and processed by various programs.

Image Files (.png): These are the heatmaps generated from the text files. They provide a visual representation of the data, making it easier to identify patterns and trends.

## Insights

While data has been provided for all elections, the analysis will primarily focus on insights drawn from the 2019 and 2014 elections for the sake of brevity apart from incumbency since this feature requires a range of elections to be considered.

### Gender-Based Voting Analysis

1. **Preference for Male Candidates**:

   In 2014, several regions showed a significant preference for male candidates. This preference was most notable in 'Daman & Diu', 'Lakshadweep', 'Arunachal Pradesh', 'Mizoram', and 'Nagaland' - all scoring a perfect 10. Other regions such as 'Dadra & Nagar Haveli', 'Goa', 'Manipur', 'Meghalaya', 'Puducherry', and 'Tripura' also exhibited a strong preference for male candidates. This could have been due to traditional social norms that favored male leadership or the dominance of male candidates on the ballot.

   By 2019, regions such as 'Arunachal Pradesh' shifted from a strong male preference to a relatively balanced gender preference, potentially due to growing awareness and promotion of gender equality. Conversely, 'Jammu & Kashmir' transitioned from a male preference in 2014 to a female preference in 2019, possibly as a result of successful female candidates or targeted campaigns to increase female representation.

2. **Balanced Voting**:

   In 2014, several regions such as 'Bihar', 'Delhi', 'Karnataka', 'Maharashtra', 'Rajasthan', 'Tamil Nadu', 'Uttar Pradesh', and 'Uttarakhand' showed balanced voting patterns. This suggests that voters in these regions might have been more focused on candidates' policies or party affiliations rather than their gender.

   By 2019, some of these regions such as 'Bihar' and 'Delhi' demonstrated a shift towards a preference for female candidates. This change might be attributed to successful efforts to promote women's political participation, changing societal attitudes towards female leaders, or an increase in the number of compelling female candidates.

3. **Preference for Female Candidates**:

   In 2014, no specific region showed a pronounced preference for female candidates.

   However, by 2019, 'Chandigarh', 'Tripura', 'Dadra & Nagar Haveli and Daman & Diu', and 'West Bengal' had developed a strong preference for female candidates. Regions such as 'Chandigarh' and 'Uttarakhand' also exhibited significant shifts towards female preference compared to 2014. These changes might be due to effective advocacy for female representation, changes in societal attitudes towards female leadership, or the influence of successful female politicians.

   These patterns indicate that gender preferences in India's electoral politics are dynamic and can change significantly over a relatively short period. Understanding these trends and the factors that influence them is crucial for promoting gender equity in political representation.

### NOTA Analysis

1. **Increase in NOTA vote share**:

   Several regions like 'Andhra Pradesh', 'Bihar', 'Chandigarh', 'Chhattisgarh', 'Dadra & Nagar Haveli', 'Daman & Diu', 'Goa', 'Gujarat', 'Himachal Pradesh', 'Jharkhand', 'Odisha', 'Punjab', 'Tamil Nadu', 'Uttarakhand', and 'Uttar Pradesh' experienced an increase in NOTA vote share from 2014 to 2019. This could be attributed to voters' dissatisfaction with the available candidates or political parties, or increasing awareness about the NOTA option since it was introduced in 2009.

2. **Decrease in NOTA vote share**:

   A few regions like 'Arunachal Pradesh', 'Assam', 'Karnataka', 'Lakshadweep', 'Meghalaya', 'Mizoram', 'Nagaland', 'Sikkim', and 'Tripura' saw a decrease in NOTA vote share from 2014 to 2019. This may suggest that voters in these regions were more satisfied with the candidates or parties available in 2019 as compared to 2014 or were less aware or less inclined to use the NOTA option in 2019.

3. **Negligible change in NOTA vote share**:

   Regions like 'Delhi', 'Haryana', 'Madhya Pradesh', and 'Maharashtra' showed minimal changes in NOTA vote share between 2014 and 2019.

In summary, NOTA vote shares exhibit regional variations and changes over time, reflecting the evolving political climate, voter awareness, and satisfaction levels. This is a critical aspect of electoral analysis, providing insights into voter behavior beyond the choices of specific candidates or parties.

### Incumbency Analysis

The incumbency rates for different regions of India, analyzed across all elections and the last five elections, illustrate a compelling landscape of electoral dynamics.

#### All Elections

On the higher end of the incumbency spectrum, regions like Lakshadweep (71.43%) and A & N Islands (57.14%) show a marked preference for retaining their incumbents, suggesting strong voter loyalty or satisfaction with the status quo. In contrast, areas like Jammu & Kashmir (28.21%) have demonstrated a proclivity towards electing new candidates over incumbents, hinting at possible dissatisfaction with existing leadership or a desire for change.

In the middle of the spectrum, states like West Bengal (49.52%), Goa (38.89%), and Uttarakhand (40%) suggest a more balanced or cyclical political landscape where incumbents and newcomers both have reasonable chances of success.

#### Last 5 Elections

Comparatively, in the last five elections, Lakshadweep has seen a decrease in its incumbency rate to 40%, indicating a potential shift in voter sentiment. Similarly, Jammu & Kashmir maintains its low incumbency rate at 30%, underscoring a consistent trend of favoring fresh faces in political positions.

However, certain regions have shown a substantial rise in incumbency rates over the last five elections. For instance, Goa's incumbency rate increased to 50%, suggesting growing support for incumbent leaders. Other states like Gujarat (52.31%) and Maharashtra (45%) also showcase an upward trend in their incumbency rates.

Conversely, Tamil Nadu's incumbency rate has dwindled to 21.03% in the recent elections, indicating a stronger inclination towards new leaders.

#### Comparative Analysis

Comparing the overall data with the data from the last five elections, a nuanced picture of changing political dynamics emerges. Some regions have demonstrated shifts in their voting patterns, either favoring new leadership over incumbency, as seen in Lakshadweep, or showing increased support for incumbents, as in the case of Goa.

In some areas, voting patterns appear to have remained relatively stable across all elections and the last five, such as Jammu & Kashmir, with consistently low incumbency rates, and West Bengal, with nearly unchanged rates.

# Classification Analysis

This project also includes a classification task, conducted in the Jupyter notebook named `classification.ipynb`. In this task, we aim to predict whether a candidate is a 'Turncoat', meaning they have switched parties. In the ever-evolving landscape of politics, party loyalty is an intriguing aspect to study. Candidates switching their allegiances, known as 'Turncoats', often pose intriguing questions regarding political behavior and strategy. This analysis aims to unravel the factors that might influence such decisions, thus providing a deeper understanding of the political dynamics at play.

The features used in this classification task are as follows:

- `State_Name`: The name of the state where the election is held.
- `Party`: The political party to which the candidate belongs.
- `No_Terms`: The number of terms the candidate has served previously.

These features were selected as a subset of the original data based on rigorous feature selection procedures, to ensure that our model focuses on the most relevant information.

By predicting 'Turncoat' status based on these features, this classification task helps to shed light on the patterns and behaviors that may influence a candidate's likelihood to switch parties.

The results of this classification task are stored in the notebook itself and presented down below, and the code for the task is also included in the notebook.

| Model               | Accuracy | Precision (Class 0) | Recall (Class 0) | F1-score (Class 0) | Precision (Class 1) | Recall (Class 1) | F1-score (Class 1) |
| ------------------- | -------- | ------------------- | ---------------- | ------------------ | ------------------- | ---------------- | ------------------ |
| Logistic Regression | 0.751    | 0.70                | 0.88             | 0.78               | 0.84                | 0.62             | 0.71               |
| Decision Tree       | 0.791    | 0.80                | 0.78             | 0.79               | 0.79                | 0.80             | 0.79               |
| Random Forest       | 0.797    | 0.82                | 0.76             | 0.79               | 0.78                | 0.84             | 0.80               |
| Gradient Boosting   | 0.804    | 0.85                | 0.73             | 0.79               | 0.77                | 0.88             | 0.82               |
| SVM                 | 0.634    | 0.60                | 0.77             | 0.68               | 0.68                | 0.50             | 0.58               |
| KNN                 | 0.787    | 0.82                | 0.74             | 0.78               | 0.76                | 0.84             | 0.80               |
| Naive Bayes         | 0.667    | 0.62                | 0.88             | 0.72               | 0.79                | 0.46             | 0.58               |

Based on the high accuracy of the models trained in this analysis, we can confidently state that the selected features - `State_Name`, `Party`, and `No_Terms` - appear to have significant predictive power when it comes to determining a candidate's likelihood of switching parties.

`State_Name` plays a crucial role, potentially reflecting regional influences, cultural differences, or state-specific political dynamics that may affect a candidate's party affiliation.

`Party` can also be a decisive factor. It is plausible that the candidate's alignment with party ideologies, the party's popularity, or its stance on specific issues can influence their decision to remain or switch.

`No_Terms` is particularly noteworthy, given its positive correlation of 0.211 with the 'Turncoat' status. This indicates that as the number of terms a candidate has served increases, so does the likelihood of them switching parties. This could suggest that candidates with more terms might be exploring new strategies for political success, and switching parties could be one such strategy. It could also indicate that experienced politicians are more confident in their ability to retain their voter base despite a party switch.

This analysis provides a data-driven foundation for understanding the phenomenon of party switching. It could be an instrumental tool for political parties to anticipate and strategize for such events. Further, by improving our understanding of political behavior, these insights can also contribute to a more informed and engaged electorate.
