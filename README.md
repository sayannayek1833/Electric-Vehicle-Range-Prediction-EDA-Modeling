Electric Vehicle Range Prediction – EDA & Modeling 🚗⚡
Project Overview
This project focuses on predicting the range of electric vehicles (EVs) based on various attributes such as model year, vehicle type, manufacturer, and base MSRP. By leveraging exploratory data analysis (EDA) and machine learning models, we aim to gain insights into key factors influencing EV range and develop an accurate prediction model.

Key Objectives
✅ Perform EDA to understand dataset characteristics and identify correlations
✅ Clean and preprocess data, handling missing values and encoding categorical features
✅ Train predictive models (e.g., XGBoost) for accurate range estimation
✅ Visualize trends and key relationships through various plots and charts
✅ Evaluate model performance using statistical metrics

Dataset Information
The dataset is sourced from [mention source, e.g., Washington State Department of Licensing] and includes information on:

Make & Model – The brand and specific EV model

Model Year – The year of manufacture

Electric Vehicle Type – BEV (Battery Electric Vehicle) or PHEV (Plug-in Hybrid)

Electric Range – The estimated range in miles

Base MSRP – Manufacturer’s suggested retail price

Geographical Data – County, postal code, and legislative district

Project Structure
bash
Copy
Edit
📂 EV_Range_Prediction
│── 📁 data               # Raw and processed datasets  
│── 📁 notebooks          # Jupyter notebooks for analysis  
│── 📁 models             # Trained models  
│── 📁 visualizations     # Plots and charts  
│── README.md             # Project overview (this file)  
│── requirements.txt      # Dependencies  
│── EV_Range_Prediction.ipynb  # Main notebook  
Exploratory Data Analysis (EDA)
EDA is conducted to gain insights into data patterns and relationships:
📌 Feature Distribution – Histograms and boxplots for understanding data spread
📌 Correlation Analysis – Heatmaps to identify key influencing factors
📌 Outlier Detection – Handling extreme values using IQR
📌 Trend Analysis – Studying EV range variations over model years

Modeling & Evaluation
The project implements XGBoost for range prediction. The model is evaluated using:
✔ Mean Absolute Error (MAE)
✔ Root Mean Squared Error (RMSE)
✔ R-squared (R²) Score

Key Insights
📊 Newer EV models tend to have longer ranges
📊 Certain manufacturers produce more efficient EVs
📊 Base MSRP moderately correlates with EV range
📊 BEVs generally have a higher range than PHEVs

Installation & Usage
1️⃣ Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/EV_Range_Prediction.git
cd EV_Range_Prediction
2️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Jupyter Notebook to explore the analysis and results.

Future Enhancements
🚀 Deep learning-based range prediction
🚀 Integration with real-time EV data
🚀 Deployment as a web app for live predictions

📌 Feel free to fork, contribute, or reach out for collaboration! 🚀







