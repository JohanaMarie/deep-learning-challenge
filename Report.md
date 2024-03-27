Neural Network Model Report

OVERVIEW:
    The of this neural network is to help the charity Alphabet Soup identify the most promising donation recipients with an accuracy rate of 75% or higher.

RESULTS:
    Data Preprocessing
        What variable(s) are the target(s) for your model? 
            The 'IS_SUCCESSFUL' column was used as the tartget variable.
        What variable(s) are the features for your model?
            'CLASSIFICATION,'APPLICATION_TYPE',and 'AFFILIATION' are a few examples pfe the feature variables for this model.
        What variable(s) should be removed from the input data because they are neither targets nor features?
            The'EIN' and 'NAME' columns were removed. They did not add value do the predictive capability of the model.
    Compiling, Training, and Evaluating the Model
        How many neurons, layers, and activation functions did you select for your neural network model, and why?
            Initially, a neural network model with two hidden layers and ReLU activation functions was chosen. The number of neurons in each layer was determined based on experimentation to try to get the accurace rate up. Unfortunaely I was unable to get the accuracy higher then 75%.
        Were you able to achieve the target model performance?
            Despite numerous attempts to optimize the model, the target performance of 75% accuracy was not achieved.
        What steps did you take in your attempts to increase model performance?
            Adjusting the model architecture by increasing the number of neurons and layers, experimenting with different activation functions, and modifying the learning rate.

SUMMARY:
    Despite several optimization attempts, the deep learning model failed to achieve the target predictive accuracy of 75% for identifying successful donation recipients for Alphabet Soup. Various adjustments to the model's architecture and parameters, including changes in neuron counts, activation functions, and learning rates, were explored but did not yield significant improvements. Further exploration of advanced techniques and feature engineering is necessary to enhance model performance in future iterations.
