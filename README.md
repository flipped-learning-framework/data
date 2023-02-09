# Data for Evaluation

We provide data of student performances (course report.csv), polls (in-class polls.xlsx), and feedback (in-class polls and feedback statistics.xlsx).

Due to privacy concerns, we have removed all personal infomartion such as user ID and username.

## Data for the evaluation of the unfolded RNN model:

Files: evaluation data of 2019.csv and evaluation data of 2020.csv.

### Format
The format of the csv file is:
<ul>
<i>probID: problem ID</i>
<i>sID: student ID</i>
<i>probAns: correct problem answer</i>
<i>answer: student's answer</i>
<i>correct: true means student answer the question correctly, false means student answer the question incorrectly.</i>
<i>answerat: student's answer time</i>
<i>publishat: the problem publish time</i>
<i>question type:</i>
-3 this is a hard pre-class quiz
-2 this is a easy pre-class quiz
-1 this is a pre-class quiz
<i>positive numbers: this is a time limited in-class quiz</i>
</ul>

in comma-separated columns.
