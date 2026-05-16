Goal:
The goal of the problem is to predict whether a passenger was satisfied or not, considering his/her overall experience of traveling on the Shinkansen Bullet Train.

Dataset: 

The problem consists of 2 separate datasets: Travel data & Survey data. Travel data has information related to passengers and attributes related to the Shinkansen train, in which they traveled. The survey data is aggregated data of surveys indicating the post-service experience. You are expected to treat both these datasets as raw data and perform any necessary data cleaning/validation steps as required.

The data has been split into two groups and provided in the Dataset folder. The folder contains both train and test data separately.

Train_Data
Test_Data

Target Variable: Overall_Experience (1 represents ‘satisfied’, and 0 represents ‘not satisfied’)

The training set can be used to build your machine-learning model. The training set has labels for the target column - Overall_Experience.

The testing set should be used to see how well your model performs on unseen data. For the test set, it is expected to predict the ‘Overall_Experience’ level for each participant.

Data Dictionary:

All the data is self-explanatory. The survey levels are explained in the Data Dictionary file.

Submission File Format: You will need to submit a CSV file with exactly 35,602 entries plus a header row. The file should have exactly two columns

ID
Overall_Experience (contains 0 & 1 values, 1 represents ‘Satisfied’, and 0 represents ‘Not Satisfied’)

Evaluation Criteria:

Accuracy Score: The evaluation metric is simply the percentage of predictions made by the model that turned out to be correct. This is also called the accuracy of the model. It will be calculated as the total number of correct predictions (True Positives + True Negatives) divided by the total number of observations in the dataset.
 
In other words, the best possible accuracy is 100% (or 1), and the worst possible accuracy is 0%



Rules:

There is no limit on the number of submissions. You are free to make as many submissions as you like until the submission deadline. If you make multiple submissions, the one with the highest accuracy score will be considered your best and final submission after the deadline.

You can use any technique you’re aware of. There are no restrictions as far as any techniques or tools are concerned.

The winners of the hackathon will be announced during the Completion Ceremony. 

The hackathon will start on April 19th, 2026 at 4 AM GMT / 12 AM ET(US), and will end on April 23rd, 2026 at 12 PM GMT / 8 AM ET(US). No submissions will be accepted after the deadline.

A learner can participate in the Hackathon as an individual or in a team of upto 3 members.

You will only be allowed to form a team with other members from the same cohort.

You are not allowed to use any external data to train your model. Only the training dataset provided to you, or a subset of it, is meant to be used for this purpose.

Throughout the hackathon, you are expected to respect fellow hackathon participants and act with high integrity.

Frequently Asked Questions:

1. What is the mode of the hackathon?
The hackathon will be conducted online. You will need an internet connection to access the hackathon problem statement, supporting material, and make submissions.

2. Will Great Learning provide any problem-solving support?
With this being a competitive hackathon, Great Learning will not be providing any academic or code-related support.

3. What is the ideal solution to the problem? Will I receive a solution notebook after the hackathon results are published?
In a hackathon, you build the capability to evaluate multiple approaches to the same problem against each other and build an intuition around which approach may be suitable for a specific scenario. As such, there is no ideal solution to the problem. You are allowed to use any technique within the constraints of the rules to maximize your model’s performance on the evaluation metric, as seen in the submission file. 

There will be no solution notebook provided for this hackathon.

4. I have uploaded my file, but it shows an error. What should I do?

If the error is “Please check the format of the file you uploaded (Check column names)” then check the following points:

Format of the file - The file format should be  CSV
Check the labels of the column (should be the same as provided in the sample submission). Please check for trailing or leading spaces in column names.
Check whether your submission file contains only 2 columns as provided in the Sample Submission.csv.
The first column must be the ID, and the second column must be the  Overall_Experience. So, check whether the columns are interchanged in your submission file. The column names in the submission file should be in the specified order.
Check the number of rows in the submission file (should be equal to the rows in the test dataset)

5. What does accuracy on the leaderboard mean?
Since this is a classification problem, we are using accuracy as the evaluation metric. Here, accuracy means the total number of values predicted correctly divided by the total number of predictions made. In this case, the higher the accuracy, the better the model, and the accuracy will be in a percentage between 0 and 100.

6. I have submitted my file, but I can’t see my score (accuracy) on the leaderboard.
The leaderboard sometimes takes a few minutes to get refreshed. 
Please try again after 15 minutes.

In case you have any other queries apart from the above FAQs, please contact your Program Manager, and they should be able to help.
