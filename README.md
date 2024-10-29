# Urban-Sounds-Classification
Assignment of the course Machine Learning II (BSc in Artificial Intelligence and Data Science 3rd year, 1st semester)

## A little context
This project is divided into 10 notebooks, all run on Google Colab, for the sake of simplification in terms of dependencies, except for notebooks 8, 9, and 10.

For these last three notebooks, it will be necessary to:

* Have the following Python version: Python 3.9.5
* Install TensorFlow: TensorFlow can be installed directly in the Jupyter notebook with
  ```!pip install tensorflow.```
  
### Notebooks:

#### Data Preprocessing and Preparation:

1. Data_Pre_Processing: Proceeds with data preprocessing,
2. Feature_Extraction: Performs MFCC (Mel-Frequency Cepstral Coefficient) extraction,
3. Label_Extraction: Performs one-hot encoding of classes and creates 3D arrays.

#### Implementation of classifiers, structuring, and data preparation:

4. test_main_functions: Contains all general functions for iteration and 10-fold cross-validation.

#### Definition of model architectures:

5. Architectures: Defines the architecture of recurrent neural networks (RNN) and Multi-Layer Perceptron (MLP).
6. Bidirectional_rnn: Trains the bidirectional recurrent neural network for one iteration, incorporating its architecture.

#### Training strategy and performance evaluation:

7. Hyperparameters: Manually tests different hyperparameters.
8. Best_Hyperparameters: Automates testing of all possible combinations of different hyperparameters for the MLP neural network for one iteration. Uses TensorBoard.
9. Individual_Best_Hyperparameters: Automates hyperparameters individually, where each hyperparameter is assigned 3 possible values. Parameters are then individually "isolated" in a list to be assigned these values, while the rest maintain the assigned value for comparison. Uses TensorBoard and MLP.
10. Robustness: Evaluates the robustness of neural networks for one iteration.

