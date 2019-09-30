# stackOverflowTrends
notebooks and data for mutliyear descriptive analysis of StackOverflow develop surveys

# libraries used
numpy, pandas, seaborn, matplotlibs pylot and ticker

# files contained in repo:
1) 2017_survey_results_public: Stack Overflow developer survey results for 2017 (see https://insights.stackoverflow.com/survey)
2) 2017_survey_results_schema: the schema for the 2017 data
3) 2018_survey_results_public: 2018 dataset
4) 2018_survey_results_schema: 2018 schema
5) 2019_survey_results_public: 2019 dataset
6) 2019_survey_results_schema: 2019 schema.
7) "Exploring language popularity trends in the Stack Overflow developer survey" notebook: main code for data import, cleaning, analysis and visualisation

# summary of findings:
https://medium.com/@ctreacy/exploring-language-popularity-trends-with-the-stack-overflow-annual-developer-surveys-b03a6ceab5aa

Our aim in this notebook was to use the yearly survey data to explore the factors that affect programming language popularity trends. More precisely, we aimed to:

track the general popularity of languages from 2017 to 2019
Investigate whether languages highly desired among developers for a given year are indicative of popular "worked" languages in following years
Investigate whether language popularity with student and professional subgroups of developers was driving the trends we saw in the general population.
In our first visualisation, we saw that the top ten languages year on year were not entirely static, with some languages dropping out of the top ten and the rise of python over Java and shell scripting languages being indicative of this. We also discussed the changing categorisation of languages year on year in the survey results and the implications of this in our analysis.

Our second visualisation, we saw that language desirability in 2018 did tend to track actual popularity in 2019, and pythons desirability in 2018 did seem to hint at its actual jump in popularity over java and shell scripting in 2019. However, we also stressed that no concrete relationship could be inferred from our descriptive statistics alone.

Finally, we saw that that the student/non-student demographic dynamics per language in 2018 and 2019 did not provide much insight into why we saw certain langauges rise and fall in popularity from 2018 to 2019; these proportions were relatively static for each language between 2018 and 2019, including python, Java and Bash/Shell/Powershell.

# acknowledgments
https://gist.github.com/jlln/338b4b0b55bd6984f883
https://stackoverflow.com/questions/14270391/python-matplotlib-multiple-bars
https://pstblog.com/2016/10/04/stacked-charts
