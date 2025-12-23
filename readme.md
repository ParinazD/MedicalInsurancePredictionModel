**Medical Insurance Predictor**
---------------------------------------------------

Environment Requirements to Install [shortened]: 

pip list --local

_Package                 |                Version
httpx-sse               |                0.4.1
huggingface-hub         |               0.35.0
idna                    |               3.10
importlib_metadata      |               8.7.0
jupyter_client          |               8.6.3
jupyter_core            |               5.8.1
keras                   |                3.11.2
matplotlib              |                3.10.5
matplotlib-inline       |                0.1.7
numpy                   |                2.3.2
ollama                  |                0.5.4
openai                  |                1.107.3
opentelemetry-api       |                1.37.0
opentelemetry-instrumentation   |        0.58b0
opentelemetry-instrumentation-threading | 0.58b0
opentelemetry-sdk        |               1.37.0
opentelemetry-semantic-conventions  |    0.58b0
pandas                   |               2.3.1
parso                    |               0.8.4
pexpect                  |               4.9.0
pillow                   |               11.3.0
pip                      |               25.2
platformdirs             |               4.3.8
prompt_toolkit           |               3.0.51
propcache                |               0.3.2
proto-plus               |               1.26.1
protobuf                 |               5.29.5
psutil                   |               7.0.0
ptyprocess               |               0.7.0
pure_eval                |               0.2.3
pyasn1                                  0.6.1
pyasn1_modules                          0.4.2
pydantic                                2.11.7
pydantic_core                           2.33.2
pydantic-settings                       2.10.1
Pygments                                2.19.2
PyJWT                                   2.10.1
pyparsing                               3.2.3
s3transfer                              0.14.0
scikit-learn                            1.7.1
scipy                                   1.16.1
setuptools                              69.1.0
six                                     1.17.0
strands-agents                          1.9.1
strands-agents-builder                  0.1.10
strands-agents-tools                    0.2.8
sympy                                   1.14.0
tenacity                                9.1.2
tensorboard                             2.20.0
tensorboard-data-server                 0.7.2
tensorflow                              2.20.0
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