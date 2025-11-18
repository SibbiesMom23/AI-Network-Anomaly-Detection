# AI-Based Network Anomaly Detection
This project uses machine learning to identify potential anomalies in network traffic that may reflect cyber threats such as scanning, unusual data flows, or suspicious packet patterns. It demonstrates how AI/ML can support cybersecurity operations, especially in environments where large volumes of telemetry must be analyzed rapidly.

## Features
- Random Forest machine learning classifier
- Synthetic network dataset (or replace with real PCAP-derived dataset)
- Data preprocessing using Pandas
- Model training, testing, and accuracy evaluation
- Confusion matrix and classification report
- Clean, readable Jupyter Notebook

## Technologies
- Python
- scikit-learn
- Pandas
- NumPy
- Matplotlib

## How It Works
1. Load and preprocess network activity data  
2. Train a Random Forest classifier  
3. Predict whether traffic is normal or anomalous  
4. Evaluate accuracy and performance metrics  
5. Visualize results  

## Future Enhancements
- Integrate real PCAP → CSV extraction
- Try unsupervised anomaly detection (Isolation Forest)
- Add basic OT/ICS-specific features
- Use neural networks for deeper detection

## Author
**Stacie A. Smith**  
Graduate Cybersecurity Student
