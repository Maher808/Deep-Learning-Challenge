# Deep-Learning-Challenge

# ** The Result **

## 1) The purpose of the analysis:

- To develop a binary classification model using deep learning techniques to predict whether organizations funded by Alphabet Soup, a nonprofit foundation, will be successful in their ventures. The model aims to aid Alphabet Soup in selecting the most promising applicants for funding, thereby maximizing the impact of their investments.
- By leveraging machine learning algorithms and neural networks, this analysis seeks to automate the process of evaluating funding applicants. This automation can help save time and resources for Alphabet Soup's business team, allowing them to focus their efforts on other critical tasks.

## 2) Data Preprocessing:

- Target Variable(s): The target variable for our model is 'IS_SUCCESSFUL', which indicates whether an organization was successful after receiving funding.
- Features: The features for our model include all other columns in the dataset except 'IS_SUCCESSFUL'.
- Variables to be Removed: The 'EIN' and 'NAME' columns were removed from the input data as they are neither targets nor features.

## 3) Compiling, Training, and Evaluating the Model:

- Neurons, Layers, and Activation Functions: The model consists of two hidden layers with 10 and 8 neurons, respectively. ReLU activation functions are used in the hidden layers, while the output layer uses a sigmoid activation function to produce binary classification probabilities.
- Target Model Performance: The target model performance was to achieve an accuracy higher than 75%. However, the best final accuracy achieved was  72.793 %.
- Steps to Increase Model Performance: Several steps were taken to increase model performance, including preprocessing techniques such as binning and one-hot encoding, optimizing the neural network architecture, tuning hyperparameters, and standardizing the data. Despite these efforts, the target performance was not achieved.

## 4) Summary:

In summary, the deep learning model developed for Alphabet Soup achieved a moderate level of accuracy but fell short of the target performance. To further improve model performance, additional strategies could be explored. One recommendation is to try different neural network architectures, such as convolutional neural networks (CNNs) or recurrent neural networks (RNNs), which may capture complex patterns in the data more effectively. Additionally, ensemble methods such as random forests or gradient boosting could be employed to combine multiple models for better predictive performance. By experimenting with different models and techniques, Alphabet Soup can continue to refine its approach to predicting the success of funded organizations and optimize its impact in the philanthropic space.