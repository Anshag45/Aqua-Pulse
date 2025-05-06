## 🌊 AquaPulse

**AquaPulse** is a real-time water quality monitoring and forecasting dashboard that uses predictive analytics and anomaly detection to assess and visualize water quality trends across different regions.

![WhatsApp Image 2025-05-06 at 18 52 15_1441e545](https://github.com/user-attachments/assets/53d711a0-4ab3-4a05-b837-eeacf4f5d50b)


---

## 🚀 Features

- **Current Water Quality Index (WQI):** Real-time WQI displayed across monitored stations.
- **Predictive Analysis:** Future WQI trends powered by the ARIMA model.
- **Monitoring Coverage:** Displays active monitoring stations across 28 states.
- **Historical Trends:** Track yearly WQI changes from 2000–2022.
- **Anomaly Detection:** Instant alerts for high pollution or critical water quality changes.
- **Interactive Visualizations:** Integrated with Tableau for detailed analysis.
- **Quick Actions:** One-click upload, refresh, anomaly scan, and state predictions.

---

## 📊 Key Metrics

| Parameter         | Value         |
|-------------------|---------------|
| Dissolved Oxygen (DO) | 6.20 mg/l     |
| pH Level          | 7.40          |
| Biochemical Oxygen Demand (BOD) | 3.20 mg/l     |
| Conductivity      | 350.00 µS/cm  |
| Nitrates          | 22.00 mg/l    |
| Coliform          | 800 MPN/100ml |

---

## 📅 Data Details

- **Total Samples:** 3,254  
- **Data Range:** 2000 – 2022  
- **Model Used:** ARIMA v5.1.0  

---

## 🛠 Tech Stack

- **Frontend:** Custom UI with dark mode theme  
- **Backend:** Real-time data streaming APIs  
- **Modeling:** ARIMA-based prediction engine  
- **Visualization:** Tableau integration  

---

## 🔔 Recent Alerts

- 🔴 **Critical Alert:** High pollution in Yamuna – 2h ago  
- 🟠 **Warning:** Declining DO levels in Ganga – 6h ago  
- 🟢 **Info:** Model retraining completed – 1d ago  

---

## 📂 Project Structure
/aquaPulse
│
├── assets/ # Images and design assets
├── src/ # Source code
│ ├── components/ # UI components
│ ├── services/ # API and model integration
│ └── styles/ # Theming and CSS
├── tableau/ # Tableau dashboard files
├── data/ # Sample datasets
└── README.md


## ✅ How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/aquaPulse.git
   cd aquaPulse
Install dependencies

npm install
Run the application

npm start
Upload data via the dashboard or use Refresh Data for real-time updates.

📈 Future Enhancements
Mobile responsive version

Role-based access and user management

Integration with IoT water sensors

👨‍💻 Developed By Ansh Agarwal
📄 License: MIT
