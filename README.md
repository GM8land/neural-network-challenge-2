

## Module 19 Challenge: Predict Attrition 

### Instructions
You are tasked with creating a neural network that HR can use to predict whether employees are likely to leave the company. Additionally, HR believes that some employees may be better suited to other departments, so you are also asked to predict the department that best fits each employee. These two columns should be predicted using a branched neural network


### Requirements
- Preprocessing (40 points)
    - Import the data. (5 points)

    - Create y_df with the attrition and department columns. (5 points)

    - Choose 10 columns for X. (5 points)

    - Show the data types of the X columns. (5 points)

    - Split the data into training and testing sets. (5 points)

    - Encode all X data to numeric types. (5 points)

    - Scale the X data. (5 points)

    - Encode all y data to numeric types. (5 points)

- Model (40 points)
    - Find the number of columns in the X training data. (5 points)

    - Create an input layer. (5 points)

    - Create at least two shared hidden layers. (10 points)

    - Create an output branch for the department column. (10 points)

    - Create an output branch for the attrition column. (10 points)

- Summary (20 points)
    - Answer the questions briefly. (10 points)

    - Show understanding of the concepts in your answers. (10 points)

### Summary

1. Is accuracy the best metric to use on this data? Why or why not?

    - Since the attrition data is imbalanced, accuracy is probably not the best metric here. I would try an F1 score.

2. What activation functions did you choose for your output layers, and why?

    - I chose 'softmax' for the department output because department has 3 possible mutually exclusive values. I chose 'sigmoid" for attrition because that is a binary output
  

3. Can you name a few ways that this model might be improved?

    - The 10 features I selected were based on what I thought would be most relevant to the model. If I was going further, I would try a PCA on the features, I would test different numbers of neurons in the layers.  I would also see if running more epochs would result in any improvements. 

### Grade: 100 

### Grader Feedback:
Hi Geoff, thank you for this submission. Well done. You have managed to complete all the requirements of the submission successfully. This included the preprocessing steps, compiling the model, and responding to questions. Errors in your code did show up, however. This was while trying to fit the model and the variable y_train_attraition was used as an input. However, this variable was not assigned a value previously. As a recommendation, make sure to keep track of your variables and naming conventions. Overall, excellent work. All the best. Your Central Grading Team -YM.
