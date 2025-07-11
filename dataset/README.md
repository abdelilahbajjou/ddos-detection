# 📁 Dataset Information

This folder does **not** contain the dataset files due to their large size and license restrictions.

## 🔗 Dataset Source

This project uses the **CIC DDoS 2019 dataset**, specifically the **SYN flood attack data** found in:

[http://cicresearch.ca/CICDataset/CICDDoS2019/Dataset/PCAPs/03-11/](http://cicresearch.ca/CICDataset/CICDDoS2019/Dataset/PCAPs/03-11/)

---

## 📌 Important Instructions

- ⚠️ **Please download only the SYN flood attack dataset from the above URL.**

- ❌ Do **NOT** use other attack types such as UDP, ICMP, or HTTP flood for this project.

---

## 📂 After Downloading

1. Place the downloaded SYN dataset file(s) inside this `data/` folder.

2. In your script, update the path accordingly, for example:

```python
df = safe_load_data("data/syn_dataset_filename.csv")
