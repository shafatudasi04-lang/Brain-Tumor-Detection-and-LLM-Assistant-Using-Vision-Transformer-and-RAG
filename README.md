# 🧠 Brain Tumor Detection and LLM Assistant

## Project Overview

This project combines Computer Vision and Large Language Models (LLMs) to develop an educational Brain Tumor AI Assistant.

It consists of two major components:

1. **Brain Tumor Classification:** Uses a pretrained Vision Transformer (ViT) to classify brain MRI images into four categories.
2. **LLM-Based Educational Assistant:** Uses Retrieval-Augmented Generation (RAG) to answer educational questions about brain tumors using a knowledge base.

## Technologies Used

- Python
- PyTorch
- Vision Transformer (ViT)
- Hugging Face Transformers
- Google FLAN-T5
- Sentence Transformers
- FAISS Vector Database
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## Dataset

**Brain Tumor MRI Dataset**

Source: Kaggle

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

### Classification Categories

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

## Project Workflow

1. Dataset Acquisition
2. Exploratory Data Analysis
3. Image Preprocessing
4. Vision Transformer Model Development
5. Model Training and Validation
6. Model Evaluation
7. Confusion Matrix
8. MRI Image Prediction
9. LLM Integration
10. RAG Implementation
11. Text Embedding Generation
12. FAISS Vector Database
13. Educational Question Answering
14. Prediction Results Export to CSV

## LLM and RAG Architecture

The educational assistant uses:

- **LLM:** Google FLAN-T5 Base
- **Embedding Model:** all-MiniLM-L6-v2
- **Vector Database:** FAISS
- **Retrieval System:** Semantic Similarity Search

### RAG Workflow

Question → Embeddings → FAISS Retrieval → Relevant Context → LLM → Answer

## Model Evaluation

The classification model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Actual evaluation results are available in the generated evaluation report.

## Project Outputs

- Trained Vision Transformer Model
- MRI Classification Predictions
- CSV Prediction Results
- Confusion Matrix
- Training and Validation Graphs
- RAG Knowledge Base
- FAISS Vector Database
- LLM Educational Assistant

## Installation

```bash
pip install torch torchvision transformers sentence-transformers faiss-cpu scikit-learn pandas matplotlib seaborn
```

## How to Run

1. Open the project notebook in Google Colab.
2. Download the Kaggle dataset.
3. Run the preprocessing and training cells.
4. Evaluate the Vision Transformer model.
5. Load the FLAN-T5 language model.
6. Initialize the RAG system.
7. Test the educational chatbot.

## Future Improvements

- Develop a Streamlit web application.
- Add more verified medical educational documents.
- Improve MRI classification performance.
- Add multilingual chatbot support.
- Implement better source-grounded responses.
- Add model explainability features.

## Disclaimer

This project is developed for educational and research purposes only. MRI classification predictions and chatbot responses are not medical diagnoses or treatment recommendations. Always consult qualified healthcare professionals for medical decisions.

## Author

**Shafaat Ullah**

AI & Data Science Enthusiast

Department: Artificial Intelligence

## License

MIT License
