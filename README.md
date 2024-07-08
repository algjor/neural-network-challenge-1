# neural-network-challenge-1

## Background:

The following code is focused on predicting whether a borrower will repay their loan and provide a more accurate interest rate for the borrower. The code will create a model to predict student loan repayment.

The code will require functions, libraries, dependencies, import of a csv file, and Tensor Flow. 
This code is available at Github under (https://github.com/algjor/neural-network-challenge-1).

## Description of Code:
This code was completed using the following steps.

(1) - A repository was created called neural-network-challenge-1 in Git hub.

(2) - A starter code named student_loans_with_deep_learning.ipynb was created on the local Git repository and pushed to GitHub.

(3) - The csv file spam-data.csv was imported for the data analysis from the url https://static.bc-edx.com/ai/ail-v-1-0/m18/lms/datasets/student-loans.csv.

(4) - The csv file was then loaded into a Dataframe and a Scalar created to scale the features.

(5) - A deep neural network was created by assigning the number of input features, the number of layers, and the number of neurons on each layer using TensorFlow’s Keras.

(6) - A model was compiled and fitted using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric.

(7) - The model was then used to make predictions using the testing data.

(8) - A classification report was generated with the predictions and testing data.

(9) - The model was saved and exported to a keras file named student_loans.keras.

(10) - Key findings:

**1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.**

Answer:  The data to be collected to determine a students trustworthiness for a student loan would be based on the prior payment history, academic performance, the student's major, and length of time remaining to complete degree.  These factors would be captured with the following features in the dataset; Payment History, GPA Ranking, Study_Major_Code, and Time to completion.


**2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.**

Answer:  The above data would be suitable for collaborative filtering - as payment history, how well a student is performing within their respective major, and the type of major are good indicators for giving a student loan.  These factors could be used as a comparison with other students and their loan options.


**3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.**

Answer:  The challenges that would require consideration would be the age of the applicant - as a freshmen would not have an extensive payment history or cumulative GPA and the student may still be undecided in their respective major.  Due to the lack of having the maturity of these factors - a student may require a co-signer as an option.
