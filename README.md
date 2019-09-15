# R for Pharmacometricians
## Administrative Things

### Where to find stuff

- All course material is available on github!
- For questions, message me at: jasminehannahhughes AT gmail.com

### Microcredit Program
A microcredit in "R for data science" is available!

Requirements:

- Participate in a 2-day workshop (so far, great start!)
- Complete the assignment. 11 questions, beginning with a dataset, manipulating data, performing basic calculations, using some clinical reasoning, presenting findings graphically.
- Email the assignment to Professor Krzyzanski; wk AT> buffalo.edu


## How to learn programming

The bootcamp will be organized in modules, each of which will be a combination of lecture/demo presentation concluded by a breakout session in which you'll work on a variety of problems of different levels of difficulty. The idea is for each person to find problems that challenge them but are not too hard. Solutions to the breakout problems will be presented before the start of the next module. 

Many of the modules will use a common dataset as an example on which to carry out various operations. We'll focus on dataset of demographic/economic information (population, GDP per capita, life expectancy) for many of the countries in the world every five years, provided by the [Gapminder project](https://www.gapminder.org). (Note that this is almost the full population of countries -- I'll fit some statistical models but the interpretation is tricky as we are not working with a sample from a well-defined population.)


## Suggestions on how to get the most out of the bootcamp

I encourage you to:

- try out the code as we walk through it
- don't be afraid of errors! nothing is going to break, the errors are there to help you learn.
- keep your eyes open! -- We'll illustrate a lot of syntax and concepts by example
- try to guess what the syntax means in cases we haven't yet seen that syntax
- play with it and try variations and try to break it and see what happens
- tell us if something interesting happens as you experiment, or post a comment in the chat room
- ask questions!!

If you find yourself not following everything, that's ok. You may miss some details, but try to follow the basics and the big picture. 

A few additional thoughts on my pedagogical philosophy here:

- I want to expose you to a lot of tools and ideas that you can come back to when you need them and when you have time for more depth.
- My aim is not to show you how to use specific statistical methods or analysis techniques. My goal is to get you up to speed generally in R.
- It can be hard to absorb everything in such a concentrated situation. Hopefully the material presented will be useful to you over the longer-term as you do more work with R. Feel free to add notes & clarifying comments that you can return to.

## RStudio and R Markdown

We'll present most of the material from within RStudio, using R Markdown documents with embedded R code. R Markdown is an extension to the Markdown markup language that makes it easy to write HTML in a simple plain text format.  This allows us to both run the R code directly as well as compile on-the-fly to an HTML file that can be used for presentation. All files will be available on github. 


## Using Github to get the documents

To download the files from Github, you can do the following. 

### As a zip file (Easiest!)

If you don't want to bother using Git or have problems, simply download a zip file with all the material from github. Navigate to the repo, and click the big green "clone or download" button.

### Within RStudio

Within RStudio go to File->New Project->Version Control->Git and enter:

- "Repository URL"
- "Project Directory Name": r-for-pharmacometricians (or something else of your choosing)
- "Directory": ~/Desktop (or somewhere of your choosing)

Then to update from the repository to get any changes we've made, you can select (from within RStudio):
Tools->Version Control->Pull Branches

or from the Environment/History/Git window, click on the Git tab and then on the blue down arrow.

Be warned that you probably do not want to make your own notes or changes to the files we are providing. Because if you do, and you then do a "Git Pull" to update the materials, you'll have to deal with the conflict between your local version and our version. You probably will want to make a personal copy of such files in another directory or by making copies of files with new names.

### From a Mac/Linux terminal window

Run the following commands:

- `cd /directory/where/you/want/repository/located`
- `git clone https://github.com/jasmineirx/R_for_pharmacometricians`

Then to update from the repository to get any changes we've made:

- `cd /directory/where/you/put/the/repository/R_for_pharmacometricians`
- `git pull`


## What is R?

- R is an Open Source (and freely available) environment for statistical computing and graphics
- It is a full-featured programming language, in particular a scripting language (with similarities to Matlab and Python)
- It can be run interactively or as a batch/background job
- R is being actively developed with ongoing updates/new releases
- R has a variety of built-in as well as community-provided packages that extend its functionality with code and data; see [CRAN](https://cran.r-project.org/web/packages/index.html) for the thousands of add-on packages
- It is freely-available and modifiable 
- Available for Windows, Mac OS X, and [Linux](http://dilbert.com/strips/comic/1995-06-24/)


## Modes of using R

- Using the RStudio GUI, an 'integrated development environment'
- From the command line in a Linux/Mac terminal window
- Running an R script in the background on a Linux/Mac machine (Windows?)
- Using the Windows/Mac GUIs



## Starting R and RStudio

The pieces of an R session include:

- The R console
- Scripts containing your code
  - The script window also has Notebook capabilities (which we will use!)
- Help files
- Graphics windows
- Workspace containing your objects/environment, which hold data and information

RStudio provides an integrated development environment in which all of these pieces are in a single application and tightly integrated, with a built-in editor for your code/scripts. 

## Why R?

- R is widely used (statisticians, scientists, social scientists) and has the widest statistical functionality of any software
- Users add functionality via packages all the time
- R is free and available on all major platforms
- R is very powerful, flexible, and easy to use
- R allows for reproducibility and automating tasks
- R can do essentially anything
- Wide usage helps to improve quality and reduce bugs
- R can interact with other software, databases, the operating system, the web, etc.
- R is built on C and can call user-written and external C code and packages (in particular, see the *Rcpp* R package)

## Why Not R?

* Other software is better than R at various tasks
* R can be much slower than compiled languages (but is often quite fast with good coding practices!)
* R's packages are only as good as the person who wrote them; no explicit quality control
* R is a sprawling and unstandardized ecosystem

## What are my other options? Get me out of here!

- Python
- Matlab/Octave
- Julia
- C/C++
- SAS
- Stata

## My ulterior motive

In addition to learning some R, this workshop will expose you to a way of thinking about doing your computational work. 

The building blocks of scientific computing include:

- reproducibility
- automating repetitive tasks
- tidy data
- version control (note our basic use of Git)


## The Legal Stuff
- This workshop is based on a workshop prepared by Chris Paciorek with contributions from Kellie Ottoboni, Nima Hejazi, Rochelle Terman, Chris Krogslund, and Jarrod Millman; originally presented at UC Berkeley (D-Lab, Dept of Statistics).
- Some of this material was drawn from [Jared Knowles R bootcamp](http://jaredknowles.com/r-bootcamp/url).
- You are free to use, modify and redistribute any of this material with or without attribution. If you liked it and use parts of it in the future, please give a call out to the people above and to myself.


