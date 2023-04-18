# Prediction using Decision Tree Algorithm

**Objectives**:

- Create the Decision Tree classifier and visualize it graphically.
- If we feed any new data to this classifier, it should be able to predict the right species.

## Highlights

How does the Decision Tree model predict species after training?

Let's say we have an unassigned flower with Sepal Length = 6.0, Sepal Width = 4, Petal Lenth = 2.5 and Petal Width = 0.3

Now, we will go down the tree in the following manner until we reach a leaf node:

1. Is the petal_length smaller than or equal to 2.45? **No**. We can see that it is **2.5**. **So we will go to the right node**.
2. Is the petal_width smaller than or equal to 1.75? **Yes**. We can see that it is **0.3**. **So, we will go to the left node**.
3. Is the petal_length smaller than or equal to 4.95? **Yes**. It is **2.5**. **So, we will go to the left node**.

![Decision Tree Visual](https://user-images.githubusercontent.com/123200960/232798618-69b2cc7f-22e3-4a2a-bca8-9b1d191a1014.png)

View the [Notebook](https://github.com/You-sha/Prediction-using-Decision-Tree/blob/main/Notebook.ipynb) for the full project with a step-wise explanation.
