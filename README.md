
# 🧠 Feature Engineering & Vertex AI Feature Store Demos

This repository contains a collection of Jupyter notebooks demonstrating various techniques in feature engineering, model training, and integration with the Vertex AI Feature Store. It covers both basic and advanced workflows using BigQuery ML and Keras/TensorFlow models.

---

## 📁 Project Structure

| Notebook Filename | Description |
|-------------------|-------------|
| `1_bqml_basic_feat_eng.ipynb` | Basic feature engineering using BigQuery ML |
| `2_bqml_adv_feat_eng.ipynb` | Advanced feature engineering with additional feature extraction using BigQuery SQL |
| `3_keras_basic_feat_eng.ipynb` | Basic Keras regression model with engineered features |
| `4_keras_adv_feat_eng.ipynb` | Advanced Keras model with enhanced feature set and preprocessing |
| `5_tftransform_taxifare.ipynb` | TensorFlow Transform (`tft`) for preprocessing taxi fare data |
| `6_gapic_feature_store.ipynb` | Vertex AI Feature Store access via GAPIC (Google Cloud API Client) |
| `7_get_started_with_feature_store.ipynb` | Introduction to creating and using Vertex AI Feature Store |

---

## 🧰 Technologies Used

- 🧪 **Jupyter Notebook**
- 🟡 **BigQuery ML**
- 🧠 **Keras / TensorFlow**
- 📦 **TensorFlow Transform (TFX)**
- ☁️ **Google Cloud Platform (Vertex AI, BigQuery)**
- 🔗 **Vertex AI Feature Store**
- 🐍 Python 3.x

---

## 🚀 Getting Started

### Prerequisites

- Google Cloud SDK installed and configured
- Vertex AI API enabled
- BigQuery and Feature Store permissions
- Python 3.x environment with required packages

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/feature-store-demos.git
cd feature-store-demos

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
````

> Note: Some notebooks require access to Google Cloud services and may need service account credentials configured.

---

## 📊 Use Cases Demonstrated

* Feature extraction with SQL in BigQuery
* Model training with BigQuery ML and Keras
* Transformation pipelines using TensorFlow Transform
* Creating and managing entities in Vertex AI Feature Store
* Feature ingestion, retrieval, and versioning

---

## 📌 Author

**Faizan Ahmed**
📬 [LinkedIn](https://www.linkedin.com/in/faizan-ahmed-74a935246/)) | 🐙 [GitHub](https://github.com/FURIOUSCHAMP007)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

* [Google Cloud Vertex AI Docs](https://cloud.google.com/vertex-ai/docs)
* [BigQuery ML Documentation](https://cloud.google.com/bigquery-ml/docs)
* [TensorFlow Transform Guide](https://www.tensorflow.org/tfx/transform/)

