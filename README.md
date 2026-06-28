# AI Network Anomaly Detector

## About the Project
This project is a network monitoring and anomaly detection system built using Python. It captures network traffic, checks request patterns, and finds unusual activities using the Isolation Forest algorithm.

The project also provides a dashboard using Streamlit to monitor live traffic, view analysis graphs, and detect suspicious activities.

## Features
- Live network traffic monitoring
- Packet capturing using Scapy
- Detection of abnormal traffic patterns
- Risk level classification
- Traffic analysis graphs
- Threat alerts
- Downloadable reports

## Technologies Used
- Python
- Streamlit
- Pandas
- Scikit-learn
- Plotly
- Scapy

## Project Files
- `app.py` – Main Streamlit dashboard
- `model.py` – Detection model logic
- `live_capture.py` – Captures live packets
- `network_data.csv` – Sample traffic dataset

## How It Works
1. Captures live network packets or loads sample data.
2. Extracts request count and data size.
3. Applies Isolation Forest for anomaly detection.
4. Labels traffic as normal or anomaly.
5. Displays results in the dashboard and charts.

## Dataset
The project includes a sample dataset (`network_data.csv`) for testing when live traffic is not available.

## Installation

Clone the repository and run the project:

```bash
git clone https://github.com/yourusername/AI-Network-Anomaly-Detector.git
cd AI-Network-Anomaly-Detector
pip install -r requirements.txt
streamlit run app.py
```

## Future Improvements
- Better threat classification
- Email alert system
- Database integration
- Cloud deployment

## Author
Mugi  
B.Tech Artificial Intelligence and Data Science

## License
This project is licensed under the MIT License.
