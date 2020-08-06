# Ford-go-bike-data-analysis

# Communicate Data Findings - Ford Go Bike (2018)
## by Nishant Sharma

## About the Project

> This project has two types of parts that provide the necessity and value of data visualization techniques in the data analysis process.The first part goes as, we have used Python libraries of visualization to explore a selected dataset (Ford GoBike data) in a proper manner, we started from plots of single variables and building up the plots of multiple variables. In the second part, we made a short presentation that speaks of interesting trends, properties and relationships that we gathered in the this dataset. The primary method we used for conveying the findings is through transforming my exploratory visualizations from the first part into polished, explanatory visualizations.

## Why this project?

> In data analysis process Data visualization is an important skill that is used in visualisation and findings. 
Exploratory data visualization generally occurs during and after the data wrangling process, and it is the main method that we used to understand the ongong patterns and relationships present in data. This understanding will help us to approach any statistical analysis and will help us build findings and conclusion. This process might also demonstrate additional data cleaning tasks to be done.
Explanatory data visualization techniques is used after generating the findings, and are used to communicate the results we found to others. Understanding design considerations will make sure that my message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.


## What I learnt?
#### After completing this project, I am able to

> Choose appropriate plots, limits, transformations, and aesthetics to explore a dataset, allowing me to understand distributions of variables and relationships between features.

> Use design principles to create effective visualizations for communicating findings to an audience.

> Supplement statistics with visualizations to build understanding of data.


## Project Details

1. Dataset: Ford GoBike system data
2. Explore the dataset: Feel free to explore the jupyter notebook where the dataset is visually, and programatically explored.
3. Document the findings: organized findings convey a story to present in front of audience.
4. Communicate the findings - a slide deck with my findings is prepared for a curious audience.


## Ford GoBike System - Summary

> There are two types of clients using the system: Subscribers and Customers. Subscribers are primarily daily commuters, Subscribers used the system heavily on work days concentrated around 8-9am and 17-18pm for work commute, whereas customers ride a lot over weekends and in the afternoon for leisure/touring purposes. Subscribers tended to have much shorter/quicker trips compared to customers which makes subscriber usage more efficient.

> There was a lot more subscribers using the bike sharing system than casual customers overall, both of which ride the most during the summer season and the least during the winter months.

> The number of trips peaked around 8-9am and 18-19pm during a day, there were more trips on work days (Mon-Fri) compared to weekends. Summar time was the most popular season of a year, likely due to the weather. The riding trips tend to be shorter on Monday through Friday compared to weekends. It indicates a pretty stable and efficient usage of the bike sharing system on normal work days, while more casual flexible use on weekends.


## Files
- exploration_template.ipynb - This Jupyter Notebook contains section templates to help you organize your exploration, starting from loading in the data, working through univariate visualizations, and ending with bivariate and multivariate exploration.

- slide_deck_template.ipynb - This Jupyter Notebook contains starter cells to help you organize your slide deck deliverable. These cells provide an example of how the slide deck should be organized, including pre-set slideshow settings.

- readme.md - This Markdown file contains sections that you should fill out as you select your dataset, complete your exploration, and plan your explanatory analysis.

- To view the slide deck, you will need to use the expression (all one line): jupyter nbconvert Example_Project_Diamonds_Part2.ipynb --to slides --post serve --template output_toggle

- output_toggle.tpl - This template file can be used with nbconvert to export your slide deck. This adds extra functionality to the slide deck by hiding the code to start, only making it visible if the reader clicks on the output (which should mostly be visualizations in the case of this project).
