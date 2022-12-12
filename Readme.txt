Extractive Text Summarization

Initially give the DUC 2001 dataset where files are there in XML format. The parser will convert the data into .csv files.

The csv files is cleaned by removing the null values from the dataset and also dealt with the abnormal data.
In this step we have removed stop-words, punctuation marks from the data. We have also applied stemming and lemmatization to make the data more clean for further processing.

After cleaning the dataset, apply different scoring techniques to calculate the individual scores of each sentences. This scores are now used for generation of the final summary.

Then on the basis of sentece score obtained the sentences having highest score’s are selected and then used for generating the final summary.

Then we compare our generated summary with the golden summary and find the rouge and blue score which tells us how much our system generated summary is accurate in comparison with the golden summary.

Then we analyze the Rouge & Blue score and after analyzing the score we will select combinations of 3 techniques for further score improvement and make graph for analysing it.

The we take combinations of scoring techniques having the highest score in individual methods which will improve the accuracy of the generated summary.

Then we will apply the optimization algorithm which will improve the sentence score by using heuristic function of cuckoo and TLBO algorithm.