# MediFlow – Real-Time Patient Health Monitoring System 🚑

**MediFlow** is a **Real-Time Health Monitoring System** developed during my internship at **GB Tech Corp**.
The system is designed to help **doctors, clients, and patients** monitor **live vitals data** through an interactive web interface and dashboard.

---

## 🩺 **Project Overview**

MediFlow collects and monitors the following patient health parameters:

* **Blood Oxygen Level (SpO2)**
* **Body Temperature**
* **Heart Rate**

The system is designed for **real-time monitoring** to help medical professionals make quick and informed decisions. Users can track patient health directly via the web interface or through detailed dashboards.

---

## 📊 **Dashboard Overview**

Here's a snapshot of the **Power BI Dashboard** I created to visualize the real-time vitals and risk categories:

![MediFlow Dashboard](./Screenshot%202025-07-13%20201334.png)

### **Dashboard Features:**

* **Min of Heart Rate by Risk Category**
* **Oxygen Saturation Levels by Temperature Category**
* **Body Temperature Distribution by Risk**
* **Monthly Patient Count Tracking**
* **Combined Heart Rate and Oxygen Saturation Report**

This dashboard helps health professionals quickly interpret large amounts of patient data in a simple and visually appealing way.

---

## ⚙️ **Features**

* **Live Vitals Monitoring** (Heart Rate, SpO2, Temperature)
* **Risk Level Classification using Machine Learning (XGBoost)**
* **Real-time Dashboard Visualization with Power BI**
* **Web Interface for Professionals and Clients**
* **Interactive User Experience for Non-Technical Users**

---

## 🧰 **Tech Stack**

| Task                        | Tools Used            |
| --------------------------- | --------------------- |
| **Data Collection**         | Kaggle                |
| **Data Processing**         | Python, Pandas, NumPy |
| **Model Training**          | XGBoost, Scikit-learn |
| **Visualization**           | Power BI, Matplotlib  |
| **Web Interface**           | Flask, HTML, CSS, JS  |
| **Development Environment** | Jupyter Notebook      |

---

## 🚀 **Workflow**

### 1️⃣ **Data Collection & Cleaning**

* Collected patient vitals from Kaggle.
* Cleaned and preprocessed data in **Jupyter Notebook**.

### 2️⃣ **Model Building**

* Built and trained an **XGBoost model** to classify patient risk levels.
* Achieved **\~70% accuracy** in predicting health risks.

### 3️⃣ **Web Integration**

* Developed a **Flask API** to connect the backend model to the frontend.
* Designed an **interactive web page** for live monitoring.

### 4️⃣ **Dashboard Creation**

* Created a **Power BI dashboard** for deeper analysis and visual reporting.

---

## 💻 **How to Run Locally**

```bash
# Clone the repo
git clone https://github.com/yourusername/MediFlow.git

# Navigate to the directory
cd MediFlow

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py

# Visit the web interface
http://127.0.0.1:5000/
```

---


## 📈 **Project Results**

* Successfully monitored **200K+ patient records**
* Achieved **70% accuracy** in health risk prediction
* Visualized data using **Power BI** for easy interpretation

---

## 📬 **Contact**

If you'd like to collaborate or know more, feel free to connect:

**Lavanya R**
[LinkedIn](https://www.linkedin.com/in/lavanya-r-479537274/)

---

## ⭐ **Acknowledgment**

Special thanks to **GB Tech Corp** for giving me the opportunity to work on real-time healthcare analytics during my internship.

---

### **Folder Structure Suggestion**

```
MediFlow/
│
├── app.py                 # Flask Web App
├── model/                  # Saved ML models
├── static/                 # CSS/JS files
├── templates/              # HTML files
├── dataset/                # Raw & cleaned datasets
├── powerbi_dashboard/      # Power BI files/screenshots
└── README.md               # Project documentation
```


