1. What does the equation for the loss function do conceptually?
- Mathematically define network outputs
- Reward indecision
- Ignore historical statistical developments
- ```Penalize overconfidence```

2. What is overfitting?
- Model complexity is perfectly matched to the data.
- Model complexity is not enough to capture the nuance of the data and will under-perform in the real-world.
- ```Model complexity fits too well to training data and will not generalize in the real-world.```
- Overfitting refers to the fact that more complexity is always better, which is why deep learning works.

3. Why should the test set only be used once?
- ```More than one use can lead to bias.```
- It is expensive to use more than once.
- The model cannot learn anything new from subsequent uses.
- More than one use can lead to overfitting.

4. Which two of the following describe the purpose of a validation set?
- ```To estimate the performance of a model.```
- ```To pick the best performing model.```
- To test the performance in lieu of real-world data.
- To learn the model parameters.

5. How do we learn our network?
- Downhill skiing
- ```Gradient descent```
- Monte Carlo simulation
- Analytically determine global minimum

6. What technique is used to minimize loss for a large data set?
- ```Stochastic gradient descent```
- Gradient descent
- Newton's method
- Taylor series expansion

7. Which of the following are benefits of stochastic gradient descent?
- ```With stochastic gradient descent, the update time does not scale with data size.```
- Stochastic gradient descent gets near the solution quickly.
- Stochastic gradient descent finds a more exact gradient than gradient descent.
- ```Stochastic gradient descent can update many more times than gradient descent.```
- Stochastic gradient descent finds the solution more accurately.

8. Why is gradient descent computationally expensive for large data sets?
- ```Calculating the gradient requires looking at every single data point.```
- There are too many local minima for an algorithm to find.
- Large data sets require deeper models, which have more parameters.
- Large data sets do not permit computing the loss function, so a more expensive measure is used.

9. What are the two main benefits of early stopping?
- ```It helps save computation cost.```
- ```It performs better in the real world.```
- It improves the training loss.
- There is rigorous statistical theory on it.

10. Why are optimization and validation at odds?
- Optimization seeks to do as well as possible on a training set, while validation seeks to do as well as possible on a validation set.
- ```Optimization seeks to do as well as possible on a training set, while validation seeks to generalize to the real world.```
- Optimization seeks to generalize to the real world, while validation seeks to do as well as possible on a validation set.
- They are not at odds—they have the same goal.
