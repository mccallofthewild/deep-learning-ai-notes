# Deep Learning AI Notes 👩‍🔬
Deep Learning Concepts, Algorithms, Code &amp; more

## Resources
* 📝[Deep Learning Notation *by Andrew Ng*](/resources/deep-learning-notation.pdf)
* ⏮[Backpropagation \[in Detail\] *by J.G. Makin of Cornell*](/resources/backpropagation.pdf)

## Cheatsheets 
* [Mahmoud Badry's DeepLearning.ai Summary](https://github.com/mbadry1/DeepLearning.ai-Summary)

## Code

    Cost function and its gradient for a propagation

    Arguments:
    w -- weights, a numpy array of size (num_px * num_px * 3, 1)
    b -- bias, a scalar
    X -- data of size (num_px * num_px * 3, number of examples)
    Y -- true "label" vector (containing 0 if non-cat, 1 if cat) of size (1, number of examples)

    Return:
    cost -- negative log-likelihood cost for logistic regression
    dw -- gradient of the loss with respect to w, thus same shape as w
    db -- gradient of the loss with respect to b, thus same shape as b
    
    Tips:
    - Write your code step by step for the propagation. np.log(), np.dot()
