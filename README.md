# Riset Operasional - [Black Friday](https://www.kaggle.com/mehdidag/black-friday)
Repository untuk Project Riset Operasional

## Machine Learning : Apriori (Association Rule Learning)
We will be using Apriori algorithm to predict costumer transactions, In other words, the algorithm solves the problem, "People who bought 'Product A' also bought 'Product B' ."

### Requirements
- [R-3.5.3](https://cran.r-project.org/bin/windows/base/) (latest)
- [RStudio 1.2.1335](https://www.rstudio.com/products/rstudio/download/)

### Required R Packages (case-sensitive)
- shiny
- tidyverse
- readr
- GGally
- stringr
- shinythemes
- gridExtra
- arules
- scales

## Into Association Rules and *Apriori* algorithm
Association Rules is a technique to uncover how items are associated to each other. Three ways to measure association:
1. Support: Says how popular an itemset is. 
![](https://annalyzin.files.wordpress.com/2016/04/association-rule-support-table.png?w=503&h=447)

## Installing
1. Download all files and put them in the same folder
2. Download all the required R packages
3. Open server.R, data1.R, and ui.R on RStudio
4. Click Run App 
![](GIFFolder/GIFInstall.gif)  

## Program Features
### Data Exploration
![](GIFFolder/GIFDatExplore.gif)  
Simply click on "Select Plot" to open the dropdown menu and change the plot. The values of the plot can be changed using the bottom-most slider.

### Prediction Table
![](GIFFolder/GIFPredTable.gif)
Modifies the confidence for the tables.

![](GIFFolder/GIFPredTableSupp.gif)
Modifies the support for the tables.

## Grouped
![](GIFFolder/GIFGroupedConf.gif)

![](GIFFolder/GIFGroupedSupp.gif)

References:
[***Black Friday Examined (EDA + Apriori)***](https://www.kaggle.com/dabate/black-friday-examined-eda-apriori/notebook)

