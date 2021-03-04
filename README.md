# Text Classification with Deep Learning in R

The following coursebook is the main part for Text Classification with Deep Learning in R workshop produced by the team at Algoritma. Algoritma is a data science education center based in Jakarta. We organize workshops and training programs to help working professionals and students gain mastery in various data science sub-fields: data visualization, machine learning, data modeling, statistical inference, etc.

Before you go ahead and run the codes in this coursebook, it’s often a good idea to go through some initial setup. Under the Training Objectives section we’ll outline the syllabus, identify the key objectives and set up expectations for each module. Under the Libraries and Setup section you’ll see some code to initialize our workspace and the libraries we’ll be using for the projects. You may want to make sure that the libraries are installed beforehand by referring back to the packages listed here.

## R and RStudio Installation

Install R and RStudio into your local device using the following [guideline](https://github.com/Argaadya/workshop-text-classification/blob/main/Algoritma%20Pre-Workshop%20Handbook%20-%20Text%20Classification%20with%20Deep%20Learning.pdf)

## Installing Keras 

Install the keras framework for building and training Deep Learning by following the [installation guide](https://github.com/Argaadya/workshop-text-classification/blob/main/Algoritma%20Handbook%20Guide%20Template%20-%20Keras%20in%20R.pdf)

## Library

Install the required packages for the workshop by using the following code.

```r
package <- c("tidyverse", "tidytext", "hunspell", "yardstick", "e1071", "keras", "scales", "tm", "furrr")
install.packages(package)

if (!require("pacman")) 
  install.packages("pacman")
pacman::p_load_gh(
    "trinker/lexicon",    
    "trinker/textclean"
)
```
