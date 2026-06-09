# AI/ML Engineering Internship Project - DevelopersHub

## Objective
The objective of this project is to demonstrate technical proficiency across five core AI/ML domains: Natural Language Processing (BERT fine-tuning), Production-ready ML Pipelines, Multimodal Learning (Vision + Tabular), Retrieval-Augmented Generation (RAG), and LLM Prompt Engineering.

## Methodology / Approach
- **Task 1 (NLP):** Fine-tuned the `bert-base-uncased` model on the AG News dataset using the Hugging Face `Trainer` API for multi-class classification.
- **Task 2 (ML Pipeline):** Developed a scikit-learn `Pipeline` to automate preprocessing (Scaling/One-Hot Encoding) and classification (Random Forest) for churn prediction.
- **Task 3 (Multimodal):** Built a dual-branch Keras model combining a CNN (for images) and an MLP (for tabular data) to predict housing prices via feature fusion.
- **Task 4 (RAG Chatbot):** Implemented a context-aware system using `sentence-transformers` for embeddings and `FAISS` for vector similarity search, grounded by a Flan-T5 generator.
- **Task 5 (Auto Tagging):** Engineered prompts for an LLM-based support ticket classifier using few-shot learning logic to categorize technical and billing inquiries.

## Key Results / Observations
- **BERT Classification:** Achieved high accuracy on the news subset, showing BERT's robust semantic understanding.
- **Pipeline Automation:** The scikit-learn pipeline successfully exported a deployable `.joblib` model, ensuring consistent data transformations.
- **Multimodal Fusion:** Combining visual features with structural data resulted in more accurate price estimations than using a single modality.
- **RAG Stability:** By using a direct FAISS implementation, the chatbot avoided hallucinations by strictly retrieving context from the knowledge base.