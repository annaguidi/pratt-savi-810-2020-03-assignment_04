
# Assignment 04

# Project Proposal

![http://www.pratt.edu/tiny_mce/plugins/imagemanager/files/Light_brown_blue22.jpg](http://www.pratt.edu/tiny_mce/plugins/imagemanager/files/Light_brown_blue22.jpg)

The **purpose of this project** is to have some **well-written** and **well-documented code** in a GitHub repository that illustrates you can write some Python code. This project is for **your** Portfolio, so pick something you are **interested in** or that's **useful** (either in some professional work or automating some task). [Learn how the project is evaluated (rubric)](https://github.
com/pratt-savi-810/pratt-savi-810-2020-03-project).


#### Project Routes

There's a couple of routes you can go;

1. **Creating a Tool to Automate a Task** - usually for some task automation, less an analysis, more data engineering. 
2. **Performing Data Analysis to Answer a Research Question** - this type of project requires plots and data insights. 

Since writing the code is the challenging part. Do not think about this in scope of a normal project. **Keep your scope focused!** Keep it limited in functionality and if you finish early, you can add more features. I've seen students go down some pretty deep rabbit holes and emerge with some very disorganized projects. You could have only 30 lines of code or so, and still have a great project so long as the code is well written and the doc's are informative and it has some functionality that's useful in some capacity. Most likely someone such as a hiring manager will only glance at your Repository, so you want it to be organized and clean and very clear as to its purpose. 

## Assignment 04 Submission
You will **Fork** and **Clone this Repo** and **edit this README.md Markdown file**. This is your submission, just the link to your forked Repo and edited README.md file. This project should be the edited version of this README.md (**Markdown**) file. 

#### Learn more about [Markdown](https://www.markdownguide.org/). 

Most code editors allow editing of Markdown files, some recommended editors are;

* [Atom](https://atom.io/)
* [MacDown](https://macdown.uranusjr.com/)
* [Visual Studio Code (VS Code)](https://code.visualstudio.com/)
* [StackEdit (edit in-browser)](https://stackedit.io/)
* [Dillinger (edit in-browser)](https://dillinger.io/)
* You can even edit inside of [GitHub](https://github.com/). 

Your Assignment 04 Deliverables are listed below:

# Deliverables

You should edit the following items in-line and substitute any of the provided text with your response below for your README.md Assignment 04 submission. 

---

## Executive Summary


I want to visualize an animated time lapse of the movement of taxis (or ambulance vehicles, but I cannot find the data) from February 1st - March 30th, 2020 (and analyze if there is time). I want to determine if there were increased number of drop-offs at hospitals before any social distancing or "shelter in place" measures were put in place.

## Background

Initially the idea behind this project was to analyze whether there were patterns of increased number of emergency dispatches in NYC prior to "shelter in place" or social distancing measures, however, the only dataset I found so far had data up until December 31st, 2019, and I want to look at least 2 months into 2020. I was insipred by this Italian Article I read where a 911 operator said that in the weeks leading to the explosion of coronavirus in Northern Italy, he received a larger number than calls from people feeling sick, but when he flagged this to authorities he was ignored. I wonder what other signals are out there, ambulance dispatches being the most obvious, but taxis maybe being a good proxy as well for people who are not quite as sick. I think it would be interesting to see at what point in time and over what time span we start seeing an uptick or disurption in transportation.


## Resources

#### Resources List

* Citibike Analysis - https://toddwschneider.com/posts/a-tale-of-twenty-two-million-citi-bikes-analyzing-the-nyc-bike-share-system/ - the key findings are a commuting patter from outer boroughs to Manhattan, but I mainly like this map from a visualization aspect
* I do not have any other resources at the moment, but I have no doubt that after deciding on this topic I will find many more, I tend to normally have an issue with too many resources rather than too few
 
## Input Data 

#### Data Sources List 
List any possible data including links with any input data sources you'll be using. 

* 311 Service Requests - https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9 - still need to investigate if this has the data I need
* (possibly, maybe not necessary) Neighborhood Tabulation Area data from NYC OpenData  

#### Data Wish List
List and describe any type of data you'd like to include but had difficulty tracking down. 

* EMS dispatch data for the past 3 months
* taxi data for months of February or March
* if all else fails I will do this analysis with citibike data (https://s3.amazonaws.com/tripdata/index.html)

## Technical Requirements

#### Python Libraries

* geopandas - for data manipulation and some basic plotting maybe
* plotly/seaborn/matplotlib - maybe, for data analysis and viz
* Possibly folium?
* Moving Pandas
* Maybe need to use paperspace or Google Colab if I need more processing power? (and/or PostGIS)


#### Library Wish List

* Mapbox - can this work in python? or is there a mapbox wrapper? I would like the ability to choose my own basemap beyond like 3 or 4 standard templates
* A library to create and capture gifs??

## Measuring Success: 

- How will you measure your project's sucess?
	- I would like to be able to determine: there was a change of pattern around a certain time, or maybe there wasn't, or it was very subtle  	 
	- I would love to do an animation with a slider where you can see mobility (potentially of an entity) over time


## Project Execution Plan Outline
Please include a short outline describing the steps you'd imagine going through. 

Could be as simple as;

```
- Background Research + Data Collection
	- Spend some time researching the topic- determine if dataset is there, look for additional resources

- Data Processing
	- Clean, format & process data
    
	 
- Data Visualization
 	- First static, then dynamic as second step? 
    
	 
- Exploratory Data Analysis
 	- Summarize the input data, plot and examine any columns that may be useful. 

- Results and Conclusion 
	- Key findings
	- Was your Project Successful. 
	- Generate Assumptions and Limitations. 
```
