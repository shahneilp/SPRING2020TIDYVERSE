1. **Create an Example** Using one or more TidyVerse packages, and any dataset from fivethirtyeight.com or Kaggle, create a programming sample “vignette” that demonstrates how to use one or more of the capabilities of the selected TidyVerse package with your selected dataset. (25 points)

2. **Extend an Existing Example** Using one of your classmate’s examples (as created above), extend his or her example with additional annotated code. (15 points)

## Collaboration
You should [fork](https://github.community/t5/Support-Protips/The-difference-between-forking-and-cloning-a-repository/ba-p/1372) the provided repository and then clone it locally if you wish. Once you have code to submit, you should make a pull request on the shared repository. Minimally, you should submit `.Rmd` files. Ideally, you should also submit an `.md` file and update the README.md file with your example.

### Advice
If you are going to use RStudio as your version control software, make sure to add `*.Rproj` and `.gitignore` to your .gitignore file **before** you make any commits. Otherwise you run the risk of trying to push that to the master repository in a pull request.

## Notification
***After you’ve read each part of the assignment, please submit your GitHub handle name in the submission link provided in the Major Assignments folder!*** This will let your instructor know that your work is ready to be graded.

## Deadline
You should complete both parts of the assignment and make your submissions on the schedule specified in our course syllabus

## References
* GitHub repository:  https://github.com/acatlin/SPRING2020TIDYVERSE
* FiveThirtyEight.com datasets:  https://data.fivethirtyeight.com/
* Kaggle datasets:  https://www.kaggle.com/datasets

## "In the Style of" Vignettes:

* https://acatlin.github.io/SPRING2020TIDYVERSE/forcats_makes_plots_better.html - how to use capabilities of forcats package to improve your plots!  Andy Catlin and Ait Elmouden Abdellah

* http://rpubs.com/christianthieme/589762 (RMD file: PurrrMap-LoseTheForLoop.rmd) - Using purrr::map() and purrr::pmap() instead of for loops in R - By Christian Thieme 

### dbplyr 
dbplyr is great and simple to use backend solution for working with data that is stored on a SQL server. dbplyr follows the same grammar and formatting as dplyr, but translates R code into a SQL query to directly access the SQL database. 

### forcats::fct_lump
From the forcats package, this function allows you to quickly group levels of a categorical variable if they are above/below a certain count or proportion.

### Working with Lubridate:
Author: Ken Popkin
This vignette loads the Lubridate package and performs a few date transformations. Ken Popkin
Lubridate Extension Author: Christian Thieme - RPubs Link: https://rpubs.com/christianthieme/597573

### Stringr package - how to manipulate strings using stringr
Author: Devin Teran

### (EXTEND) Stringr package - Layla_Quinones_EXTEND_Devin_Teran
Functions added for extension:
- str_sub()
- str_subset()
- str_detect()
- str_count()
- str_extract & str_extract_all()
- str_remove
- str_replace
RPubs Link: https://rpubs.com/MsQCSNYC/592259

### (Extension) Stringr: Origional author Devin Teran, extended by David Blumenstiel on 04/17/20
filename = TidyVerse_Devin_Teran.Rmd
added:
str_view()
str_wrap()


### ggplot2 - barcharts
Author: Laylah Quinones
Extended By: Angel Claudio

ggplot2 is a ubiquitous library that allows you to easily visualize data and explain patterns in data to people who are not nessesarliy familiar with the technical aspect of data analysis. Visualizations made with ggplot2 are easy to understand and construct thanks to an API that allows visualizations to be "built" via layering of graphics and other visual elements.

This file should help you understand how to export a table from a website, gather the data into a tall format, and plot the variables of interest into several plots for easy comparison

### tidyr's unite and pivot_wider found in tidyr_AC.Rmd
Author: Angel Claudio

This vignette is meant to teach you how to use the unite and pivot_wider function from the tidyr package.

# Neil Shah Tidy
 A vignette describing the progressive use of as_tibble(), dplyr functions select, arrange, filter and a gpplot to visualizae data.
Author: Neil Shah


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

##### Extension of Vinayak Kamath's vignette
Author: Ken Popkin
Extended this vignette to also include how to create a barplot using ggplot2

Gabriel Abreu

Abdellah Ait Elmouden

### Basic Functionalities of GGplot using polling data
Author: Samuel Bellows

#### Usages:

calling basic geometries, calling aes and when arguments should go inside/outside aes, facet grid, and basic plot customization.
Also includes some use of dplyr and lubridate.



Nilsa Bermudez

Vinayak Kamath

### Extend GGPlot 
Showcase a few more styles and customizations in GGPlot. Themes, guides, manual color fills, and labels. 

### ggplot2::geom_polygon:
Author: Adam Gersowitz

This vignette looks at varisous ways to display visual data using ggplot2 and specifically geom_polygon.

This can be very useful when trying to convey information that has a physical correlation to people who aren't data scientists. For example population data on a map based on county or a blueprint of a building that shows where certain problems are occurring with certain tenants.

### Tidyverse: stringr
Author: Michael Munguia

This vignette showcases some of the text manipulation capacities of the stringr library using the context of restructuring the names of America's mayors.
=======
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

* http://rpubs.com/christianthieme/589762 (RMD file: PurrrMap-LoseTheForLoop.rmd) - Using purrr::map() and purrr::pmap() instead of for loops in R - By Christian Thieme 

### dbplyr 
dbplyr is great and simple to use backend solution for working with data that is stored on a SQL server. dbplyr follows the same grammar and formatting as dplyr, but translates R code into a SQL query to directly access the SQL database. 

### forcats::fct_lump
From the forcats package, this function allows you to quickly group levels of a categorical variable if they are above/below a certain count or proportion.

### Working with Lubridate:
Author: Ken Popkin
This vignette loads the Lubridate package and performs a few date transformations. Ken Popkin

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

##### Extension of Vinayak Kamath's vignette
Author: Ken Popkin
Extended this vignette to also include how to create a barplot using ggplot2

Gabriel Abreu

Abdellah Ait Elmouden

##### Extension of Subhalaxmi Rout's vignette
Author: Neil Shah
Extended this vignette to also include how to deal with missing values

Abdellah Ait Elmouden
### Basic Functionalities of GGplot using polling data
Author: Samuel Bellows

#### Usages:

calling basic geometries, calling aes and when arguments should go inside/outside aes, facet grid, and basic plot customization.
Also includes some use of dplyr and lubridate.



Nilsa Bermudez - Tidyverse recipe

Vinayak Kamath

### Extend GGPlot 
Showcase a few more styles and customizations in GGPlot. Themes, guides, manual color fills, and labels. 

### purrr functions for filtering lists
Author: Bonnie Cooper
This vignette uses global shark attack data to demonstrate several purrr functions for filtering lists

=======
### ggplot2::geom_polygon:
Author: Adam Gersowitz

This vignette looks at varisous ways to display visual data using ggplot2 and specifically geom_polygon.

This can be very useful when trying to convey information that has a physical correlation to people who aren't data scientists. For example population data on a map based on county or a blueprint of a building that shows where certain problems are occurring with certain tenants.


### Group_by
Author: David Blumenstiel

Group_by provides an intuitive way to look at one's data.  As the name implies, this function will interperet data based on "groups".  See the vignette for more information.
=======

Author: Amit Kapoor
Used the dataset https://fivethirtyeight.com/features/which-state-has-the-worst-drivers/


### Highlights of the tutorials  
=======
======
### Dplyr::summarise/group_by/count/arrange/select/filter
Author: Manolis Manoli
looking through hotel booking data using some dplyr functions and a bit of lubridate
=======


### stringr: 8 most popular verbs
Author: Philip Tanofsky

Vignette for the popular stringr functions from the Tidyverse packages. The stringr library provides a suite of commonly used string manipulation functions to assist in data cleaning and data preparation tasks on a vector of 10 tweets.

#### 1. dplyr :: rename vs. dplyr :: select
#### 2. dplyr :: top_n vs. dplyr :: top_frac
#### 3. tally        
#### 4. count

* https://rpubs.com/dpong8988/591906 by Dennis Pong
   + explain the nuances between rename and select
   + explain what's top_frac and how is it different from top_n
   + explain how to use an alternative to summarise/summarize's n() -- tally
   + explain an even simpler way to do tally by introducing count
 
=======
1. **Create an Example** Using one or more TidyVerse packages, and any dataset from fivethirtyeight.com or Kaggle, create a programming sample “vignette” that demonstrates how to use one or more of the capabilities of the selected TidyVerse package with your selected dataset. (25 points)

2. **Extend an Existing Example** Using one of your classmate’s examples (as created above), extend his or her example with additional annotated code. (15 points)

## Collaboration
You should [fork](https://github.community/t5/Support-Protips/The-difference-between-forking-and-cloning-a-repository/ba-p/1372) the provided repository and then clone it locally if you wish. Once you have code to submit, you should make a pull request on the shared repository. Minimally, you should submit `.Rmd` files. Ideally, you should also submit an `.md` file and update the README.md file with your example.

### Advice
If you are going to use RStudio as your version control software, make sure to add `*.Rproj` and `.gitignore` to your .gitignore file **before** you make any commits. Otherwise you run the risk of trying to push that to the master repository in a pull request.

## Notification
***After you’ve read each part of the assignment, please submit your GitHub handle name in the submission link provided in the Major Assignments folder!*** This will let your instructor know that your work is ready to be graded.

## Deadline
You should complete both parts of the assignment and make your submissions on the schedule specified in our course syllabus

## References
* GitHub repository:  https://github.com/acatlin/SPRING2020TIDYVERSE
* FiveThirtyEight.com datasets:  https://data.fivethirtyeight.com/
* Kaggle datasets:  https://www.kaggle.com/datasets

## "In the Style of" Vignettes:

* https://acatlin.github.io/SPRING2020TIDYVERSE/forcats_makes_plots_better.html - how to use capabilities of forcats package to improve your plots!  Andy Catlin and Ait Elmouden Abdellah

* http://rpubs.com/christianthieme/589762 (RMD file: PurrrMap-LoseTheForLoop.rmd) - Using purrr::map() and purrr::pmap() instead of for loops in R - By Christian Thieme 

### dbplyr 
dbplyr is great and simple to use backend solution for working with data that is stored on a SQL server. dbplyr follows the same grammar and formatting as dplyr, but translates R code into a SQL query to directly access the SQL database. 

### forcats::fct_lump
From the forcats package, this function allows you to quickly group levels of a categorical variable if they are above/below a certain count or proportion.

### Working with Lubridate:
Author: Ken Popkin
This vignette loads the Lubridate package and performs a few date transformations. Ken Popkin

### Stringr package - how to manipulate strings using stringr
Author: Devin Teran


# Neil Shah Tidy
 A vignette describing the progressive use of as_tibble(), dplyr functions select, arrange, filter and a gpplot to visualizae data.
Author: Neil Shah


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

##### Extension of Vinayak Kamath's vignette
Author: Ken Popkin
Extended this vignette to also include how to create a barplot using ggplot2

Gabriel Abreu

Abdellah Ait Elmouden

### Basic Functionalities of GGplot using polling data
Author: Samuel Bellows

#### Usages:

calling basic geometries, calling aes and when arguments should go inside/outside aes, facet grid, and basic plot customization.
Also includes some use of dplyr and lubridate.

Nilsa Bermudez

Vinayak Kamath

### Extend GGPlot 
Showcase a few more styles and customizations in GGPlot. Themes, guides, manual color fills, and labels. 

### ggplot2::geom_polygon:
Author: Adam Gersowitz

This vignette looks at varisous ways to display visual data using ggplot2 and specifically geom_polygon.

This can be very useful when trying to convey information that has a physical correlation to people who aren't data scientists. For example population data on a map based on county or a blueprint of a building that shows where certain problems are occurring with certain tenants.

### Tidyverse: stringr
Author: Michael Munguia

This vignette showcases some of the text manipulation capacities of the stringr library using the context of restructuring the names of America's mayors.
=======
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

* http://rpubs.com/christianthieme/589762 (RMD file: PurrrMap-LoseTheForLoop.rmd) - Using purrr::map() and purrr::pmap() instead of for loops in R - By Christian Thieme 

### dbplyr 
dbplyr is great and simple to use backend solution for working with data that is stored on a SQL server. dbplyr follows the same grammar and formatting as dplyr, but translates R code into a SQL query to directly access the SQL database. 

### forcats::fct_lump
From the forcats package, this function allows you to quickly group levels of a categorical variable if they are above/below a certain count or proportion.

### Working with Lubridate:
Author: Ken Popkin
This vignette loads the Lubridate package and performs a few date transformations. Ken Popkin


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

##### Extension of Vinayak Kamath's vignette
Author: Ken Popkin
Extended this vignette to also include how to create a barplot using ggplot2

Gabriel Abreu

Abdellah Ait Elmouden

##### Extension of Subhalaxmi Rout's vignette
Author: Neil Shah
Extended this vignette to also include how to deal with missing values

Abdellah Ait Elmouden
### Basic Functionalities of GGplot using polling data
Author: Samuel Bellows

#### Usages:

calling basic geometries, calling aes and when arguments should go inside/outside aes, facet grid, and basic plot customization.
Also includes some use of dplyr and lubridate.



Nilsa Bermudez - Tidyverse recipe

Vinayak Kamath

### Extend GGPlot 
Showcase a few more styles and customizations in GGPlot. Themes, guides, manual color fills, and labels. 

### purrr functions for filtering lists
Author: Bonnie Cooper
This vignette uses global shark attack data to demonstrate several purrr functions for filtering lists

=======
### ggplot2::geom_polygon:
Author: Adam Gersowitz

This vignette looks at varisous ways to display visual data using ggplot2 and specifically geom_polygon.

This can be very useful when trying to convey information that has a physical correlation to people who aren't data scientists. For example population data on a map based on county or a blueprint of a building that shows where certain problems are occurring with certain tenants.


### Group_by
Author: David Blumenstiel

Group_by provides an intuitive way to look at one's data.  As the name implies, this function will interperet data based on "groups".  See the vignette for more information.
=======

Author: Amit Kapoor
Used the dataset https://fivethirtyeight.com/features/which-state-has-the-worst-drivers/


### Highlights of the tutorials  
=======
======
### Dplyr::summarise/group_by/count/arrange/select/filter
Author: Manolis Manoli
looking through hotel booking data using some dplyr functions and a bit of lubridate
=======


### stringr: 8 most popular verbs
Author: Philip Tanofsky

Vignette for the popular stringr functions from the Tidyverse packages. The stringr library provides a suite of commonly used string manipulation functions to assist in data cleaning and data preparation tasks on a vector of 10 tweets.

#### 1. dplyr :: rename vs. dplyr :: select
#### 2. dplyr :: top_n vs. dplyr :: top_frac
#### 3. tally        
#### 4. count

* https://rpubs.com/dpong8988/591906 by Dennis Pong
   + explain the nuances between rename and select
   + explain what's top_frac and how is it different from top_n
   + explain how to use an alternative to summarise/summarize's n() -- tally
   + explain an even simpler way to do tally by introducing count

### Explore and manipulate a dataset using dplyr and tidyr (by Abdellah Ait Elmouden)

The purpose of this Vignette is to demonstrate how some of tidyverse packages can be used to explore and manipulate a dataset in R. A dataset was selected from the fivethirtyeight Package. the R markdown file can be accessed from [here](/tidyverse_AitElmouden) 


<!-- Start: Extended Dennis Pong Create by Vinayak on 04/15/2020--> 
## Using dplyr: mutate to add new variables that are functions of existing variables  
## Using dplyr: arrange to changes the ordering of the rows  
## Using dplyr: slice to Choose rows by their ordinal position in the tbl. Grouped tbls use the ordinal position within the group.  
<!-- End: Extended Dennis Pong Create by Vinayak on 04/15/2020--> 

<!-- Start: Extended Vincent Miceli Created by Bruno de Melo on 04/19/2020--> 
## Using forcats: functions fct_recode and fct_lump 
## fct_recode: allows to change value of factors, also allows for combining factors into groups
## fct_lump: allows to lump together group of factors. Useful for make a plot or table simpler
 
<!-- End: Extended Vincent Miceli Created by Bruno de Melo on 04/19/2020--> 

