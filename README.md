PEGASUS News Summarization 📰✨

A complete pipeline for abstractive news summarization using the PEGASUS transformer.
Includes data preprocessing, tokenization, model fine-tuning, evaluation, and a Streamlit-powered web app for real-time summarization.

🚀 Project Overview

This project fine-tunes the google/pegasus-xsum model on English news articles.
Key highlights:

✅ Robust text cleaning & preprocessing

✅ Tokenization and efficient sequence-to-sequence training

✅ Performance evaluation with ROUGE metrics

✅ Ready-to-use Streamlit demo app for generating summaries

📂 Project Structure
PEGASUS-News-Summarization/
├── App/
│   └── streamlit_pegasus_app.py         # Streamlit app for interactive summarization
├── Data/
│   ├── Raw/                             # Raw, original datasets
│   └── Processed/
│       ├── english_train_cleaned.csv
│       ├── english_test_cleaned.csv
│       └── tokenized_pegasus_english/
│           ├── train/                   # Tokenized training data
│           └── test/                    # Tokenized test data
├── Models/
│   └── pegasus_english_finetuned/
│       ├── checkpoint-*/                # Model checkpoints
│       └── final_model/                 # Final fine-tuned model & tokenizer
├── Notebooks/
│   ├── Preprocessing/
│   │   └── preprocessing_english.ipynb  # Data cleaning & EDA
│   ├── Tokenization/
│   │   └── pegasus_tokenize.ipynb       # Prepare datasets for training
│   └── Training/
│       └── train_pegasus_final.ipynb    # Fine-tuning & monitoring
│   └── Evaluation/
│       └── evaluation.ipynb             # ROUGE evaluation & sample summaries
├── requirements.txt                     # Dependencies
└── README.md                            # Project info & instructions


---

## 📊 Dataset & Trained Model  

Since the dataset and model are large, they are provided via Google Drive:  

- **Dataset (Raw + Processed + Tokenized):**  
  [📥 Download Here](https://drive.google.com/file/d/1T9mx5l-4CLOw7nRQAujT3CSGl3F-rXII/view?usp=drive_link)  
  ➡️ Place inside `Data/` after unzipping  

- **Fine-Tuned PEGASUS Model:**  
  [📥 Download Here](https://drive.google.com/file/d/167KtBRJPTy_LgxAhKMDiC8HXcs9QLkdP/view?usp=drive_link)  
  ➡️ Place inside `Models/` after unzipping  

---


## Contributors

- Abhishek Shete (https://github.com/Abhishekshete0808)  
- Shivam Chincholkar (https://github.com/Shivam22112)
