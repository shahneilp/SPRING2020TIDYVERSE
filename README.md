# CUNY DATA 607 Spring 2020 Tidyverse recipes
For DATA 607 students to practice collaborating on GitHub

=======
## Objective
In this assignment, you’ll practice collaborating around a code project with GitHub. You could consider our collective work as building out a book of examples on how to use TidyVerse functions.

## Tasks
You have two tasks:

 1. **Create an Example** Using one or more TidyVerse packages, and any dataset from fivethirtyeight.com or Kaggle, create a programming sample “vignette” that demonstrates how to use one or more of the capabilities of the selected TidyVerse package with your selected dataset. (25 points)

 1. **Extend an Existing Example** Using one of your classmate’s examples (as created above), extend his or her example with additional annotated code. (15 points)

## Collaboration
You should [fork](https://github.community/t5/Support-Protips/The-difference-between-forking-and-cloning-a-repository/ba-p/1372) the provided repository and then clone it locally if you wish. Once you have code to submit, you should make a pull request on the shared repository. Minimally, you should submit `.Rmd` files. Ideally, you should also submit an `.md` file and update the README.md file with your example.

### Advice
If you are going to use RStudio as your version control software, make sure to add `*.Rproj` and `.gitignore` to your .gitignore file **before** you make any commits. Otherwise you run the risk of trying to push that to the master repository in a pull request.

## Notification
***After you’ve each parts of the assignment, please submit your GitHub handle name in the submission link provided in the Major Assignments folder!*** This will let your instructor know that your work is ready to be graded.

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