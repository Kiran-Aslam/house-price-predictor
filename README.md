# California House Price Prediction Web App

A machine learning web application to predict house prices based on the California Housing Dataset using **Linear Regression** and **Random Forest** models. Developed in **Google Colab** with data preprocessing, model training, and an interactive **Gradio** GUI for predictions and exploratory data analysis.

---

## Project Highlights

- Predict median house prices in California  
- Compare performance of two models:  
  - **Linear Regression** – R² Score: 0.58  
  - **Random Forest Regressor** – R² Score: 0.81  
- Interactive data visualizations including:  
  - Exploratory Data Analysis (EDA) plots  
  - Actual vs. Predicted prices  
  - Residual (error) distribution plots  
- Clean and intuitive Gradio-based GUI for real-time user interaction  
- Models trained and saved using `joblib`  

---

## Features

- Real-time price prediction using user inputs:  
  - Median Income, House Age, Average Rooms, Average Bedrooms, Population, Average Occupants, Latitude, Longitude  
- Visual insights via:  
  - Distribution plots of house prices  
  - Correlation heatmaps of features  
  - Actual vs. Predicted price scatterplots  
  - Residuals (errors) histogram  

---

## Tech Stack

- Python (NumPy, Pandas, Scikit-learn)  
- Gradio (for GUI)  
- Matplotlib & Seaborn (for visualizations)  
- Google Colab (development environment)  
- ChatGPT (for coding assistance and idea generation)  

---

## How to Use

1. Clone this repository  
2. Open the notebooks in Google Colab or Jupyter  
3. Run the cells to train/load models and launch the Gradio interface  
4. Input housing features to get real-time price predictions  
5. Explore the EDA tab for interactive visualizations  

---

## Acknowledgements

Thanks to the California Housing Dataset and open-source libraries that made this project possible.

