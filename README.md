# Applied Data Science @ Columbia
## Fall 2018
## Project 1: What made you happy today?

![image](figs/title.jpeg)

### [Project Description](doc/)
This is the first and only *individual* (as opposed to *team*) this semester. 

Term: Fall 2018

+ Projec title: Lorem ipsum dolor sit amet
+ This project is conducted by [hl3148]

+ Project summary: [a short summary] Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.

### Project Main Findings

In this data blog, I explore the text in the HappyDB, which contains more than 100,000 happy moments from over 10,000 contributors. In this project, a LDA model using Gibbs sampling with 10 topics is fitted. Then, I plot several bar plots to get more insights into each fitted topics. Finally, I use the LDA model to answer the following questions:

+ Which countries have more common happy moments? 
++ Most main western countries, like USA, AUS, BGR, FRA, CAN, are in the same cluster. 
++ For cluster 1, there is only one country, **CRI** or **The Costa Rica**. Perhaps this is due to the culture difference and geographic reason.

+ What are the differences in happiness between people of different marital status?
++ The most popular topics among **single people** are **school**, **pet** and **travel**.
++ **Married people** are most interested in **Shopping** and **friends**.
++ For **divorced people**, **Family** is the most popular topics. 

### Main report files are linked below

+ [Text_Processing.Rmd](doc/)
+ [GR5243_Project 1_hl3148.Rmd](doc/)
+ [GR5243_Project 1_hl3148.html](doc/)








