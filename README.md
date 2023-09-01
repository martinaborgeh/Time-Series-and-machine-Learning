


## Project Description

This is my Final Year project as Bachelor of Science Degree holder in Geomatic Engineering Titled: Assessing the Spatiotemporal Variability of Precipitable Water vapour in Africa using machine learning. This project assess how climatic conditions vary both time and in space using data analytics. The main Frameworks or packages used in this project is Python data science FrameWorks listed in the dependencies below

## Table of Contents

- [Installation](#installation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contribution](#contribution)


## Installation

Follow these steps to set up and run the project:

1. Clone this repository:

      git clone https://github.com/martinaborgeh/Time-Series-and-machine-Learning.git



2. Download and install Anaconda(Comes with Jupyter IDE.

3. Open the cloned folder as your project directory.

4. Install the required dependencies:

The dependencies are found below. Run 'pip install package_name1,package_name1 etc' to install all dependencies needed for the project



## Dependencies

The project relies on the following dependencies:

-pandas

-matplotlib.pyplot

-numpy

-sklearn

-statsmodels

-scipy

-xgboost


-mlxtend

-pymannkendall

-seaborn


## Usage for Each File
1. Project_Functions_Definitions.ipynb contains all the dependencies and Functions needed for actual analysis by the other files
2. Time Series Forecasting with Autoregressive.ipynb extends the Project_Functions_Definitions.ipynb. It forecast time series data based on past lagged values 
3. Moving Average.ipynb extends the Project_Functions_Definitions.ipynb. It forecast time series data based on window averages taking into considerations past forecast errors
4. Autoregressive Integrated Moving Average.ipynb extends the Project_Functions_Definitions.ipynb and combines both moving average and Autoregressive models
5. Machine_Learning_prediction.ipynb extends the Project_Functions_Definitions.ipynb. It predicts future values using Xgboost, Least Square Support Vector Machine and MultiLayer Perceptron as base models in s Stacked ensemble models.
6. Time_Series_Annual_Seasonality.ipynb extends the Project_Functions_Definitions.ipynb and involves time series analysis and data analytics Techniques
7. Model Accurace Accessment.ipynb extends the Project_Functions_Definitions.ipynb and it contains the stacked ensemble and time series model accuracy assessment and comparisoms.
8. Final Powerpoint_Revised_Re-updated Defense_Ready.ptx is the Summarised PowerPoint Presentation of the whole Project



<!-- You can add screenshots or GIFs here to demonstrate the usage -->

## Contribution

We welcome contributions to this project! If you'd like to get involved, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Open a pull request to merge your changes into the main branch.
