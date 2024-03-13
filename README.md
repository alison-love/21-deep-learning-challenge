## Alphabet Soup Charity Funding Predictor

### Overview

This project aims to predict the success of funding applications to Alphabet Soup’s charity using machine learning and neural networks. Starting with an initial model, we employed hyperparameter tuning with Keras Tuner to optimize performance. The project's challenge was to surpass a target predictive accuracy of 75%.

### Phase 1: Initial Model Development

#### Data Preprocessing
Target Variable: IS_SUCCESSFUL indicates if the funding was used effectively.

Features Used: EIN and NAME were dropped as identifiers, leaving all other column data as features used for the model.

#### Model Configuration
A neural network model with an input layer, two hidden layers, and an output layer was compiled and evaluated.

#### Training and Initial Results
The model achieved a validation accuracy of approximately 72.47%, indicating room for improvement.


### Phase 2: Model Optimization with Keras Tuner

#### Hyperparameter Tuning
Employed Keras Tuner to explore various architectures and configurations. Optimizations included testing different layers, units, and activation functions.

#### Results
Accuracy: Upon final evaluation on the test set, the model demonstrated a test accuracy of 72.64%, serving as the measure of the model's ability to generalize to new data.

### Conclusion and Future Directions

The optimized model shows promising results, with a test accuracy of 72.64%. While still shy of the 75% target, the improvements demonstrate the value of hyperparameter tuning in enhancing model performance.


charity_data.csv: Dataset file.
AlphabetSoup.ipynb: Jupyter Notebook for initial model development.
AlphabetSoupOptimization.ipynb: Notebook detailing the optimization process.
