# 介紹
此專案使用sklearn提供之加州房價資料集，透過多元線性回歸對地區房價中位數進行預測

# 使用套件
import pandas as pd  
import numpy as np  
import matplotlib.pyplot as plt  
import matplotlib as mpl  
import wget  
from matplotlib.font_manager import fontManager  
from sklearn.linear_model import LinearRegression as LR  
from sklearn.model_selection import train_test_split  
from sklearn.datasets import fetch_california_housing  
from sklearn.metrics import mean_squared_error  
import scipy.stats as stats  
