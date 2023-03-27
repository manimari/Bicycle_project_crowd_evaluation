# Bicycle project crowd evaluation 

The dataset 

The dataset presented here was collected with the purpose of evaluating the quality and
performance of a new crowd: The tasks are based on images which were taken from an
automotive dataset (https://www.a2d2.audi) and show typical things you would see on a
street. The question asked to the annotators was “Do you see a bicycle?”. The annotators
were able to pick “yes” or “no” to answer the question. They also had the option to select
“can’t solve” if they are unable to decide or “corrupt data” to flag an issue with the data. 

The dataset to use in this project consists of two files:  

The annotator responses which is the file anonymized_project.json and the reference dataset called
references.json. 

The annotator responses will show for each task the task_input (i.e. what was sent to the
annotator), their response task_output, as well as some metadata about the vendor (=crowd)
and the annotator (=user). 


Tasks 

1. Gather insights about the annotators: 

a. How many annotators did contribute to the dataset? 

b. What are the average, min and max annotation times (durations)? Feel free to
add visual representations here such as graphs if you like. 

c. Did all annotators produce the same amount of results, or are there
differences? 

d. Are there questions for which annotators highly disagree? 

2. Besides picking yes or no the annotators had the chance to tell if the data were
corrupted or if they for any reason were not able to solve the task. These are fields
'cant_solve' and 'corrupt_data' given in the task_output. 

How often does each occur in the project and do you see a trend within the
annotators that made use of these options? 

3. Is the reference set balanced? Please demonstrate via numbers and visualizations. 

4. Using the reference set, can you identify good and bad annotators? Please use
statistics and visualizations. Feel free to get creative. 

5. Please prepare a small presentation to summarize your findings.

