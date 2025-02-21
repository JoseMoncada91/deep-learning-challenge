AlphabetSoupCharity_Optimization - Deep Learning Challenge
Jose Moncada - Module #21

Project Overview
This project is part of Module 21 - Deep Learning Challenge. The goal is to build, train, and optimize a deep learning model to predict the success of charitable donations using a dataset from AlphabetSoup.

Files in This Repository
AlphabetSoupCharity_Optimization.h5 - The trained and saved deep learning model.
AlphabetSoupCharity.h5 - Original model file (before optimization).
AlphabetSoupCharity_Optimization.ipynb - Jupyter Notebook containing data preprocessing, model creation, training, evaluation, and optimization steps.
Starter_Code.ipynb - Jupyter Notebook containing the original code for data preprocessing and basic model creation.
README.md - Project documentation (this file).
Report on the Neural Network Model.docx - A detailed report on the deep learning model.

Steps Completed
Data Preprocessing:
Loaded and cleaned the dataset.
Encoded categorical variables.
Scaled the numerical features.

Model Creation:
Built a sequential deep learning model using TensorFlow/Keras.
Used appropriate activation functions and loss metrics.
Training & Evaluation:
Trained the model with multiple epochs and batch sizes.
Evaluated model performance using accuracy and loss.

Optimization:
Adjusted hyperparameters (number of layers, neurons, activation functions).
Improved the model performance from the baseline.

Model Export:
Saved the trained model to an HDF5 file (AlphabetSoupCharity_Optimization.h5).

Notes
The saved model file is located in the same directory as the project files.
Despite multiple optimization attempts and consulting with ChatGPT, the model did not reach the target accuracy of 75%. The final model achieved around 73.2% accuracy.
The model was optimized for improved accuracy compared to the initial baseline model.
I've included in GitHub a Word document with the report named Report on the Neural Network Model.docx.

Instructions for Running the Model
Ensure Python is installed along with TensorFlow, Pandas, and Scikit-learn.
Run the Jupyter Notebook (AlphabetSoupCharity_Optimization.ipynb) to train and evaluate the model.
The final trained model is saved as AlphabetSoupCharity_Optimization.h5 and can be loaded for future predictions.

Contact
For any questions or clarifications, please reach out to Jose Moncada
