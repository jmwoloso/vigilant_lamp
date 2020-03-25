# Lighthouse Data Challenge
Welcome to the Lighthouse data challenge, we are glad you are here! 

Let's get started. 

Take some time to read the instructions below. If you have
any questions _before you begin_, please send an email to 
[jwolosonov@lighthouseglobal.com](mailto:jwolosonov@lighthouseglobal.com)
and we will do our best to address your question(s) in a timely manner.



## Background
Lighthouse operates in the electronic discovery (e-discovery) industry.
E-discovery, as the name suggests, involves the discovery phase of a
legal proceeding. In the discovery phase, each party to the proceeding is afforded the 
opportunity to obtain facts and legal information (i.e. evidence) from 
the opposing party. We have developed a robust, industry-leading set of 
technologies that allow our clients to quickly and efficiently traverse 
vast amounts of information to ensure full compliance with the discovery
process. At Lighthouse, innovation runs deep. We are dedicated to our providing
our clients with state-of-the-art technologies that enable them to 
navigate the discovery process more efficiently. To that end, we are continuosly researching new and emerging 
technologies, incorporating the most promising among them into our 
products.



## The Challenge
We are interested in gauging your ability to take a machine learning 
project from conception to reality. In this data challenge, you are 
tasked with building a classification model using the supplied dataset.
To complete this challenge, you will need to create a fork of this
repository and commit your changes to the fork. When you are satisfied
with your model, open a pull request to this repository. Before opening 
a pull request, ensure that you have met the requirements
specified below.

You are expected to deliver the following in your pull request:

```
    1. submission.csv: A file containing the predictions from your
       model on the provided test dataset.
       
    2. training.py: A Python script that contains the logic used to
       train your model using the provided training dataset.
       
    3. METRICS.md: A markdown file indicating the evaluation metric(s) 
       you chose and your justification for choosing said metric(s).
       
    4. Any additional supporting python files, modules and packages that
       you need to create in order to successfully train your model on
       the training dataset and make predictions on the test dataset.
```


## The Data
In this repository, you will find a compressed CSV file called 
`train.csv.tar.bz2` 
containing the data that we would like you to use for the challenge. 
The features within the provided dataset are:
```
id: The unique identifier for the document
text: The text that should be used for modeling
class: The target that you are attempting to predict.
```

Additionally, you will find a CSV file named `test.csv.tar.bz2` that
contains the following features:
```
id: The unique identifier for the document
text: The text that should be used for making your submission file
```

_NOTE: Please refrain from
using any data sources other than what you might find in the CSV files._ 

## Code Requirements
You are required to complete this challenge using Python 3 
(version 3.6 or later). Within that scope, you are free to use whichever
libraries and frameworks allow you to get the job done.

We will attempt to run your code as-is, so you should include everything
we might need (or some mechanism for getting everything we might need)
to successfully run your code.

## Evaluation
For this challenge, _you_ are tasked with selecting the appropriate
metric(s) with which to evaluate your model. As mentioned above, you will
need to provide justification for your choice(s).

## Timeline
There is no pre-determined timeline for the project, however it is
important to remember that you are competing against other candidates.

## Submission Instructions
Once your confident in your solution, submit a pull request and our team
will evaluate your solution.

Good luck!
