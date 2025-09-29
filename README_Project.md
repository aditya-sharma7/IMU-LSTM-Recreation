# IMU-LSTM Pipeline: Human Activity Recognition & Payload Estimation  

This repository contains Jupyter notebooks implementing an **LSTM-based deep learning pipeline** for Human Activity Recognition (HAR) and Payload Estimation using **Inertial Measurement Unit (IMU) sensor data**.  

The project includes preprocessing, reproducibility setup, and training pipelines to classify human activities and estimate carried payloads from IMU signals.  

---

## 📂 Files  

- `IMU_LSTM_pipeline.ipynb` – Main pipeline for HAR & payload estimation.  
- `IMU_LSTM_pipeline_(1).ipynb` – Alternate/backup version of the pipeline (Colab-ready).  

---

## 🚀 Features  

- **Colab Integration** – Pre-configured with Google Colab badges for quick execution.  
- **Reproducibility** – Seeds and configurations for consistent results.  
- **Data Handling** – Automated detection of label columns in IMU datasets.  
- **Modeling** – LSTM-based architecture using TensorFlow/Keras.  
- **Evaluation** – Supports activity recognition and payload classification tasks.  

---

## 🛠️ Requirements  

Install dependencies via pip:  

```bash
pip install scikit-learn scipy nbformat tensorflow
```

Additional requirements (depending on dataset handling and visualization):  

```bash
pip install pandas numpy matplotlib seaborn
```

---

## 📊 Workflow  

1. **Setup & Dependencies**  
   - Colab and local support with Google Drive integration.  

2. **Preprocessing**  
   - Load IMU dataset.  
   - Detect label columns.  
   - Normalize and segment signals.  

3. **Model Architecture**  
   - LSTM-based deep neural network.  
   - Configurable number of layers and units.  

4. **Training & Evaluation**  
   - Activity classification.  
   - Payload estimation (regression/classification).  

---

## ▶️ Usage  

Run the pipeline on **Google Colab**:  

- [Open IMU_LSTM_pipeline.ipynb in Colab](https://colab.research.google.com/drive/1FbF6zwGi1JU5oIqyjeS6t1ST-oLjCy2u?usp=sharing)  
- [Open IMU_LSTM_pipeline_(1).ipynb in Colab](https://colab.research.google.com/drive/193DoXT6MnmaDdzE8uRz8pwyVs7BCrpxp?usp=sharing)  


## 📌 Notes  

- Ensure IMU dataset is uploaded or mounted via Google Drive in Colab.  
- Adjust sampling frequency (`FS = 100`) and window sizes as per dataset.  
- Both notebooks are similar; one may serve as a backup or experimental version.  
