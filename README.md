# AI-Powered Network Anomaly Detection and Monitoring System

<img src="output.jpeg" alt="Network Anomaly Detection Dashboard" width="1000">

## Description

This project is an AI-powered network monitoring and anomaly detection system that identifies suspicious network traffic using the Isolation Forest machine learning algorithm. It combines real-time packet capture, anomaly detection, and interactive visualization to help monitor network activity efficiently.

---

## Features

* Real-time network packet monitoring
* Machine learning-based anomaly detection
* Detects anomalous network traffic patterns
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
## Dataset

The project includes a sample dataset (`network_data.csv`) for testing and demonstration purposes. It can also analyze live network traffic captured using Scapy.

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
├── output.jpeg             # Dashboard output
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
