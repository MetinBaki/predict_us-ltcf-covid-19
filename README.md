# Predicting COVID-19 Cases In US Long-Term Care Facilities: An Empirical Study Using Epidemiological Data

## Objectives
The focus of this project is to identify factors that increase the probability of COVID-19 cases in nursing homes and to provide an exemplary concept for applying the findings using machine learning algorithms to allow future research.

## Subjects
This study investigates all active, and Medicare and Medicaid certified nursing home facilities in the United States (excluding Alaska and Washington, DC) that reported the number of COVID-19 infections and fatalities among their residents and staff up to August 02nd, 2020 (13,069 nursing homes). The required information about nursing homes and the respective epidemiological data was obtained from nine datasets retrieved from three state and publicly accessible databases.

## Methods
The dependant variables are the reported COVID-19 infections and fatalities among nursing home residents and staff. The independent variables are clustered into five different themes: (1) facility characteristics, (2) rating, deficiencies and fines, (3) nurse staffing, (4) resident demographics and (5) external factors. A total of seven machine learning models were tested. The models are logistic regression, nearest neighbours, Gaussian naïve Bayes, support vector machines, decision trees, random forests and neural networks.

## Results
The findings show evidence of a relationship between COVID-19 infections and fatalities and (1) the size of a nursing home, (2) the facility's age, (3) whether a nursing home is for-profit, (4) whether a nursing home is urban or rural, (5) the number of federal deficiencies, (6) the total amount of fines, (7) the concentration of residents with Medicaid, (8) the share of residents from a racial or ethnic minority, (9) the excess of beds in the respective county of a nursing home, (10) the number of infections per 100,000 people in a county, (11) the number of deaths per 100,000 people in a county, (12) the occupancy rate, (13) the overall CMS facility rating, (14) the total reported registered nurse (RN) staffing levels, (15) the total reported nurse staffing levels and (16) its competitive environment (Herfindahl Index). Whether a nursing home was a chain was not significantly related to COVID-19 cases and deaths. Even though the for-profit status, the urban location, the rating, the number of serious federal deficiencies and infection control deficiencies and the total amount of fines paid showed a statistical significance, these factors only marginally contributed to the machine learning model.
