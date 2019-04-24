<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 20px; height: 55px">

# Final Project Pt. 2: Exploratory Data Analysis

## Overview

Build a first-pass model on your data and look for ways to improve on it.

## Deliverables

In the final project Git repository you created for Pt 1, create a new Jupyter notebook called `part2.ipynb`. In that notebook...

- Build a first-pass model on your data:
    - Load in your data set.
    - Separate your target column from potential feature columns.
    - Get those columns in a clean enough state that you can build a model with them. It is OK to be fast and loose at this stage, e.g. by simply dropping rows or columns that have missing values or have string values that would take some work to make usable.
    - Do a train/test split.
    - Fit some kind of regression or classification model on your training set. Be sure to choose the correct type: regression if your target variable is a number, classification if it is a category.
    - Use an appropriate metric to evaluate your model on both the training set and the test set. Be sure to choose a regression metric for a regression problem (e.g. MSE, RMSE, MAE, R-squared) or a classification metric for a classification problem (e.g. accuracy, $F_1$).
    - Use the same metric to evaluate a null model for your target variable. 
    - State whether this first-pass model appears to be overfitting or underfitting.

- Explore your data, looking for insights that might help you improve your model.
    - For each variable individually (including categorical variables):
        - Look at the descriptive statistics.
        - Visualize the distribution.
        - Note which variables appear to be roughly normally distributed and which appear to be strongly skewed, as well as any other potentially important observations.
    - For each potential feature variable:
        - Measure its correlation with the target variable.
        - Visualize its relationship with the target variable.
        - Note which feature variables appear to be roughly linearly related to the target, related to it but not linearly, and unrelated to it, as well as any other potentially important observations.
    - Determine how to handle sampling or missing values.
- Clearly identify...
    - Shortcomings of your data
    - Any assumptions that you will need to make in light of those shortcomings
    - At least five things you might try as ways to improve your model.
    - What you think is the most appropriate metric for evaluating the models you will build.
    
Submit your project following the instructions in the course info document.

## Motivation

Conventional data science advice says to explore your data thoroughly before building a model. However, in my experience it is helpful to build a first model as quickly as possible and then to circle back to data exploration. This approach has a few benefits:

- It takes away the burden of worrying that you will not be able to finish your project at all. Once you have a working model, the only question is how much better your can make it.
- It gives you some sense of how hard the problem you are trying to solve is. If the target variable is highly predictable from your features, then you might find that your first-pass model is already pretty good. On the other hand, if your first-pass model is little better or no better than the null model, then it may be that there is not a lot of signal in your features.
- It helps you prioritize your next rounds of work. After you have built your first quick-and-dirty model, you will know what problems you skimmed over and may have some sense of which are the most important, whereas if you try to do everything perfectly up front then you are likely to waste a lot of time on tasks that do not really matter.

That being said, you typically do not want to stop with your first model, and exploratory data analysis is an excellent way to identify possible low-hanging fruit for improving on it.

## Examples

See an example of a past submission [here](./pt2_example.ipynb), but note that the instructions for your cohort might be slightly different from the instructions that this student was following.
