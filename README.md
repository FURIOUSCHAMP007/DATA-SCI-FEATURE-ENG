
# 🧠 Feature Engineering & Vertex AI Feature Store Demos

This repository contains a collection of Jupyter notebooks demonstrating various techniques in feature engineering, model training, and integration with the Vertex AI Feature Store. It covers both basic and advanced workflows using BigQuery ML and Keras/TensorFlow models.

---

## 📁 Project Structure

| Notebook Filename                              | Description |
|-----------------------------------------------|-------------|
| `1_bqml_basic_feat_eng.ipynb`                 | Basic feature engineering using BigQuery ML |
| `2_bqml_adv_feat_eng.ipynb`                   | Advanced feature engineering with BigQuery SQL |
| `3_keras_basic_feat_eng.ipynb`                | Basic Keras regression model with engineered features |
| `4_keras_adv_feat_eng.ipynb`                  | Advanced Keras model with enhanced feature preprocessing |
| `5_tftransform_taxifare.ipynb`                | TensorFlow Transform preprocessing for taxi‐fare data |
| `6_gapic_feature_store.ipynb`                 | Vertex AI Feature Store access via GAPIC |
| `7_get_started_with_feature_store.ipynb`      | Intro to creating and using Vertex AI Feature Store |

---

## 🧰 Technologies Used

- **Jupyter Notebook**  
- **BigQuery ML**  
- **Keras / TensorFlow**  
- **TensorFlow Transform (TFX)**  
- **Google Cloud Platform (Vertex AI, BigQuery)**  
- **Vertex AI Feature Store**  
- **Python 3.x**

---

## 🚀 Getting Started

### Prerequisites

- Google Cloud SDK installed and configured  
- Vertex AI API enabled  
- BigQuery & Feature Store permissions  
- Python 3.x environment with required packages  

### Installation

```bash
# Clone the repo
git clone https://github.com/FURIOUSCHAMP007/feature-store-demos.git
cd feature-store-demos

# (Optional) Create virtual env
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
````

> Note: Some notebooks require Google Cloud access and service account credentials.

---

## 📊 Use Cases Demonstrated

* Feature extraction with SQL in BigQuery
* Model training via BigQuery ML and Keras
* Preprocessing pipelines using TensorFlow Transform
* Creating & managing entity types in Vertex AI Feature Store
* Feature ingestion, retrieval, and versioning

---

## 📌 Author

**Faizan Ahmed**
📬 [LinkedIn](https://www.linkedin.com/in/faizan-ahmed-74a935246/) | 🐙 [GitHub](https://github.com/FURIOUSCHAMP007)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

* [Google Cloud Vertex AI Documentation](https://cloud.google.com/vertex-ai/docs)
* [BigQuery ML Guide](https://cloud.google.com/bigquery-ml/docs)
* [TensorFlow Transform (TFX) Guide](https://www.tensorflow.org/tfx/transform/)


