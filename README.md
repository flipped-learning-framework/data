# Data for Evaluation

We provide data of student performances (course report.csv), polls (in-class polls.xlsx), and feedback (in-class polls and feedback statistics.xlsx).

Due to privacy concerns, we have removed all personal infomartion such as user ID and username.

## Data for the evaluation of the unfolded RNN model:

Files: evaluation data of 2019.csv and evaluation data of 2020.csv.

The format of the csv files is:
* probID: problem ID
* sID: student ID
* probAns: correct problem answer
* answer: student's answer
* correct: true means student answer the question correctly, false means student answer the question incorrectly
* answerat: student's answer time
* publishat: the problem publish time
* question type: -3 this is a hard pre-class quiz; -2 this is a easy pre-class quiz; and -1 this is a pre-class quiz
* positive numbers: this is a time limited in-class quiz

in comma-separated columns.
