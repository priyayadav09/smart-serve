# 🧠 SmartServe – AI-Powered Food Waste Management System

SmartServe is an AI-powered platform built to help restaurants reduce food waste, manage inventory efficiently, and streamline surplus food donations. It combines machine learning, smart reminders, and an easy-to-use Streamlit interface to support chefs, managers, and restaurant staff.

---

## 🚀 Features

### *1. AI-Based Food Waste Prediction*

* Predicts possible waste based on patterns.
* Helps optimize daily food preparation.

### *2. Inventory & Expiry Tracking*

* Tracks items with purchase and expiry dates.
* Sends alerts before items spoil.

### *3. AI Chatbot & Expiry Alerts*

* Assists staff with queries on storage, shelf-life, usage tips.
* Works via text/voice.

### *4. Surplus Donation System*

* Recommends nearby NGOs.
* Shows contact details and donation suggestions.

### *5. Dashboard & Analytics*

* Displays waste trends.
* Shows top wasted items and prediction insights.

### *6. Streamlit UI*

* Lightweight and user-friendly.
* Works smoothly for hackathon-ready deployment.

---

## 🗂 Project Structure


SmartServe/
│── data/
│   ├── food_donation_data.json
│   ├── Food Waste data and research - by country.csv
│   └── inventory_expiry_tracking.csv
│
│── models/
│   └── waste_prediction_model.pkl
│
│── app/
│   ├── pages/
│   │   ├── 1_Inventory_Tracker.py
│   │   ├── 2_Waste_Prediction.py
│   │   ├── 3_Donation_System.py
│   │   └── 4_Chatbot.py
│   └── main.py
│
│── utils/
│   ├── prediction.py
│   ├── expiry_alerts.py
│   ├── donation_recommender.py
│   └── chatbot_logic.py
│
│── README.md
│── requirements.txt
└── streamlit_app.py


---

## 📦 Installation & Setup

### *1. Clone the repository*

bash
git clone https://github.com/yourusername/SmartServe.git
cd SmartServe


### *2. Install dependencies*

bash
pip install -r requirements.txt


### *3. Run the application*

bash
streamlit run streamlit_app.py


---

## 📊 Datasets Used

| Dataset                                       | Purpose                          |
| --------------------------------------------- | -------------------------------- |
| Food Waste data and research - by country.csv | ML training for waste prediction |
| inventory_expiry_tracking.csv                 | Tracks expiry and alerts         |
| food_donation_data.json                       | NGO mapping and donations        |

---

## 🤖 Tech Stack

* Python
* Streamlit
* Scikit-learn
* Pandas, NumPy
* Plotly/Matplotlib
* JSON/CSV datasets

---

## 💡 Future Improvements

* Mobile app version.
* POS system integration.
* Automated image-based waste detection.
* Smart supplier optimization.

---

## 🧑‍💻 Team

Developed by a 4-member team in 24 hours during a hackathon.

---

## 📜 License

This project is licensed under the MIT License.
