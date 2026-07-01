# Nlpians-NLP

A custom implementation of the Word2Vec model built from scratch — including dataset preparation, text cleaning, TF-IDF weighted context matrices, and a softmax-based forward pass trained with negative log-likelihood loss.

This project was built as part of **Assignment 1**, focused on understanding word embeddings at a fundamental level rather than using pre-built libraries like Gensim.

---




## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Nlpians-NLP.git
   cd Nlpians-NLP
   ```

2. Install dependencies (see `req.txt` for the full pipeline reference):
   ```bash
   pip install numpy pandas nltk scikit-learn
   ```

3. Run the cleaning pipeline first:
   - Open and execute `clean.ipynb` to preprocess `testdata.txt`.

4. Train the custom Word2Vec model:
   - Open and execute `final.ipynb`, which uses `new.txt` as training data.



## 📄 License

This project is open for educational use. Feel free to fork and build upon it.
