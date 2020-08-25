---
author: Yashparna De
date: "2020-08-22T13:45:06+06:00"
feature_image: images/blog/r1.jpg
image: images/blog/r.jpg
title: 'R for dummies'
---
### -How I stated with R


New to R? Interested in Data science?
This is a short blog on how I started learning R and understanding how to use and utilize it.


>What is R?

R is a programming language and free software environment for statistical computing and graphics supported by the R Foundation for Statistical Computing. The R language is widely used among statisticians and data miners for developing statistical software and data analysis.
So if you are here you already know what R is and its basic usage. 
To get started with R, I followed the steps as given below. Its not necessary to do it the same way as different people learn it differently. It is just how I started it.

Before getting into working with R, it is important to learn the basics about data, data analysis, data visualization, need for data science etc. It is also important to understand algorithms, flow charts and working of program code. If you already have experience of working with different programming languages, this will be a easy part and you can skip and go straight to working with R, But if not then its better to utilize good amount of time into this.

**•	Download R and Rstudio**

As we said before, R itself does not have a graphical interface, but most people interact with R through graphical platforms that provide extra functionality. We will be using a program called RStudio as a graphical front-end to R, so that we can access our scripts and data, find help, and preview plots and outputs all in one place. Google R and Rstudio and you’ll find the link for both. Download the latest version.


![overview](images/blog/r2.png)

**•	Understand basic codes**

Try out some basic commands like setting working directory, downloading packages, etc.
Try out the following codes:

```
setwd(“Your working directory here”)   #to set the working directory 
getwd()   #to get the working directory
ls()   #show list of variables

#ctrl+l #to clear console
```

You can use ? infront of any command to get help and information on that specific command.
Ex:  Try ?getwd

**•	Install Swirl**

The most basic, easy and fun way to get started with R is through swirl package
Install and start swirl through the code given below:

```
Install.packages(“swirl”)
Library(swirl)
Swirl()
```

On opening swirl, you’ll be prompted to input your name. Remember this for when you need to open it again to continue your practice.
Select the course that you want to start practicing with. Mostly start with the R programming environment to get down the basics.

With this swirl package you’ll get down to almost all the basic elements required to understand the working of Rstudio.
To close swirl just type bye()

If you'd like to install a course that is not part of our course repository, type ?InstallCourses at the R prompt for a list of functions that will help you do so.


(for more information visit https://swirlstats.com/students.html)

