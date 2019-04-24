<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 20px; height: 55px">

# Final Project Pt. 1: Proposal

## Overview

Describe your chosen problem and show that you have access to relevant data and know how to open it.

## Deliverables

Create a new Git repository, follow the naming convention described in the project submission section of the course info document. In a Jupyter notebook called `part1.ipynb`, draft a well-formed problem statement in a Markdown cell. Include the following elements:

- The target variable you want to predict
- How predicting that target variable could help with some kind of decision
- The features you want to use to predict that target variable
- Goals and success metrics
- Risks or limitations

Then load each dataset that you plan to use for your project into a Pandas dataframe in one or more code cells.

Finally, evaluate the adequacy of the data you loaded for answering the question you have in mind. For instance, does it have the target variable you want? Does it have feature columns that are plausibly predictive of the target variable? How many rows and columns does it have? How many values are missing in each column. You do not need to look at descriptive statistics or do any data visualization or modeling at this point. You just need to assess whether the data set is promising enough to warrant doing those things in Part 2 of the final project.

Submit your project following the instructions in the course info document.

If the project you propose at this stage does not work out, you can change course later on. However, you will have a much easier time if you invest time up front in developing a good problem statement.

You may include up to three proposals if you want our feedback on which one seems most promising.

## Project Topics

Projects for work often yield good results, presumably because students may be able to develop them during work time and have strong incentives to do a good job. However, your project can be about any subject matter you want as long as it involves creating a **predictive model** that could help guide some kind of decision. [Here are some sites you might explore for data sets](https://git.generalassemb.ly/AdiBro/Resources/blob/master/Datasets.md).

Additional guidelines:

- Use real data rather than a synthetic data set.
- Anything less than about 100 rows and four feature columns is probably too small. You don't really need to worry about having too many rows or columns because you can always work with just a subset of the data. You will probably want to subset your data if you have more than about 250,000 rows.
- You will have an easier time if you stick with supervised learning on tabular, cross-sectional data.
- Using anomaly detection detection rather than supervised learning techniques is an option as long as you have a way to evaluate your results against labeled anomalies, but you will have to learn those techniques largely if not entirely on your own.
- Similarly, you are allowed to use time-series data or text data, but doing so will require additional work.
- Projects involving image, video, or audio data are probably not a good option unless you have at least a year of coding experience and are willing to do fairly extensive independent work.
- Traditional statistics projects that involve primarily evaluating a hypothesis rather than creating a model that generates predictions are outside the scope of this course.

## Example

See an example of a past submission [here](./pt1_example.ipynb), but note that the instructions for your cohort might be slightly different from the instructions that this student was following.
