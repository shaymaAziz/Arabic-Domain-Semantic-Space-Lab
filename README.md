# Arabic-Domain-Semantic-Space-Lab

## 📌 Notebook Overview

The `Shayma_Azhrani_GATE_Arabic_Domain_Semantic_Space_Lab.ipynb` notebook provides a complete Python environment to apply semantic space concepts, representing Arabic words and sentences in a multi-dimensional vector space to extract semantic relationships and analyze domain-specific contexts.

## ⚖️ Conceptual Comparison: Traditional Statistical Models vs. Modern Semantic Vector Spaces

| Feature | Traditional Statistical Models (e.g., TF-IDF / Bag of Words) | Semantic Vector Space (Dense Embeddings) |
| --- | --- | --- |
| **Context Awareness** | Relies on exact word counts and ignores context completely. | Captures semantic meaning and context based on surrounding words. |
| **Synonym Handling** | Treats synonyms (e.g., "حاسب" and "كمبيوتر") as independent entities. | Maps semantically similar words close to each other in the vector space. |
| **Vector Dimensionality** | High-dimensional and sparse vectors that grow with vocabulary size. | Fixed-size, dense, continuous vectors that optimize computational efficiency. |

## 💻 Numerical & Practical Example

When measuring semantic similarity using Cosine Similarity between word vectors in the Arabic semantic space:

* Assumed word vectors in the space:
* Vector for "تقنية" (Technology): $\vec{v}_1 = [0.85, 0.50, 0.20]$
* Vector for "تكنولوجيا" (Technology): $\vec{v}_2 = [0.82, 0.53, 0.22]$
* Vector for "حديقة" (Garden): $\vec{v}_3 = [0.10, 0.05, 0.90]$


* **Calculation & Execution:** Computing the Cosine Similarity yields a similarity score of approximately **0.98** between $\vec{v}_1$ and $\vec{v}_2$ (indicating strong semantic proximity), whereas the similarity between $\vec{v}_1$ and $\vec{v}_3$ is approximately **0.18** (indicating semantic divergence). This demonstrates the model's ability to accurately capture contextual meaning.

## ❓ Expected Exam & Assessment Questions (with Model Answers)

* **Question 1:** Why is Cosine Similarity preferred over Euclidean Distance when comparing semantic text vectors?
* **Model Answer:** Euclidean distance is sensitive to vector magnitude, which varies with text or document length. Cosine similarity measures the angle between vectors regardless of their magnitude, making it a more accurate metric for pure semantic similarity.


* **Question 2:** How does Domain Adaptation impact the performance of Arabic semantic spaces?
* **Model Answer:** Arabic is rich in morphology and derivation. Training a semantic space on a general domain is often insufficient for understanding domain-specific terminology (e.g., medical or technical terms). Domain fine-tuning adjusts vector weights to align accurately with specialized contexts.



## 🚀 How to Run

1. Clone the repository via terminal:
```bash
git clone https://github.com/your-username/Arabic-Domain-Semantic-Space-Lab.git

```


2. Launch and run the notebook using Jupyter:
```bash
jupyter notebook Shayma_Azhrani_GATE_Arabic_Domain_Semantic_Space_Lab.ipynb

```
