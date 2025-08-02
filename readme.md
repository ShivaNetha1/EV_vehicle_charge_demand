# 🔮 EV Adoption Forecasting using Machine Learning

This project forecasts the future growth of Electric Vehicles (EVs) in Washington State using historical monthly registration data (2017–2024). It helps urban planners identify when and where to scale EV infrastructure like charging stations.

---

## 📌 Use Cases

🚗 **Urban Planning**: Anticipate regional EV demand to prevent charging bottlenecks  
📉 **Trend Analysis**: Understand EV growth patterns across counties  
🏛️ **Policy Support**: Data-driven planning for sustainable transport initiatives  
📊 **Public Dashboards**: Build visual tools for public awareness and decision-making  

---

## 🧰 Tech Stack

🧠 **ML Models**: Random Forest Regressor, Decision Tree Regressor  
📦 **Frameworks**: Scikit-learn, Pandas, NumPy  
📈 **Visualization**: Matplotlib, Seaborn  
🖥️ **Web App**: Streamlit  
🗂️ **Deployment**: Local or Streamlit Cloud  
📁 **Data Source**: Washington State EV registration data (Kaggle)

---

## ⚙️ Setup Instructions

### 1. ✅ Prerequisites

- Python 3.9+
- Git, pip
- VS Code or any code editor

### 2. 📦 Install Dependencies

```bash
git clone https://github.com/ShivaNetha1/EV_vehicle_charge_demand
cd EV_vehicle_charge_demand

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

pip install -r requirements.txt
```

---

## 3. 🚀 Run the App

```bash
streamlit run app.py
```

This launches the interactive web app in your browser.

---

## 📷 Screenshot  
### 🔍 Main User Interface of the EV Forecasting App (Streamlit)
![Working Screenshot](Screenshots\Deployed.jpg)
- - - 
### 🔍 3-Year Forecast for a Single County
![Working Screenshot](Screenshots\running.jpg)
![ss](Screenshots\image.jpg)
- - -
### 🔍 Comparison of EV Adoption Trends for Three Counties
![Working Screenshot](Screenshots\s.jpg)
![Working Screenshot](Screenshots\r2.jpg)

<!-- <sub><i>EV adoption in <strong>Los Angeles County</strong> is expected to show an <strong>increase of 57.49%</strong> over the next 3 years.</i></sub> -->

---

## 🧠 Machine Learning Workflow

- **Data Preprocessing**: Handled missing values, formatted dates, and removed outliers  
- **Feature Creation**: Created lag values, rolling means, percentage changes, and growth slope  
- **Model Training**: Used **Random Forest Regressor** and tested with **Decision Tree Regressor**  
- **Model Evaluation**: Assessed using **MAE**, **MSE**, and **R² Score**  
- **Deployment**: Built and deployed using **Streamlit** for interactive user access

---

## 🗂️ File Structure

```
.
├── app.py                         # Streamlit frontend
├── EV_Adoption_Forecasting.ipynb # Model training & EDA notebook
├── preprocessed_ev_data.csv      # Feature-enriched dataset
├── Electric_Vehicle_Population_By_County.csv  # Raw dataset
├── forecasting_ev_model.pkl      # Trained model file
├── ev-car-factory.jpg            # UI image
├── requirements.txt              # Project dependencies
└── .gitignore                    # Ignored files
```

---

## 🚀 Future Scope

- Integrate real-time EV registration APIs  
- Add external features (fuel prices, population, incentives)  
- Expand analysis to other U.S. states  
- Deploy on Streamlit Cloud or Hugging Face Spaces  
- Enable CSV upload for new data forecasting

---

## 🔗 Connect & Explore More

📁 GitHub Repo: [github.com/ShivaNetha1/EV_vehicle_charge_demand](https://github.com/ShivaNetha1/EV_vehicle_charge_demand)  
💼 LinkedIn: [linkedin.com/in/shivanetha](https://www.linkedin.com/in/shiva-pandala-243914229/)

---

## 📄 License

This project is licensed under the **MIT License**.
