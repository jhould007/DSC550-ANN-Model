# DSC550-ANN-Model
An assignment for DSC550 (Neural Networks and Deep Learning) at GCU that focused on building an artificial neural network to select an optimal American football team based on publicly-available NFL player data.

Check out the full report [here.](https://github.com/jhould007/DSC550-ANN-Model/blob/master/ANN%20Model.ipynb)

# Assignment Instructions

# Part 1
Download the ["NFL Players Dataset"](https://www.kaggle.com/datasets/toddsteussie/nfl-play-statistics-dataset-2004-to-present/data), located in the topic Resources. The dataset contains football players' characteristics.

1. Select from a pool of 200 "Active Players" and 200 "Retired Players." 
2. Define "optimal team" based on your decision of the player characteristics necessary to build a team:
    - Starting offense (11 players): passing, rushing, and receiving.
    - Starting special teams (11 players): punting, punt returns, and kick returns.
    - Starting defense (11 players): tackles, sacks, safeties, and fumbles.
3. Your task is to identify the optimal team from each pool comprised of 33 "Active Player" and "Retired Player" members. 
4. Examine the multilayer neural network MLP architecture depicted in the "DSC-550 An Artificial Neural Network Model Image."
5. Build a deep artificial neural network MLP to include the following: a) 1 input layer, b) as many hidden layers as you deem necessary, and c) an output layer fully connected to the hidden layers.
6. Explain your architecture and how the NFL player characteristics are used as inputs.

# Part 2

Activate the MLP by performing the following steps:

1. Starting at the input layer, forward propagate the patterns of the training data through the network to generate an output.
2. Based on the network's output, calculate the error that we want to minimize using a cost function that we will describe later.
3. Back propagate the error, find its derivative with respect to each weight in the network, and update the model.
4. Repeat steps 1 through 3 for multiple epochs and learn the weights of the MLP.
5. Use forward propagation to calculate the network output and apply a threshold function to obtain the predicted class labels in the one-hot representation.
6. Interpret the output of your MLP in the context of selecting an optimal football team.

While APA style is not required for the body of this assignment, solid academic writing is expected, and documentation of sources should be presented using APA formatting guidelines, which can be found in the APA Style Guide, located in the Student Success Center.
This assignment uses a rubric. Please review the rubric prior to beginning the assignment to become familiar with the expectations for successful completion.
You are not required to submit this assignment to LopesWrite.
