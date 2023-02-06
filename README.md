# FBI-BJS Crime Data Analysis Project
This project aims to analyze patterns of crime in the United States using publicly available data from the Federal Bureau of Investigation (FBI) and the Bureau of Justice Statistics (BJS). The project will be divided into 4 parts: Data Collection and Cleaning, Exploratory Analysis, Answering Questions, and Hypothesis Testing.

# Part 1: Data Collection and Cleaning
## 2.1 Data Collection
National crime victimization survey (NCVS) data:
Use the NCVS data API (available without an API key) to download as much of the personal crime victimization and personal population data as is available for all years (limit >= 1000000).
Read the codebook carefully to understand the variables and their meanings.
NIBRS Reported offense count data:
Use the FBI Crime Data API (apply for an API key first) to download the state-level NIBRS offense count data for all available states and offenses.
Get a list of state abbreviations and names either manually or through a separate API call.
Collect the data by repeated requests for all possible states and offenses to get the counts.
Read the offense definitions and categories carefully.
Recidivism data for the state of Georgia [2013-2015]:
Use the SODAAPI to download as much of the NIJ's recidivism data as is available (limit >= 1000000).
Read the data description and codebook carefully.
Firearm laws per state:
Download the Firearm laws per state dataset and codebook.
Read the codebook to understand the structure of the dataset and the purpose of each referenced law.
## 2.2 Data Cleaning:
Perform necessary cleaning and restructuring on the data, with the following requirements for the final output:

Descriptive column/variable names.
Numerically-encoded categories must be replaced with descriptive strings in the analysis outputs and plots.
# Part 2: Exploratory Analysis
Use statistics and plots to investigate the following:

National criminal offense rates per year across all available years for the top five most frequent offense categories.
Average percentage of violent crimes relative to total crime per state over all available years.
National homicide rates, as well as total violent crime rates per year over all years.
The frequency of non-fatal crime incidents in relation to victim demographics.
The frequency of non-fatal crime incidents in relation to offender demographics.
The relationship between the victim's education level, their gross household income, and their rate of victimization.
All analysis points must be accompanied by commentary and at least one appropriate visualization.

# Part 3: Answering Questions
Use appropriate statistics and plots to answer the following questions:

Which type of non-fatal crime is the most under-reported? Is there an association between the offender-victim relationship and the likelihood of a crime being reported?
Who are the people (the demographic segment) that appear to be most at risk of violent victimization? Who is the least at risk?
Of all victims of non-fatal crimes who suffer an injury, which demographic is the most likely to receive medical attention at the scene? Which is the least likely?
4. Which class of crimes is associated with the highest rate of
same-offense-recidivism; i.e. prison re-entry for the same offense within 3
years of release?
5. Are prisoners who are younger at the time of release more or less likely to
reoffend than those who are older?

# PART 4: Hypothesis Testing
Claim: “U.S. states that implement stricter firearm control laws, have lower

violent crime rates on average”

## 4.1 Formulate a hypothesis test to assess the validity of this claim
given the available data:
● State the test you will use and justify your choice.
● Clearly state the hypotheses.
● Conduct the test and report the result.
● Make a conclusion as to the validity of the claim, assume a significance
level of 0.05.

4.2 Come up with your own claim and formulate a hypothesis test to
assess it following in the same steps.


# PART 5: Predictive Modeling:

5.1 Using one or more machine learning techniques, build a predictive model that
will help predict the likelihood of an individual being a victim of a non-fatal crime.

5.2 Evaluate the model using appropriate metrics and techniques (such as
cross-validation).

5.3 Use the model to make predictions on new data.

5.4 Present the results of the predictive model, including important features and
their influence on the prediction.

# University of Science and Technology
# Communications & Information Engineering Program
# CIE 457: Statistical inference and data analysis
This was the final project for the course CIE 457: Statistical inference and data analysis. The goal of the project was to use publicly available crime data from the Federal Bureau of Investigation (FBI) and the Bureau of Justice Statistics (BJS) to analyze crime patterns in the U.S. The project was divided into six parts: Data Collection and Cleaning, Exploratory Analysis, Answering Questions, Hypothesis Testing, Predictive Modeling, and Conclusion.

In the Data Collection and Cleaning section, we collected and cleaned the data using various APIs, including the NCVS data API, the FBI Crime Data API, the SODA API, and a dataset on firearm laws per state. In the Exploratory Analysis section, we used statistics and plots to investigate national criminal offense rates, violent crime rates, homicide rates, non-fatal crime incidents in relation to victim and offender demographics, and the relationship between the victim's education level, income, and rate of victimization.

In the Answering Questions section, we used appropriate statistics and plots to answer questions about crime reporting, risk of victimization by demographics, medical attention for victims, recidivism rates, and reoffending rates by age. In the Hypothesis Testing section, we formulated a hypothesis test to assess the validity of the claim that states with stricter firearm control laws have lower violent crime rates on average.

In the Predictive Modeling section, we built a predictive model using machine learning techniques to predict the likelihood of an individual being a victim of a non-fatal crime. The results of the predictive model, including important features and their influence on the prediction, were presented.

In the Conclusion section, we summarized the results of the entire project, discussed the limitations, and suggested areas for future research. The code and data used in the project were stored in a public Github repository and a Readme file was included to outline the purpose and structure of the code and data.
