# 👗 Sales Forecasting for Clothing Sector using ARIMA & LSTM

📈 A complete end-to-end Data Science project that forecasts sales in the clothing industry using traditional statistical models (ARIMA) and advanced deep learning models (LSTM), deployed via an interactive Flask dashboard.

---

## 🚀 Project Highlights

- 📅 **Time-Series Sales Forecasting**
- 🤖 **ARIMA** for traditional time series forecasting
- 🧠 **LSTM (Deep Learning)** for sequence modeling
- 📊 Clean and intuitive **Dashboard** with historical and future projections
- 📁 Modular & professional **project structure** for scalability
- 🧪 Built with **Python, Pandas, Keras, Flask, Matplotlib**

---

## 📂 Project Structure

sales-forecasting-clothing-sector/
│
├── 📁 data/ # Raw and cleaned data
│ ├── raw_sales_data.csv
│ └── cleaned_sales_data.csv
│
├── 📁 notebooks/ # Jupyter Notebooks for development
│ ├── 01_data_cleaning.ipynb
│ ├── 02_exploratory_data_analysis.ipynb
│ ├── 03_feature_engineering.ipynb
│ ├── 04_model_building_ARIMA.ipynb
│ ├── 05_model_building_LSTM.ipynb
│ └── 06_dashboard_design.ipynb
│
├── 📁 models/ # Trained models and scalers
│ └── best_model.pkl
│
├── 📁 app/ # Flask app folder
│ ├── app.py
│ ├── templates/
│ │ └── index.html
│ └── static/
│ └── style.css
│
├── 📁 reports/ # Project report
│ └── final_report.pdf
│
├── 📁 images/ # Visuals used in reports/dashboards
│ └── visualizations.png
│
├── .gitignore
├── README.md
├── requirements.txt
└── LICENSE

## 📊 Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| `Pandas` | Data manipulation |
| `Matplotlib` | Visualization |
| `Flask` | Web application |
| `Keras` + `TensorFlow` | LSTM modeling |
| `statsmodels` | ARIMA modeling |
| `joblib` | Model serialization |

---

## 🔍 Features

- ✔️ Cleaned raw transactional data for clothing sector
- ✔️ Performed EDA to discover seasonal trends
- ✔️ Built ARIMA model for quick forecasting
- ✔️ Built LSTM model for capturing long-term patterns
- ✔️ Downloadable forecast results
- ✔️ Flask-based UI with Matplotlib visualizations

---

## 🧪 How to Run

```bash
# Clone the repo
git clone https://github.com/your_username/sales-forecasting-clothing-sector.git
cd sales-forecasting-clothing-sector

# Set up virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate  # Mac/Linux

# Install requirements
pip install -r requirements.txt

# Run the app
cd app
python app.py
