# AI-Powered Network Anomaly Detection and Monitoring System

## Description

This project is an AI-powered network monitoring system that detects abnormal network traffic patterns using machine learning techniques. It combines real-time packet monitoring, anomaly detection, and interactive visualization to identify suspicious network activities.

---

## Features

* Real-time network packet monitoring
* Machine learning-based anomaly detection
* Detection of abnormal traffic patterns
* Interactive Streamlit dashboard
* Traffic visualization using Plotly
* Risk level classification
* Live packet capturing using Scapy
* Modular Python implementation
* Sample dataset for testing

---

## Technologies Used

* Python
* Machine Learning
* Isolation Forest Algorithm
* Scikit-learn
* Pandas
* NumPy
* Streamlit
* Scapy
* Plotly

---

## Project Structure

```
AI-Network-Anomaly-Detector/
│
├── app.py                 # Streamlit dashboard
├── model.py               # Isolation Forest model
├── live_capture.py        # Live packet capture
├── network_data.csv       # Sample dataset
├── requirements.txt
├── output.png             # Dashboard output
├── README.md
└── LICENSE
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/Mugila-B/AI-Network-Anomaly-Detector.git
```

2. Navigate to the project

```bash
cd AI-Network-Anomaly-Detector
```

3. Install the required packages

```bash
pip install -r requirements.txt
```

4. Run the Streamlit application

```bash
streamlit run app.py
```

---

## Working Principle

1. Captures live network traffic using Scapy or loads sample network data.
2. Extracts network features such as packet count and traffic statistics.
3. Trains and applies the Isolation Forest algorithm to learn normal network behavior.
4. Detects abnormal traffic patterns and classifies them as anomalies.
5. Displays the results through an interactive Streamlit dashboard with visual charts.

---

## Output

### Network Anomaly Detection Dashboard

<img width="1917" height="967" alt="image" src="https://github.com/user-attachments/assets/f8206a85-a4ab-4a3a-8b37-8eaf3788e396" />


---

## Applications

* Network Security Monitoring
* Intrusion Detection Systems (IDS)
* Cybersecurity Analysis
* Traffic Behavior Monitoring
* Threat Detection and Prevention
* Educational Machine Learning Projects

---

## Future Enhancements

* Deep Learning-based anomaly detection
* Email and SMS alert notifications
* Database integration
* Cloud deployment
* Advanced threat classification
* Real-time logging and reporting

---

## Author

**Mugila**

B.Tech Artificial Intelligence and Data Science

---

## License

This project is licensed under the MIT License.
