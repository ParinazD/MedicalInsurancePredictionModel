**Medical Insurance Predictor**
---------------------------------------------------

Environment Requirements to Install [shortened]: 

matplotlib              |                3.10.5
matplotlib-inline       |                0.1.7
numpy                   |                2.3.2
openai                  |                1.107.3
pandas                   |               2.3.1
scikit-learn                            1.7.1
scipy                                   1.16.1
:::::
:::::
:::::
zipp                                    3.23.0
'''_

**Layout of the Code**
- Data Cleansing and categorization
    - used sklearn to spit training and testing data (95-5 Ratio)
    - mapped answers like yes/no and word descriptions of regions to understandable numbers 
    - used numpy arrays for features and labels
- Gradient Descent
    - Compute Cost - Used MSE 
    - Gradiet Descent - parameters are updated, moving opposite to the gradient at a learning rate
- Prediction
    - Calcuate the dot product between optimized weights and features test
    - Flattened using .ravel method for numpy arrays
- Evaluation
    - Used MAE - Mean Absolute Error


*Data Obtained From Kaggle© Data Sets*
