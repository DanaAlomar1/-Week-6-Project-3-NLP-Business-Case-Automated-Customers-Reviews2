
# 📘 README.md

## 🧠 Project Overview
This project includes three main components of a Natural Language Processing (NLP) pipeline using different techniques: **Text Classification**, **Summarization**, and **Clustering**. Each notebook tackles a specific NLP task using Hugging Face Transformers and other modern libraries.

---

## 📁 Files Included

### 1. `classification TRUE.ipynb`
🔹 **Task**: Text Classification  
🔹 **Description**:  
- Loads and preprocesses labeled review data  
- Trains a transformer-based classification model  
- Evaluates performance using standard metrics (accuracy, precision, etc.)  
🔹 **Model Used**: Pretrained BERT-like model from Hugging Face  
🔹 **Input**: Reviews + Ratings  
🔹 **Output**: Predicted sentiment or category  

### 2. `NLP(summrazition).ipynb`
🔹 **Task**: Text Summarization  
🔹 **Description**:  
- Loads product reviews  
- Filters them by category  
- Uses BART summarization pipeline to generate short summaries  
🔹 **Model Used**: `facebook/bart-large-cnn`  
🔹 **Input**: Raw review text  
🔹 **Output**: Concise summary of reviews  

### 3. `Clustring.ipynb`
🔹 **Task**: Clustering / Topic Discovery  
🔹 **Description**:  
- Applies vectorization on textual data  
- Performs clustering using KMeans or Hierarchical clustering  
- Evaluates clusters with Silhouette Score  
🔹 **Input**: Text data  
🔹 **Output**: Grouped topics or document clusters  

---

## 🛠️ Requirements

- Python 3.8+
- `transformers`
- `sklearn`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`
- `gradio` 

---

## 🚀 How to Run

1. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
2. Open JupyterLab or Jupyter Notebook:
   ```bash
   jupyter lab
   ```
3. Run notebooks in order or independently based on the task:
   - `classification TRUE.ipynb`
   - `NLP(summrazition).ipynb`
   - `CTD.ipynb`
