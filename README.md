# Wine Quality Dataset Analysis

#### Academic citation: 
>P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.
>Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

## Objectives and assumptions
#### Objectives
I will frame the objectives of this analysis as the answers to questions. Those questions are: 
1. What are the most important factors in making good quality (6+) wine? 
2. What are the most important factors in making poor quality (4-) wine?
3. What is the most popular type of wine? 
4. How well can the quality of wine be predicted from physicochemical measurements?

#### Assumptions
1. That not all features contribute equally to quality. 
2. That markets work to the degree such that the most popular types of wine are demanded more, and therefore are supplied more. 
3. The data is an accurate sampling of wines in Portugal in 2009. 
4. That human taste in wine is strongly affected by the physicochemical properties of wine. 
5. That the quality ratings of expert wine tasters would correlate with the quality ratings of casual wine drinkers. 


## EDA
The EDA found nothing significant that suggests I should remove any features, or that I would have any significant difficulty with any of them. They're all numerical and there's no missing data. Nothing in the initial EDA answers any of the objective-questions, though the low linear correlations between the target variable and all the prediction variables is vaguely suggestive of the answer to objective-question 4 being 'poorly'. 

