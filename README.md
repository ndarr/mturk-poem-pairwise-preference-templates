# Templates for Pairwise Preference annotation using Amazon Mechanical Turk
Repository containing various templates to be used with Amazon MTurk for pairwise preference annoations with custom questions.

## Usage
Copy the desired template into *Design Layout* when creating a new Project on Amazon MTurk

## Descriptions

### pairwise-pref.html
Template assumes a csv with the following columns as input:
```
poem1, poem2, question1, question1_id, question2, question2_id, question3, question3_id, question4, question4_id 
```
*question4* and *question4_id* are optional and can be left blank. In this case only the first 3 questions are displayed to the annotator.

*TODO* Insert photo here

### pairwise-pref-with-na.html
Similar setup as the previous template but with an additional *n/a* field in the form to allow annotators not only decide between poem1 and poem2 but also left a question undecided.

*TODO* Insert photo here

### pairwise-pref-ext.html
Template with 5 questions and no blank fields allowed, displaying a binary choice for each question.
```
poem1, poem2, question1, question1_id, question2, question2_id, question3, question3_id, question4, question4_id, question5, question5_id 
```
*TODO* Insert photo here
