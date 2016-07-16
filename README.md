# BrainStorming

Target audience:
* Assume no prereqs
* students taking traditional intro stats class in a small college environment 

## Book title

* Maybe an acronym?  Something that includes Modern, Open, Reproducible, Intuitive, Visualization, Data Analysis?

## Principles

* As much as possible, explain why we are making the choices we are in the book
    + Give the point of the book in the prologue/introduction and the conclusion
    + Refer to it frequently throughout the book
* Data/science pipeline.
* Visualizations first whenever possible, then definitions/theorems.
* Multivariate thinking.
* Minimizing prerequisites to research
* Tidy data as a representation of:
    + Multivariate relationships
    + Variable types
    + Starting point of "data pipeline" AKA "science pipeline" 
* Reproducibility: the greatest collaborator you'll ever have is yourself in a few years
* Introduce statistical inference via computing/resampling/randomization. quantifying uncertainty
* Tie chapters together whenever possible
    + Have examples that go from own chapter to another and build on each other
    + Summarize everything covered with a mind map in the last chapter
    + Build on the mind map as the chapters progress


## Datasets

* nycflights13
* babynames


## Topics Needed

* Definitely need a good preamble: Intro to stats (what is it?  what is data science? how do they relate?)
* What are variables? What are observational units? Explanatory/Response, Categorical/Continuous
* Data visualization (what makes a good plot given a problem setup?  why do we choose one plot over another?)
* Data tidying/reshaping/manipulation/summarizing: use RStudio keynote flowcharts.
* Data analysis
    + Allude or explicity state regression?
    + Random sampling
    + Observational study vs randomized experiment (fit with correlation)
    + Developing traditional inference from randomization
        + two-sample permutation test -> null distribution   
    + Standard error
    + Showing what happens when assumptions/conditions aren’t met
    + Comparing non-parametric and parametric methods
        - For two sample mean, two sample proportion, regression, and multiple regression?
    + Regression/correlation/multiple regression/confounding
        + Categorical predictor and baseline 
        + Implement `tidy`, `broom::augment`, and `glance` in `broom` package to get results
    + 60% Confidence Intervals vs 40% Hypothesis Testing
        + HT: the theory of hypothesis. Criminal justice. Question: what do you do with a problem like alpha?
        + 
    + Model selection is a can of worms 
    + Interpretation of results


## Topics to be Dropped

* Design of experiments
* statistical power
* Independence/Probability
* Chi-Square Tests
* Not do extensive ANOVA, but allude to it after doing multiple regression with categorical
* Logistic Regression
* CLT/Mathematical computation engine (but we need to ascertain the unintended consequences of dropping it)
    + Tell them the minimum they need to know.
    + 


## Lingering Questions

* HW frequency/collection/grading
* Selling them on R Markdown/reproducibility
* Feedback
    + Minute papers
    + Plicker questions
* How do we introduce them to naming conventions? Using R?
    + It would seem that we need to create an introductory "lab" to do so and reinforce it throughout the course.  
    + Does it belong in the book in an appendix?
* How should we build the mind map on http://coggle.it for data visualization?
    + Which things do we include?
    + When do we add them for students to see?  After? Before? During?
