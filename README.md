# Machine-Learning
Machine Learning Practicals 

### Building Stacked Ensembles
Stacking is an interesting approach to building ensemble models that is
particularly effective when heterogenous mixes of base classifiers is used. While
less commonly used than its bagging and boosting counterparts, the stacked
ensemble idea has been around for as long as ensemble models have been
popular in machine learning - for example (Wolpert, 1992). In stacked
ensembles a set of base classifiers are trained, and their outputs are combined
into a training set for the stack layer classifier. One of the main challenges in
building effective stacked ensembles is designing the process to generate the
data to train the models at the stack layer.
The task in is to implement a selection of stacked ensemble approaches.

The 3 Stacked Ensembles implimented are:
1. StackedEnsembleClassifierHoldOut -That uses a hold-out test set to generate the stack training dataset.
2. StackedEnsembleClassifierKFold - That uses a k-fold cross validation approach to generate the stack training dataset.
3. StackedEnsembleClassifierOneVsOne 


### Lunar Lander
Different Task performed in this are
1. Train a supervised machine learning model to control the Lunar Lander craft based on the image dataset.
  • Images were converted to greyscale.
  • Images were shrinking.
  • Class imbalance in the dataset was handelled.
2. Use the DeepQLearning reinforcement learning algorithm to train an agent to play the Lunar Lander.




