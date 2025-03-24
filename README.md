# Real Estate Price Prediction

This repository contains a complete machine learning workflow for predicting housing prices using various models. The dataset is filtered and preprocessed, then different regression models such as Linear Regression, Decision Tree, and Random Forest are trained and evaluated. The project is built using Python and several machine learning and data analysis libraries.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation Instructions](#installation-instructions)
  - [Setting Up the Virtual Environment](#setting-up-the-virtual-environment)
  - [Installing the Required Libraries](#installing-the-required-libraries)
- [Usage](#usage)
- [License](#license)

## Project Overview

This project leverages a dataset of housing prices, where different attributes like square footage, number of bedrooms, bathrooms, and location are used to predict the price of a house. The project involves:

- **Data Preprocessing**: Handling missing values, scaling data, and encoding categorical variables.
- **Exploratory Data Analysis (EDA)**: Visualizing the distribution of features and their relationships with the target variable.
- **Model Building**: Implementing and training multiple regression models (Linear Regression, Decision Tree, Random Forest).
- **Model Evaluation**: Evaluating the models using RMSE (Root Mean Squared Error) and visualizing the predictions versus the actual prices.

## Installation Instructions

Follow the instructions below to set up the environment for this project.

### Setting Up the Virtual Environment

To get started, you'll first need to set up a virtual environment. This isolates the project's dependencies from your global Python environment.

1. **Create the Virtual Environment**  
   In the project directory, run the following command to create a virtual environment:

   ```bash
   python -m venv venv
   ```

2. **Activate the Virtual Environment**  
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

   Your prompt should change to show that the virtual environment is active.

### Installing the Required Libraries

Once the virtual environment is activated, install the necessary dependencies for the project.

1. **Install the dependencies**  
   Run the following command to install all required libraries:

   ```bash
   pip install -r requirements.txt
   ```

   Alternatively, if you don’t have a `requirements.txt` file, you can manually install each package with `pip`. Here's a list of the required libraries:

   ```bash
   pip install asttokens certifi charset-normalizer colorama comm contourpy cycler debugpy decorator executing fonttools geographiclib geopy idna ipykernel ipython ipython_pygments_lexers jedi joblib jupyter_client jupyter_core kagglehub kiwisolver matplotlib matplotlib-inline nest-asyncio numpy packaging pandas parso pillow pip platformdirs prompt_toolkit psutil pure_eval Pygments pyparsing python-dateutil pytz pywin32 PyYAML pyzmq requests scikit-learn scipy seaborn setuptools six stack-data threadpoolctl tornado tqdm traitlets typing_extensions tzdata urllib3 wcwidth wheel
   ```

2. **Verify the installation**  
   After installation, you can check that everything was installed correctly by running:

   ```bash
   pip list
   ```

   This should display all the installed packages, including the ones listed above.

## Usage

1. **Clone the Repository**  
   First, clone this repository to your local machine:

   ```bash
   git clone https://github.com/jquelas/seattle_pricing_model.git
   cd seattle_pricing_model
   ```

2. **Run the Jupyter Notebook**  
   To begin exploring the project, open the Jupyter notebook in the `notebooks/` directory:

   ```bash
   jupyter notebook
   ```

   Open `price_prediction.ipynb` to start analyzing and predicting housing prices.

3. **Training Models**  
   The notebook demonstrates how to train multiple models such as:
   - **Linear Regression**
   - **Decision Tree Regressor**
   - **Random Forest Regressor**

   After training, each model's performance is evaluated using RMSE, and predictions are visualized.

4. **Model Evaluation**  
   The models are evaluated using **cross-validation** to ensure their robustness and to prevent overfitting. The results are displayed in the notebook, along with plots for predictions vs. actual prices.

## License

This project is licensed under the GNU V3 License - see the [LICENSE](LICENSE) file for details.

---