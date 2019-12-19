# UCSF DSI Hacky Hour
##### December 19, 2019

## Introduction

There is a lot involved in this problem, but you can expect this to take ~2 hours, so you'll only get a start today. And that's if you know what you're doing.

A beginner? All the better! This may be tough and take longer than 2 hours, but it will force you to think about complex coding problems (which is the best way to learn).

If you'd like to submit/discuss whatever code you write during the next Hacky Hour, please clone this repository and make your own branch to track your code. Don't know how? Ask the DSI!

You can use any language you'd like - I (Angelo) used R for this.

## The Challenge

You are working within a community hospital that is trying to do a better job managing 30-day readmissions of diabetic patients.  The goal is to create a clinical decision support (CDS) system that takes very basic data and identifies the chance that a patient will be readmitted within 30 days.

### Directions:

The following tasks are what you should roughly attempt to accomplish.

1. Explore the data through plots
2. Determine the best features
3. Cluster the data and calculate the silhouette score _(yes the data is claerly labeled... but we'll cluster it anyways)_
4. Classify the data and calculate accuracy, sensitivity, specificity, F1, and area under the curve

Remember, this will be an iterative process - **_have fun with it!_**

### Features available in your dataset:

1. Time in hospital (days)
2. Number of lab procedures during the admission
3. Number of interventional procedures during the admission
4. Number of medications ordered/administered during the admission
5. Number of outpatient visits this patient has had in the past
6. Number of emergency department visits this patient has had in the past
7. Number of in-patient stays this patient has had in the past
8. Last A1C result

The datset also contains a boolean field indicating whether or not the patient had a 30-day readmission. Happy coding!