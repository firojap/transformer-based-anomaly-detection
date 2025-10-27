# Explaining Manufacturing Anomalies: Transformer-Based Detection with xAI for Imbalanced Process Data
#### An anomaly detection classification approach based on Transformer-based encoder techniques
---

## Transformer-based Anomaly Detection
This is the repository of the project abd paper entitled 'Explaining Manufacturing Anomalies: Transformer-Based Detection with xAI for Imbalanced Process Data'

---
## Project Structure

```
anomaly_detection/
│
├── data/
│   ├── station1.csv
│   ├── station2.csv
│   ├── station4.csv
│   └── station5.csv
│
├── data_preprocessing/
│   ├── preprocess_feature_extraction.ipynb
│
├── model/
│   ├── modeling_anomaly_detection.ipynb
│
├── Figures/
│   └── (figures and plots generated from analyses)
│
└── README.md

```
---

### Folder Description
- **Data Preprocessing:** Contains all the notebooks and codes to preprocess the data for models implementation. It also included Extract, Transform, and Load (ETL) for entire data engineering of the project.
- **Data:** This folder contains the all stations data that have used in this project. 
- **Figures:** Contains all visualization plot, figures of the project.
- **Model:** Contains the notebook of Transformer encoder model.
---

### Workflow of the Project:
![Workflow](https://github.com/firojap/transformer-based-anomaly-detection/blob/master/Figures/flow_.png)

__Figure:__ *SHAP summary plot for the BiLSTM model. Red dots represent the high values of each feature and blue dots represent the low values of each feature. The y-axis lists the features in order of their importance, with the most significant feature at the top. The x-axis represents the SHAP values, which indicate the magnitude and direction of each feature’s impact on the model’s output.*

---

### Contributed Features to Anomaly:
![Bar Diagram](https://github.com/firojap/transformer-based-anomaly-detection/blob/master/Figures/lime3f.png)

__Figure:__ *SHAP summary plot for the BiLSTM model. Red dots represent the high values of each feature and blue dots represent the low values of each feature. The y-axis lists the features in order of their importance, with the most significant feature at the top. The x-axis represents the SHAP values, which indicate the magnitude and direction of each feature’s impact on the model’s output.*

---

### ROC Curve:
![ROC Curve](https://github.com/firojap/transformer-based-anomaly-detection/blob/master/Figures/roc_.PNG)

__Figure:__ *SHAP summary plot for the BiLSTM model. Red dots represent the high values of each feature and blue dots represent the low values of each feature. The y-axis lists the features in order of their importance, with the most significant feature at the top. The x-axis represents the SHAP values, which indicate the magnitude and direction of each feature’s impact on the model’s output.*

---

### Final Manuscript:
The final manuscript of the project paper can be download and view from [here](https://www.sciencedirect.com/science/article/pii/S2405896325010134).

---

### Citation:
If you use or refer to this work, please cite it as follows:

---

#### 🔹 APA Citation
```
Al Noman, A., Zitnikov, A., Patwary, F. A., Heuermann, A., & Thoben, K. D. (2025). Explaining Manufacturing Anomalies: Transformer-Based Detection with xAI for Imbalanced Process Data. IFAC-PapersOnLine, 59(10), 1498-1503.
```
---
#### 🔹 MLA Citation
```
Al Noman, Abdullah, et al. "Explaining Manufacturing Anomalies: Transformer-Based Detection with xAI for Imbalanced Process Data." IFAC-PapersOnLine 59.10 (2025): 1498-1503.
```
---
#### 🔹 BibTeX Citation
```bibtex
@article{al2025explaining,
  title={Explaining Manufacturing Anomalies: Transformer-Based Detection with xAI for Imbalanced Process Data},
  author={Al Noman, Abdullah and Zitnikov, Anton and Patwary, Firoj Ahmmed and Heuermann, Aaron and Thoben, Klaus-Dieter},
  journal={IFAC-PapersOnLine},
  volume={59},
  number={10},
  pages={1498--1503},
  year={2025},
  publisher={Elsevier}
}
---

