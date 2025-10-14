# dataset
https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package
medical_charges_url = 'https://raw.githubusercontent.com/JovianML/opendatasets/master/data/medical-charges.csv'
from urllib.request import urlretrieve
urlretrieve(medical_charges_url, 'medical.csv')
medical_df = pd.read_csv('medical.csv')