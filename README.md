# titanic_sample
import numpy as np
import pandas as pd
url = "https://docs.google.com/spreadsheets/d/1BAluxxVI2koF_lh-6huTfvyEKX5pC0IC/edit?usp=sharing&ouid=112588145839588945747&rtpof=true&sd=true"
path = 'https://drive.google.com/uc?export=download&id='+url.split('/')[-2]
df_titanic= pd.read_excel(path,sheet_name='train')

df_titanic.head()
df_titanic.describe(include="all")
