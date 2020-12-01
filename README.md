# UCB Bootcamp Project 1

First Project for UC Berkeley Extension Data Analytics Bootcamp.

Data and instructions provided by UC Berkeley Extension Data Analytics Bootcamp.

## Project Name- "Fight Island: Keeping the Fight Alive"

![Project Logo](https://raw.githubusercontent.com/yuyhong23/UCB_BootCamp_Project_One/main/Fight_Island.png)

###### Group Members: Madhav Srivastava, Robert Smith, Yuying Hong

Using what we have learned so far to create a project from scratch.

What we have learned so far:

  - Excel
  - VBA
  - Python
  - Pandas
  - Matplotlib
  - Python APIs

# Introduction 

#### Project Idea (written by Robert for the presentation script)

Humans are resilient in times of crisis, and COVID is a crisis that made an impact on almost every industry. Some companies, especially sports organizations put their hands up and essentially said “we're done here for now, let’s just see how COVID plays out these next few months”. With everything thats been going on with COVID  lockdown and deaths also followed by political unrest, financial stress and uncertainty, it seems like we need some form of entertainment now more than ever.

While the majority of the sports industry sat back, there was someone in the forefront who exclaimed out to the media saying “We're going to make history”. That man was Dana White, President of the UFC, and that idea was something you may have imagined out of a mortal kombat movie; called Fight Island for the UFC organization, the top leading Mixed Martial Arts organization in the world.

Dana White’s goal was to be the first sport to air on television live since COVID began, so 400,000 man hours and 350 tons of metal later, UFCs Fight Island on Yas Island was created and aired on Saturday, July 11th: UFC 251 for the entire world to watch, and due to the location; Dana has now created a perfect hub for international fighters that helps combat COVID and Traveling restrictions, which Dana coins the #1 fight location in the world.

Dana White has claimed that this would help the UFC in a major way and there was high praise and definitely some questioning as to whether this, including some other changes made during the transition would be a good idea. The most notable change is the size of the Octagon ring, as it has decreased since fight island was created. This ring size change has created a little bit of controversy, with everyone claiming it will change the fight game in various ways.

Some of the biggest speculation was the idea it would make these fights “more exciting” since fighters are closer to each other, and therefore need to engage with each other more often. Dana White has denied these claims, as it was a big topic for the press upon the upcoming change, as he claims “it’s all an illusion, it’s BS”
        	
As a team, we have decided to cut out all this speculation out with real evidence if there actually has been a change, by comparing the same amount of fights before COVID occurred and during COVID occurred. First, we will compare the fight results before and after COVID, seeing if TKOs, Submission or Decision rates have changed. 

Following up on this, We will also take a look if any weight classes have had different results with the change, as there is speculation that certain weight classes like heavyweights may have more knockouts, based on their size and change of the cage. 

While results may or may not change, we also want to see more specifically if there has been “more action” while the fight occurs. What we consider “more action” follows this criteria:
If there is a changed in significant strikes (landing a punch), if accuracy has changed among fighters, how many submission were attempted, and also if takedown accuracy has changed a long with average takedowns per 15 mins of a fight.

A more off topic but fun topic we decided to delve into is the betting world: as more people have had time to stay at home during COVID we will see if people have gained some new knowledge, such as if their betting predictions have been more accurate.

With all this speculation, it’s time to put these questions to rest and put data to good use.

#### Result

- Decreased Cage Size: Does it make a difference with results or more action? 
  - Not significantly enough!
 
- Any changes in results by weight class?
  - For some weight classes, yes

- Have betting odds gotten more accurate since COVID?
  - Betting odds have been 10% more accurate!

#### Technical Requirement

- Use Pandas

- Contain 2 Jupyter Notebooks
  - Describe the data exploration and cleanup process
  - Illustrate the final data analysis
  
- Use Matplotlib to create a total of 6-8 visualizations of your data
  - Ideally, at least 2 per question we ask of our data
  - So we probably need to have 3-4 questions to address
  
- A folder of saved PNG images for the class and instructional team

- Optional, use at least 1 API

- Write up summarizing major findings
  - Include address for each question we asked of our data


#### Group Member Task Division

  - Project idea & Data Exploration: Robert
  - Data Cleanup & Setup for creating visualization: Yuying
  - Visualization & Analysis: Madhav
  
# Technologies/Libraries

  - Python Pandas
  
  - Jupyter Notebook
  
  - Matplotlib
  
  - Datetime
  
  - Numpy
  
  - Requests
  
  - Json
  
  - Conda Environment used: PythonData
  
# Files
 
 - Cleaning.ipynb
    - Where the data cleaning process happened
 
 - Project_One_Visualization_and_Analysis-workcopy.ipynb
    - Where we created graphs for analysis
 
 - Fight Island.pptx
    - Our presentation slides
  
# Data Resources:

- http://www.ufcstats.com/statistics/events/completed
- https://www.kaggle.com/mdabbert/ultimate-ufc-dataset
- https://sportsdata.io/developers/api-documentation/mma#/scores

# Other Resources/References:

Cleaning:

- https://www.programiz.com/python-programming/datetime/timestamp-datetime
- https://stackoverflow.com/questions/32168848/how-to-create-a-pandas-datetimeindex-with-year-as-frequency
- https://dzone.com/articles/pandas-find-rows-where-columnfield-is-null
- https://www.kite.com/python/answers/how-to-find-rows-with-nan-values-in-a-pandas-dataframe-in-python
- https://www.codegrepper.com/code-examples/python/python%3A+remove+specific+values+in+a+dataframe
- https://stackoverflow.com/questions/46113078/pandas-add-value-at-specific-iloc-into-new-dataframe-column
- https://pynative.com/python-range-function/
- https://www.geeksforgeeks.org/ways-to-apply-an-if-condition-in-pandas-dataframe/
- https://www.statisticshowto.com/combined-mean/
- https://pbpython.com/weighted-average.html
- https://www.abcboxing.com/unified-weight-classes-mma/
- https://datacarpentry.org/python-ecology-lesson/05-merging-data/index.html

Visualization:

- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.bar.html
- https://www.kite.com/python/answers/how-to-set-the-font-size-of-the-figure-title-and-axis-labels-in-a-matplotlib-graph-in-python
- https://stackoverflow.com/questions/34001751/python-how-to-increase-reduce-the-fontsize-of-x-and-y-tick-labels/34004236

Website Articles:
- https://www.essentiallysports.com/its-an-illusion-dana-white-says-smaller-cage-not-an-issue-ufc-news/
- https://www.sportskeeda.com/mma/is-smaller-cage-truly-better-cage
- https://www.bjpenn.com/mma-news/ufc/john-mccarthy-explains-why-the-ufc-prefers-to-use-a-smaller-cage/
