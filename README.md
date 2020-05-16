# MTurk/Sagemaker labeling job

This is a very simple set of scripts intended to illustrate a simple labeling job for classifying text on AWS Sagemaker using a custom template.

There are four scripts:
- pre- and post- label custom function scripts (Python) for pre- and post- processing the labeling data. These functions do little other than pass the data through
- task_template.html is the template for the user interface that meets annotators
- jobs_html.txt is the data to label. This file consists of one json-object per line


