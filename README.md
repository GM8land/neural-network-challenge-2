# neural-network-challenge-2

## Predict Attrition 

### Preprocessing 

- Feature Selection
- Split
- Scaling
- Encoding

### Modeling

- non-sequential Neural Network

### Evaluation

- Accuracy 

### Summary

1. Is accuracy the best metric to use on this data? Why or why not?

    - Since the attrition data is imbalanced, accuracy is probably not the best metric here. I would try an F1 score.

2. What activation functions did you choose for your output layers, and why?

    - I chose 'softmax' for the department output because department has 3 possible mutually exclusive values. I chose 'sigmoid" for attrition because that is a binary output 

3. Can you name a few ways that this model might be improved?

    - The 10 features I selected were based on what I thought would be most relevant to the model. If I was going further, I would try a PCA on the features, I would test different numbers of neurons in the layers.  I would also see if running more epochs would result in any improvements. 

