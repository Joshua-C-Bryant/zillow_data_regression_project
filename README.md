# Regression Project: Estimating Home Value

### Goal:
To be able to predict the values of **single unit properties** that the tax district assesses using the property data from those with a transaction during the "hot months" (in terms of real estate demand) of **May-August, 2017**.

### Project Goals:
- Use machine learning regression algorithms to predict the tax value of single homes, using data from the Zillow database.
- Visualize the distribution of tax rates for each county using the fips data.
- Present findings to the Zillow Data Science Team.

### Deliverables:
1. A report in the form of a presentation, verbal supported by slides.
    The report/presentation slides should summarize your findings about the drivers of the single unit property values. This will come from the analysis you do during the exploration phase of the pipeline. In the report, you should have visualizations that support your main points.
    The presentation should be no longer than 5 minutes.
2. A github repository containing your work.
    This repository should contain one clearly labeled final Jupyter Notebook that walks through the pipeline, but, if you wish, you may split your work among 2 notebooks, one for exploration and one for modeling. The repository should also contain the .py files necessary to reproduce your work, and your work must be reproducible by someone with their own env.py file.

### Initial Hypotheses:
- The square footage of the home will be the leading driver of tax value.
- Bedroom and Bathroom count will have a strong correlation to the area of the home.
- Year built will also be a top driver of tax value, usually newer homes have a higher value.
- The area of the home will be a driver of tax value.

#### Data Dictionary:

|Target|Datatype|Definition|
|:-------|:-------|:----------|
|logerror|51897 non-null: float64|How far over/under the Zestimate is from assessed value|

|Feature|Datatype|Definition|
|:-------|:-------|:----------|
|bathroomcnt|float64|Number of bathrooms|
|bedroomcnt|float64|Number of bedrooms|
|calculatedbathnbr|float64|Number of bathrooms and bedrooms|
|calculatedfinishedsquarefeet|float64|structure size in sqft|
|fips|float64|Federal Information Processing Standards, unique county code|
|latitude|float64|Property latitudinal location|
|longitude|float64|Property longitudinal location|
||lostsizesquarefeet|float64|Size of entire property in sqft|
|roomcnt|float64|Number of rooms in structure|
|taxamount|float64|Taxes assessed in Dollars|
|taxrate|float64|taxamount / assessed value|

### Reproduce this Project:
- You will need an env file with credentials to access the Codeup SQL Database along this repository



