# Capstone Report Format

Your capstone report should take the form of a semi-formal research paper. If you have never written a research paper before, that's OK, you just need to follow the instructions here. You may wonder *why* you need to write a paper, in fact why aren't you just submitting your code? Well, submitting code is well and fine, but in order to truly check if you have understood anything, you need to explain it. It's 10x harder to explain what you have done than it is to do it. The reality is, if you want to get hired or be useful, you need to be able to explain what you have done and why.  A research paper format is an *excellent* way to do this.


## Abstract

Sell your project in 6-8 sentences.  Answer these questions
* What is the problem? Why is it a problem? Why should I (or anyone at all) care about this problem? 
* What have other people done to solve the problem (existing solutions). Why are they not good enough? What limitations do they have?
* What is your solution and how does it solve the problem and address those limitaitons
* What are you results - tell me in numbers (X % accuracy, Y F1-score, etc)

## Introduction

Take every sentence of your abstract (which answered all those questions) and expand it into paragraphs. The introduction repeats everything that happened in the abstract, with more detail. End your introduction by explaining very clearly what you did. "In this work we took dataset X, performing algorithms Y, and found out results Z."

## Related Work

Tell us about how other people have solved this problem. You may have no idea - that's OK. Spend a little time researching it, you don't need to do any in depth literature review (this isn't grad school), but it's good to have _some_ idea how others have approached the problem. You can organize it two ways. Chronologically or Topologically.  Chronologically is just by time, who did what when at what point in time. Topologically is by method, different kinds of techniques to solve the problem.  However you present it, just make sure it's logical and follows a flow.  This section can be endless since it's research based, so make of it what you _you_ want.

## Methodology

This is the meaty part of the paper. What did you do and how? I should be able to reproduce all your work by reading this section.

### Dataset

What dataset did you use and why? Where did you get it? How many datapoints are there? Tell us all interesting and relevant facts you learned about the dataset. Show some Exploratory Data Analysis (EDA) if appropriate.

### Baseline Model

What is your baseline model. Why?

### Algorithms

What algorithms will you use, why? Describe the algorithms briefly (how do they work)

### Metrics

What metrics are you using to evaluate your model? Why? Describe what the metrics are measuring (you can show equations or not, your choice) and why that metric suits your problem well.  

### Experiments

What experiments will you run? Do you do a hyper-parameter search? What space did you search? How did you search it?

## Results and Analysis

You should have a few tables / charts showing the results of your experiments. What as the best model, what were the best parameters.  What tradeoffs did you find?  It's important not to flood the report with _all_ your results. It's very tempting to want share everything you discovered, however that makes for a very hard to read paper.  Instead, focus on the most important results. What are the key insights?

## Conclusion

What did you do, what did you learn, How did it go? What would you do different next time? What unanswered questions do you have?

