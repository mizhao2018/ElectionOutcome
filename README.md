# Predicting 2016 Presidential Election Outcome by County

The 2016 Presidential Election had many people question the data and analysis used to predict election outcome. I was curious to see if there was any correlation between counties that voted for Republican vs. those that voted for Democrat. With each county's socio-economic data including: 
* Education
* Healthcare
* Crime
* Demographic
* Income
* Occupation
I would like to see if I can predict election outcome (voted for R vs. D) for a particular county. 

**Tools Used**
AWS, postgresql, SKLearn, Matplotlib, Seaborn, Pandas, Plotly. 

**References**
[Election Data File from DataOpenSoft] (https://www.opendatasoft.com/2016/11/13/2016-united-states-election-results-open-data/)
[Presidential Election Results from NYTimes] (https://www.nytimes.com/elections/results/president)
[How Data Failed Us in Calling an Election] (https://www.nytimes.com/2016/11/10/technology/the-data-said-clinton-would-win-why-you-shouldnt-have-believed-it.html)

**Reports**
Attached is the presentation / analysis produced based on the model generated. 

**Models**
Include a few exploratory models from SKLearn

**ipython files**
* ElectionOutcome_DataCleaning.ipynb: data cleaning from original data (open data soft)
* ElectionOutcome_SQLQueries.ipynb: SQLQueries to retrieve data from AWS EC2 instance (put in iPython notebook for easy reading)
* ElectionOutcome_ExploreModeling.ipynb: model exploration through SKLearn, comparing models
* ElectionOutcome_Plotly.ipynb: plotted predictions using plotly to visualize outcome

**Data**
* ElectionTable_cleandata.csv: clean data from election table
* table_from_aws.pkl: joined data for modeling