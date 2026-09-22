# Tabeeb-Gara7 🩺
--------------------
A two-stage medical search and reranking engine built to match user symptom queries with relevant medical conditions from an NHS database[cite: 1].


## 📌 Architecture & Features
-----------------------------------
-----------------------------------
1. **Candidate Retrieval (FAISS):** Embeds text with `sentence-transformers/all-MiniLM-L6-v2` and runs fast dense vector searches using FAISS[cite: 1].
2. **Re-ranking (TensorFlow / Keras):** A trained sequential neural network scores query-document embedding pairs to improve final search accuracy[cite: 1].
3. **Data Preprocessing:** Cleans and processes text from MongoDB using `nltk` tokenization and lemmatization[cite: 1].


## 🛠️ Stack
--------------
--------------
* Python 3[cite: 1]
* MongoDB (`pymongo`)[cite: 1]
* FAISS (`faiss-cpu`)[cite: 1]
* Sentence-Transformers[cite: 1]
* TensorFlow / Keras[cite: 1]
* NLTK & Pandas[cite: 1]
