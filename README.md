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

### MNIST Fashion
Zalando, a fashion and technology company with a large presence in Dublin, have released MNIST Fashion, an alternative to the famous MNIST hand written digit classification dataset. The dataset contains 70,000 28x28 pixel grayscale images of fashion items of 10 different kinds: (0) T-shirt/top, (1) Trouser, (2) Pullover, (3) Dress, (4) Coat, (5) Sandal, (6) Shirt, (7) Sneaker, (8) Bag, and 9) Ankle boot. The task associated with this is to build a classification model that can recognise these different fashion items.


### Multi-armed Bandits
In this task policies for multiarmed bandit problem are implemented and compaired.
random arm selection policy, a greedy arm selection policy, and an 𝜀-greedy arm selection policy.
An 𝜀-first policy uses a random policy for the first N trials and then a greedy policy after that. 
An 𝜀-decreasing policy basically uses an 𝜀-greedy strategy except the value of 𝜀 decreases over time.


### Monkey Classification
The monkey species classification tasks from Kaggle https://www.kaggle.com/slothkong/10-monkey-species/home involves recognising 10 different species of monkey from disparate image types. The task is to build an accurate classification model for this scenario using different types of CNN model.

