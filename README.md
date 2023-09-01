


## Project Description

This is my Final Year project as Bachelor of Science Degree holder in Geomatic Engineering Titled: Assessing the Spatiotemporal Variability of Precipitable Water vapour in Africa using machine learning. This project assess how climatic conditions vary both time and in space using data analytics. The main Language used in this project is Python data science FrameWorks listed in the dependencies below

## Table of Contents

- [Installation](#installation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contribution](#contribution)


## Installation

Follow these steps to set up and run the project:

1. Clone this repository:

      git clone https://github.com/martinaborgeh/Least-Square-Adjustment.git



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


## Usage
### For Local Geoid
1. Specify the train data in the obj.readdata() method and test input data in the read_data() method assigned to the new_data varible in geoid_model() method. the train and test sampple is found in the cloned directory 
2. Running Local_Geoid will generate the local geoid model for converting ellipsoidal height to corresponding orthometric heights
### For Levelling Least Square Adjustment Geoid
1. Run the MainUiConnect.py file to run the application
2. Enter or import data from excel
3. select appropriate output requirement and compute
4. Export the Error Assessment and the Most probable Height to Excel.



<!-- You can add screenshots or GIFs here to demonstrate the usage -->

## Contribution

We welcome contributions to this project! If you'd like to get involved, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Open a pull request to merge your changes into the main branch.
