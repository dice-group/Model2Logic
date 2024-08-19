This reporsitory contains code implementing the idea introduced in the paper [Trading-Off Interpretability and Accuracy in Medical Applications: A Study Toward Optimal Explainability of Hoeffding Trees](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10611982). The idea of the paper was to use logical explanations to reduce the features that are `least important', and remove them incrementally to find out how much we gain in interpretability and how much we lose in terms of accuracy. Our aim was to compute an optimal point between the two.

The core idea of the paper is to convert the model into logical formula and compute explanations for individual example (i.e, input-output). To this end, this reporsitory contains files to perform such a conversion for different models, Gradient Boosting, Feedforward neural network and the random forest. The notebooks provided in this reporsitory could be easily used to generate the logical formula given the model.


