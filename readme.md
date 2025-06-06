  
  # 🧠 Multiclass-Disease-Classification-for-ENT_Respiratoy_Neurological-Domains-

This project focuses on classifying diseases into specific medical domains using the BioBERT transformer model. It primarily targets **ENT (Ear, Nose & Throat)**, **Respiratory**, and **Neurological & Psychological** disorders based on patient symptom descriptions.

## 📚 Project Overview

We built a text classification model by finetuning **BioBERT (Bidirectional Encoder Representations from Transformers for Biomedical Text Mining)** on 30k samples to automatically categorize diseases from medical text inputs.

The model is trained on a custom dataset containing symptom descriptions and corresponding disease labels. The goal is to assist in intelligent healthcare diagnostics and specialist routing.

---

## 🧾 Disease Categories

The diseases are grouped under 3 medical domains:

1. **Ear, Nose & Throat (ENT)**  
   - Otitis media, Conjunctivitis, Stye, Eustachian tube dysfunction, etc.

2. **Respiratory Disorders**  
   - Asthma, Pneumonia, Bronchitis, Sleep Apnea, Common Cold, etc.

3. **Neurological & Psychological Disorders**  
   - Concussion, Depression, Personality disorder, Stress, Anxiety, etc.

(See `Disease_Domain_Catagories.txt` for full list)

---

## 📂 Files in this Repository

| File/Folder Name | Description |
|------------------|-------------|
| `disease_data.csv` | Raw dataset containing symptom text and disease labels |
| `391042_ENT_respiratory_neurological.csv` | Cleaned dataset containing symptom text and disease labels |
| `Disease_Domain_Catagories.txt` | List of diseases categorized under 3 domains |
| `*.ipynb` files | Jupyter notebooks for preprocessing, training, and evaluation of BioBERT model |

---

## 🛠️ Technologies Used

- Python
- BioBERT (HuggingFace Transformers)
- Pandas, NumPy
- Scikit-learn
- Google Colab (for training)

---

## 🚀 How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/kishorpatil87/Multiclass-Disease-Classification-for-ENT_Respiratoy_Neurological-Domains-.git
   cd kishorpatil87/Multiclass-Disease-Classification-for-ENT_Respiratoy_Neurological-Domains
Install dependencies
(Recommended to run in Google Colab or use Python 3.8+)

bash
Copy
Edit
pip install transformers pandas scikit-learn
Open Notebooks

Use the .ipynb notebooks to:

Load and preprocess the data

Tokenize with BioBERT tokenizer

Fine-tune the BioBERT model

Evaluate accuracy, precision, and F1-score

🧪 Model Output
The model achieves good performance on multiclass classification with three domains. Evaluation metrics include accuracy, confusion matrix, and F1-score (see final notebook for charts and details).

