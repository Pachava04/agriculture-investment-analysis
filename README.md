# 🌱 Optimizing Investments on Agricultural Land
project analyzing farmland investment using crop yield, soil characteristics, and market data.

# 🔍 Overview

This project analyzes agricultural land data to help investors and farmers make data-driven decisions on crop selection and land investment.
We used exploratory data analysis (EDA), predictive modeling, and geospatial analytics to uncover actionable insights on soil quality, yield patterns, and profitability.

Our study focuses on answering 4 key problem-solving questions:

1️⃣ What effects do soil characteristics have on the yield of crops in various geographical areas? 

2️⃣ Over the last ten years, which states and counties have produced the best yields of various crop types?

3️⃣ Which factors affect rising or falling yields, and how have patterns in agricultural yields altered over time?

4️⃣ How can we best choose crops and make investments in various farming sites to achieve maximum profitability?

# 🗂️ Dataset & Sources

We combined multiple datasets to build a robust analytical model:

•	USDA National Agricultural Statistics Service (NASS) – Quick Stats: Crop yields by county over 10+ years

•	USDA Soil Data: Soil composition, nutrient levels, pH, and moisture capacity

•	Market Prices & Land Values: Historical commodity and farmland prices

•	Geospatial Data: Used GeoPandas and Folium for mapping insights

# 🔬 Approach & Methodology

This project followed a data science workflow:

	1.	Data Cleaning & Preprocessing – Handling missing values, standardizing metrics, and feature engineering
	2.	Exploratory Data Analysis (EDA) – Trend analysis, geospatial mapping, and correlation studies
	3.	Model Building & Selection:
	  •	Tested Linear Regression, Random Forest, and XGBoost for yield prediction
	  •	Selected XGBoost for its superior accuracy and ability to capture nonlinear relationships
	4.	Validation & Evaluation:
	  •	Metrics: RMSE, R² Score, Feature Importance
	5.	Recommendation Engine:
	  •	Provides state/county-level profitability rankings
	  •	Suggests best crop choices per region

# 🏆 Key Findings & Insights
	•	🌾 Soil pH and Organic Matter are top predictors of crop yield
	•	🗺️ Top-yielding regions for crops like corn and soybeans are concentrated in the Midwest
	•	📈 Climate shifts and commodity price trends significantly influence long-term profitability
	•	💡 Our model enables data-driven investment strategies for sustainable farming

# 📊 Final Deliverables
	•	✅ Interactive Tableau Dashboard – For visual exploration of crop yield trends and profitability
	•	✅ Python-based ML Pipeline – For predictive modeling and recommendation generation
	•	✅ Geospatial Heatmaps – Visualizing best crop-land combinations
	•	✅ Technical Documentation – For reproducibility and scalability

# 🛠️ Tech Stack
	•	Languages: Python, SQL
	•	Libraries: Pandas, NumPy, Scikit-learn, XGBoost, GeoPandas, Folium, Matplotlib, Seaborn
	•	Visualization: Tableau, Plotly
	•	Workflow: Jupyter Notebooks, GitHub, VSCode

# Project Impact  

This project demonstrates end-to-end data analytics skills, from data wrangling to ML model deployment.
Recruiters and collaborators can quickly see:
  
  •	🔹 Strong analytical reasoning
  •	🔹 Model comparison and justification
  •	🔹 Actionable insights from real-world agricultural data

# 📁 Repository Structure

├── data/                # Raw and cleaned datasets  
├── notebooks/           # Jupyter notebooks for EDA & modeling  
├── scripts/             # Python scripts for ML pipeline  
├── visuals/             # Charts and geospatial maps  
└── README.md            # Project overview  

# 👤 Author

Goutham

Data Analyst | Machine Learning Enthusiast

📫 LinkedIn | Portfolio
