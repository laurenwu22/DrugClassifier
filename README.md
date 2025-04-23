Our project uses a quantifiable database for drug consumption from the UCI Machine Learning Repository. Database contains records for 1885 respondents. For each respondent 12 attributes are known: Personality measurements which include NEO-FFI-R (neuroticism, extraversion, openness to experience, agreeableness, and conscientiousness), BIS-11 (impulsivity), and ImpSS (sensation seeking), level of education, age, gender, country of residence and ethnicity. 

All input attributes are originally categorical and are quantified. After quantification values of all input features can be considered as real-valued. In addition, participants were questioned concerning their use of 18 legal and illegal drugs (alcohol, amphetamines, amyl nitrite, benzodiazepine, cannabis, chocolate, cocaine, caffeine, crack, ecstasy, heroin, ketamine, legal highs, LSD, methadone, mushrooms, nicotine and volatile substance abuse and one fictitious drug (Semeron) which was introduced to identify over-claimers. 

For each drug they have to select one of the answers: never used the drug, used it over a decade ago, or in the last decade, year, month, week, or day. Database contains 18 classification problems. Each of independent label variables contains seven classes: "Never Used", "Used over a Decade Ago", "Used in Last Decade", "Used in Last Year", "Used in Last Month", "Used in Last Week", and "Used in Last Day".

Detailed description of database and process of data quantification are presented in E. Fehrman, A. K. Muhammad, E. M. Mirkes, V. Egan and A. N. Gorban, "The Five Factor Model of personality and evaluation of drug consumption risk.," arXiv https://arxiv.org/abs/1506.06297, 2015.

In data pre-processing, we created pleiad groups for different drug uses (ecstasy, heroin, and benzodiazepine), as well as using a “week-based” approach for drug usage. 

For our project, we wanted to test if predicting drug consumption was possible and to identify the most informative attributes using data mining methods. Implementing a logistic regression model, we were able to build an acceptable model predicting for ecstasy use, but not for benzodiazepine and heroin use. We are also able to validate that heroin and benzodiazepine use are strongly correlated with one another.

This dataset is good to work with imbalanced data for a social science setting.
