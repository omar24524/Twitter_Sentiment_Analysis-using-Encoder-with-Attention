# 📊 Twitter Sentiment Analysis with Bi-LSTM + Attention

A PyTorch implementation of a **4-way Twitter sentiment classifier** (**Irrelevant**, **Negative**, **Neutral**, **Positive**) using:  
- Custom text cleaning & tokenization  
- Train-from-scratch or optional GloVe-Twitter word embeddings  
- Bidirectional LSTM encoder  
- Additive attention layer  
- Linear classifier  


## 🛠️ Requirements

- Python 3.7+  
- PyTorch 1.7+  
- pandas, scikit-learn, nltk (optional), tqdm  
- (Optional) GloVe-Twitter embeddings  

Install dependencies:  
```bash
pip install -r requirements.txt
