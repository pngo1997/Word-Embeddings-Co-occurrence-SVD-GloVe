# 🔠 Word Embeddings: Co-occurrence, SVD & GloVe  

## 📜 Overview  
This project explores **word embeddings**, focusing on two key approaches:  

1. **Manually creating word embeddings** using a **co-occurrence matrix** and **Singular Value Decomposition (SVD)** for dimensionality reduction.  
2. **Experimenting with pre-trained GloVe embeddings**, verifying similarity relations, analogies, and inspecting ambiguous word embeddings.  

📌 **Key Concepts Covered**:  
- **Word Representations**: Understanding distributed word embeddings.  
- **Co-occurrence Matrix**: Capturing contextual relationships between words.  
- **Dimensionality Reduction**: Applying **Singular Value Decomposition (SVD)** to derive dense word vectors.  
- **Word Embedding Visualization**: Plotting embeddings in 2D space for interpretation.  
- **GloVe Embeddings**: Exploring **pre-trained embeddings**, analogy tasks, and ambiguity analysis.  

## 🚀 1️⃣ Implementation Details  

### **Part 1: Manually Creating Word Embeddings**  
✅ **Build a Co-occurrence Matrix** from a given corpus.  
✅ **Apply SVD** to reduce dimensionality and extract word vectors.  
✅ **Visualize embeddings** in 2D space using **Matplotlib & PCA**.  
✅ **Analyze Word Relationships**:  
   - Plot words with similar meanings in vector space.  
   - Observe clusters of related words.  

### **Part 2: Exploring GloVe Embeddings**  
✅ **Load Pre-trained GloVe Embeddings**.  
✅ **Reduce Dimensionality** using **PCA to 2D** for visualization.  
✅ **Evaluate Word Similarities & Analogies**:  
   - Verify relationships between semantically similar words.  
   - Solve analogy tasks (`king - man + woman ≈ queen`).
     
✅ **Analyze Ambiguous Words**:  
   - Inspect word embeddings for words with multiple meanings (e.g., "bank" as a financial institution vs. riverbank).  

## 📊 2️⃣ Results & Visualizations  

### **Example: Word Embedding Plot**  
📌 **Visualization of word vectors in 2D space**:  
- Displays clusters of related words.  
- Shows how embeddings capture semantic relationships.  
- PCA is used to reduce high-dimensional embeddings.  

### **Example: Analogical Reasoning**  
🔹 `king - man + woman ≈ queen`  
🔹 `Paris - France + Germany ≈ Berlin`  
🔹 `apple - fruit + vegetable ≈ carrot`  

✅ **The embeddings successfully capture analogical reasoning and semantic relationships**.  

## 📌 Summary  
✅ Implemented word embeddings from scratch using SVD.

✅ Explored pre-trained GloVe embeddings.

✅ Verified word relationships, analogies, and ambiguous words.

✅ Visualized embeddings in 2D space for interpretation.
