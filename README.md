# DDoS Detection Using Machine Learning on CICIDS2019 SYN Flood Dataset

## Project Overview

This project implements a machine learning pipeline to detect SYN flood Distributed Denial of Service (DDoS) attacks using the CICIDS2019 dataset. It includes data loading, preprocessing, feature selection, and evaluation of classifiers like Logistic Regression, SVM, Random Forest, Decision Tree, and K-Nearest Neighbors to accurately identify SYN flood attack traffic.

## Dataset

The project uses the CICIDS2019 dataset, specifically the SYN flood attack traffic.

Important:
- The dataset is NOT included due to size and license restrictions.
- Only use the SYN flood attack data; do NOT use other attack types like UDP, ICMP, or HTTP flood.

Download the dataset from:
http://cicresearch.ca/CICDataset/CICDDoS2019/Dataset/PCAPs/03-11/


## Setup Instructions

1. Clone this repository:
   git clone https://github.com/abdelilahbajjou/ddos-detection.git
   cd ddos-detection

2. Install dependencies:
   pip install -r requirements.txt

3. Download the SYN flood dataset CSV file and place it in the data/ folder.

4. If needed, update the dataset path in ddos_detection.py:
   df = safe_load_data("data/Syn.csv")

## Running the Project

Run the main script:
python ddos_detection.py

This will preprocess data, select features, train classifiers, evaluate performance, and save logs and confusion matrices.

## Logging

Logs are saved with timestamps in the project directory, named like:
ddos_detection_YYYYMMDD_HHMMSS.log

## Notes

- The dataset is large; ensure you have enough system resources.
- Balancing and preprocessing steps are applied for best results.

## License

Specify your license here.

## Contact

For questions or suggestions, feel free to contact me.

Thank you for your interest!
