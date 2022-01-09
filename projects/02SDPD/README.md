# Week 2: Data is Messy

This project uses the San Diego RIPA police stop data (see [https://data.sandiego.gov/datasets/police-ripa-stops/](https://data.sandiego.gov/datasets/police-ripa-stops/). The city makes a bunch of interesting data available at [https://data.sandiego.gov](https://data.sandiego.gov).

By the end of this week you will be able to:

* Work with messy real-world data
* Identify when data is bad, and what to do about it
* Perform more sophisticated analysis in Tableau, including aggregations, formulas and new plot types

## Questions to pursue:

As you explore the SDPD dataset, you will be trying to build a picture of the nature of stops in San Diego. To draw conclusions, you'll typically looking at the difference between occurrences (e.g. getting stopped) across multiple attributes (e.g. time, space, gender, ethnicity). This analysis will sometimes show no difference. However, sometimes it will show a difference, and you'll have to determine whether this difference is due to a significant reason or just random fluctuations.

When working with real data created by many individual humans, oddities in the data collection process often occlude the "real" picture. This could be null values, inconsistent data input, typos in data, and approximations during data entry. These oddities are unavoidable, and this project begins with exploring and handling the messiness in data.

* After loading the data, plot the counts of the values of each field. Keep an eye out for null values, values that seem impossible (e.g. outliers), and values that occur 'unnaturally' often. 

A few sample questions to pursue, to get you started:

* What ages do you see? oldest? youngest? null values? *anything else?* E.g., stops by age: anything strange here? 
* Examine the "Stop Cause" field. What are some issues and how should you deal with it?
* Stops by race: what races seem to be over or underrepresented? what data are needed to figure this out precisely?
* Plot counts of fields by time -- are the  stops uniform? or is there a pattern? is the pattern an oddity?
    - Number of stops by quarter, month, day?
    - Number of stops by day of month? day of week? hour of day? minute of the hour?
* Are there dates where stops are abnormally low/high? why?
* Gender breakdown of stops by hour of day? Median age by hour  of day?
* Percentage of cars searched by hour? by ethnicity? by gender?
* Property seized/arrested in relation to searched? Ask the same question here as with stops overall?
* Ask the same questions for various "Stop Causes"

## Assignment 1:

* When is it due: Tuesday 18, 4.59pm
* Which data can I use: Any SDPD data in Tableau.
* What to do: You need to complete your analysis on the Tableau Online platform, defining your question, answering with clear figures and reporting in a Dashboard
* What to submit: One pdf, obtained from your Dashboard, clearly explaining what you wanted to do and what you discovered.
* How to submit: You should send your pdf as a Direct message to Instructor (Giorgio Quer) in Slack.

### Helpful Links

[Tableau Aggregations](https://onlinehelp.tableau.com/current/pro/desktop/en-us/calculations_calculatedfields_aggregate_create.htm)