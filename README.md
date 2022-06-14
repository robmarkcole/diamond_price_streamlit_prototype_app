# Diamond Price Predictor App using Streamlit #
## By: Nate DiRenzo ##

### Statement of Purpose ###
The purpose of this repository is as a tutorial for creating a regression model that predicts the price of a diamond, and building a simple frontend application to make the model publicly available using Streamlit. [Medium article](https://medium.com/towards-data-science/deploying-ml-models-using-streamlit-5d6212453bdd)

### Data Description ###
The data we will be using for this project is the [Diamonds](https://www.kaggle.com/datasets/shivam2503/diamonds) dataset, which is publicly available via Kaggle. It contains 53940 observations, and 10 features in the dataset.

### Tools ###
- **Pandas** for accessing the data, and preparing the it for modeling.
- **XGBoost** for creating a gradient-boosted regression model.
- **Streamlit** for creating a frontend application

## Development
Currently only the helper functions are tested, using pytest.
* `python3 -m venv venv`
* `source venv/bin/activate`
* `pip install -r requirements.txt`
* `pip install streamlit`
* `streamlit run app`