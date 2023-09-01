import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
from sklearn.preprocessing import MinMaxScaler
from statsmodels.tsa.seasonal import seasonal_decompose
import numpy as np



from sklearn.base import BaseEstimator, RegressorMixin
from sklearn.metrics.pairwise import rbf_kernel
from sklearn.utils import check_X_y, check_array
from sklearn.exceptions import NotFittedError
from scipy.sparse.linalg import lsmr
from sklearn.linear_model import LinearRegression,LogisticRegression

from sklearn.model_selection import KFold
from sklearn.datasets import make_regression
from sklearn.neural_network import MLPRegressor
from xgboost import XGBRegressor
from mlxtend.regressor import StackingRegressor,StackingCVRegressor
from sklearn.model_selection import train_test_split,cross_val_score
from sklearn.metrics import mean_squared_error

import statsmodels.api as sm
from statsmodels.tsa.stattools import adfuller
import pymannkendall as mk
import seaborn as sns

from statsmodels.graphics.tsaplots import plot_acf,plot_pacf



from statsmodels.tsa.arima.model import ARIMA


# Time-Series-and-machine-Learning
