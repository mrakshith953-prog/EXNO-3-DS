

import pandas as pd
     

df=pd.read_csv("/content/Encoding Data.csv")
df
     
ORDINAL ENCODER


from sklearn.preprocessing import LabelEncoder,OrdinalEncoder
     

pm=['Hot','Warm','Cold']
     

##TYPE YOUR CODE HERE
     

df['bo2']=e1.fit_transform(df[["ord_2"]])
     

df
     

df['ord_2']=e1.fit_transform(df[["ord_2"]])
     

df
     
LABEL ENCODER


le=LabelEncoder()
     

dfc=df.copy()
     

##TYPE YOUR CODE HERE
     
OneHotEncoder


from sklearn.preprocessing import OneHotEncoder
     

ohe=OneHotEncoder(sparse=False)
df2=df.copy()
     

#TYPE YOUR DATAFRAME CODE HERE
     

#TYPE YOUR CONCAT CODE HERE
     

pd.get_dummies(df2,columns=["nom_0"])
     
BinaryEncoder


pip install --upgrade category_encoders
     

from category_encoders import BinaryEncoder
     

df=pd.read_csv("/content/data.csv")
     

df
     

be=BinaryEncoder()
     

##TYPE YOUR CODE HERE
     
TargetEncoder


from category_encoders import TargetEncoder
     

te=TargetEncoder()
     

cc=df.copy()
     

##TYPE YOUR CODE HERE
     

#TYPE YOUR CONCAT CODE HERE
     
FEATURE TRANSFORMATION


import pandas as pd
from scipy import stats
import numpy as np
     

df=pd.read_csv("/content/Data_to_Transform.csv")
     

df.skew()
     

#Perform Log,Reciprocal,sqrt,dquare method one by one
     

#perfrom boxcox and yeojhonson method for any one column
     

import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
import scipy.stats as stats
     

sm.qqplot(df['Moderate Negative Skew'],line='45')
plt.show()
     

sm.qqplot(df['Moderate Negative Skew_1'],line='45')
plt.show()
     

df["Highly Negative Skew_1"]=qt.fit_transform(df[["Highly Negative Skew"]])
sm.qqplot(df['Highly Negative Skew'],line='45')
plt.show()
     

df
     

sm.qqplot(df['Highly Negative Skew_1'],line='45')
plt.show()
     
