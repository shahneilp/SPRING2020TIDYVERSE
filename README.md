1. **Create an Example** Using one or more TidyVerse packages, and any dataset from fivethirtyeight.com or Kaggle, create a programming sample “vignette” that demonstrates how to use one or more of the capabilities of the selected TidyVerse package with your selected dataset. (25 points)

2. **Extend an Existing Example** Using one of your classmate’s examples (as created above), extend his or her example with additional annotated code. (15 points)

## Collaboration
You should [fork](https://github.community/t5/Support-Protips/The-difference-between-forking-and-cloning-a-repository/ba-p/1372) the provided repository and then clone it locally if you wish. Once you have code to submit, you should make a pull request on the shared repository. Minimally, you should submit `.Rmd` files. Ideally, you should also submit an `.md` file and update the README.md file with your example.

### Advice
If you are going to use RStudio as your version control software, make sure to add `*.Rproj` and `.gitignore` to your .gitignore file **before** you make any commits. Otherwise you run the risk of trying to push that to the master repository in a pull request.

## Notification
***After you’ve read each part of the assignment, please submit your GitHub handle name in the submission link provided in the Major Assignments folder!*** This will let your instructor know that your work is ready to be graded.

## Deadline
You should complete both parts of the assignment and make your submissions on the schedule specified in our ourse syllabus

## References
* GitHub repository:  https://github.com/acatlin/SPRING2020TIDYVERSE
* FiveThirtyEight.com datasets:  https://data.fivethirtyeight.com/
* Kaggle datasets:  https://www.kaggle.com/datasets

## "In the Style of" Vignettes:

* https://acatlin.github.io/SPRING2020TIDYVERSE/forcats_makes_plots_better.html - how to use capabilities of forcats package to improve your plots!  Andy Catlin and Ait Elmouden Abdellah


### dbplyr 
dbplyr is great and simple to use backend solution for working with data that is stored on a SQL server. dbplyr follows the same grammar and formatting as dplyr, but translates R code into a SQL query to directly access the SQL database. 

### forcats::fct_lump
From the forcats package, this function allows you to quickly group levels of a categorical variable if they are above/below a certain count or proportion.

### Working with Lubridate:
This vignette loads the Lubridate package and performs a few date transformations. Ken Popkin


## ggplot2 - geom
ggplot2 is a ubiquitous library that allows you to easily visualize data and explain patterns in data to people who are not nessesarliy familiar with the technical aspect of data analysis. Visualizations made with ggplot2 are easy to understand and contruct thanks to an API that allows visualizations to be "built" via layering of graphics and other visual elements.
=======
This file should help you understand how to export a table from a website, gather the data into a tall format, and plot the variables of interest into several plots for easy comparison

# DATA607_Tidyverse_Vignette
 A vignette describing the prepration of an online table for ggplot and facet_wrap
Author: Thomas Hill

Instructions:

Please follow along with the steps I took to prepare date for ggplot exploration.  I based this off of a previous project and added some annotations about the functions I called.

### tidyverse
Using `titanic` dataset from `Kaggle`, clean and manipulate data using various functions of tidyvesrse package. (Subhalaxmi Rout) 


### An Example using TidyVerse packages - **ggplot2** and **dplyr**  and using tesla-stock-data-from-2010-to-2020 Data set from Kaggle 
Author: Vinayak Kamath

#### Package Selected : **ggplot2**  and **dplyr**

##### Capability 1: **ggplot2 geom_line**

###### Usage:  
ggplot2 is a system for declaratively creating graphics, based on The Grammar of Graphics. You provide the data, tell ggplot2 how to map variables to aesthetics, what graphical primitives to use, and it takes care of the details.
  
###### Demo:  
ggplot2 geom_line to show the stock price movement over the years for Tesla shares.  

##### Capability 2: **dplyr filter**
  
###### Usage:  
dplyr filter helps in filtering of data based on one or more conditions.    
  
###### Demo:   
dplyr filter to show the days when the stock price for Tesla moved by over 15% (profit or loss) in one day.    

##### Capability 3: **dplyr group by and summarise**
  
###### Usage:  
dplyr group by and summarise helps in getting aggregated data from the given data set for one or more columns.      
    
###### Demo:   
dplyr group by and summarise to show the yearly minimum and maximum stock price close and arranging it in descending order of movement in a year. 


Gabriel Abreu

Abdellah Ait Elmouden

Samuel Bellows

Nilsa Bermudez

Vinayak Kamath

