# 🚖 Dynamic Pricing for Ride Sharing

**Dynamic Pricing for Ride Sharing** is a **Machine Learning project** built with Python and scikit-learn that predicts ride demand and adjusts prices in **real time** using factors like **traffic conditions, weather, and time of day**.  
The model is deployed as a **REST API**, enabling smooth integration with ride-sharing platforms for better **profitability** and **customer satisfaction**.

---

## ✨ Key Highlights
- 📊 **Demand Prediction** – Uses regression algorithms to forecast demand patterns.
- 🌦 **Context-Aware Pricing** – Considers traffic, weather, and time for accurate pricing.
- ⚡ **Real-time API** – Pricing engine accessible via REST endpoints.
- 💹 **Business Impact** – Balances profitability with fair pricing for users.

---

## 🛠️ Tech Stack
| Category           | Tools / Libraries                  |
|--------------------|------------------------------------|
| Language           | Python 3.x                         |
| ML Framework       | scikit-learn                       |
| Data Handling      | Pandas, NumPy                       |
| API Development    | Flask / FastAPI                     |
| Deployment Format  | REST API                            |

---


## 📂 Project Structure
├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks for EDA and model training
├── src/ # Source code for training and API
│ ├── train_model.py # Model training script
│ ├── predict.py # Prediction logic
│ ├── app.py # REST API endpoint
├── requirements.txt # Dependencies
├── README.md # Project documentation
└── model.pkl # Saved ML model
