# IEEE SIGHT ENSIT — Machine Learning Fundamentals Workshop

> **From raw data to a model "you can trust"**
> Prepared and presented by **Farah Hammami** · Organized by **IEEE SIGHT — ENSIT SIGHT Group** · 29/09/2026

---

## About the workshop

This workshop introduces the core ideas of Machine Learning from first principles. It is not about memorizing algorithms. It is about understanding the full path from a real-world question to a model you can actually trust:

> **fθ(X) ≈ y** — find parameters θ so that a function gets close to reality, *and still works on data it has never seen.*

The session combines a **guided presentation** (concepts) with an **interactive notebook** (practice and decision-making).

---

## Download the materials

| Resource | Description | 
|---|---|
|  **Presentation (PDF)** | The full slide deck used during the workshop | 
|  **Notebook (.ipynb)** | The *Interactive Decision Lab* for the fundamental practice | 

The same files are also included in this archive:

```
IEEE_SIGHT_ML_Workshop/
├── README.md
├── IEEE_SIGHT_ML_Fundamentals.pdf
└── IEEE_SIGHT_ML_Decision_Lab.ipynb
```

---

## Workshop structure

### Part 1 — Presentation (concepts)

| # | Section | What you will learn |
|---|---|---|
| 01 | **The AI Landscape** | A brief history of AI (1956 → agents), where ML sits between Symbolic AI, Deep Learning, and LLMs, and why ML still matters underneath it all |
| 02 | **From Reality to Data** | Data ≠ Information ≠ Knowledge; why a table of numbers does not contain "knowledge" until a human (or a model) extracts the pattern |
| 03 | **From Data to Computation** | Exploratory Data Analysis (EDA) and why it is where projects fail (missing values, wrong types, outliers, duplicates, leakage); why Python; vectors and matrices; vectorization |
| 04 | **From Computation to Learning** | Supervised vs unsupervised learning; the ML problem fθ(X) ≈ y; algorithm vs model; the loss function; gradient descent; the learning loop |
| 05 | **Models** | Overview of regression, classification, clustering, dimensionality reduction; train vs test; underfitting vs overfitting; the evaluation trap (accuracy is not enough); the full ML workflow with NumPy, pandas, scikit-learn |

### Part 2 — Notebook: *Interactive Decision Lab — "Can You Trust This Model?"*

The notebook is the **hands-on practice for the fundamentals**. It is **not a coding exercise**. It is a decision-making lab built around one case:

> A university wants to identify students who may need academic support **two weeks before the final exam**.

At each checkpoint, participants **predict / decide first**, submit their answer, then open the reveal and discuss whether their decision changes.

| Checkpoint | Theme | Key idea |
|---|---|---|
| 1 | **From reality to data** | Identify the target `y` and the type of problem (classification) |
| 2 | **EDA: be a data detective** | Investigate outliers, missing values, and duplicates before acting |
| 3 | **The suspiciously powerful feature** | Spot **data leakage**: a feature unavailable at prediction time |
| 4 | **A higher score can be a worse experiment** | 97% with leakage vs. 82% that is actually valid |
| 5 | **Train ≠ test** | Recognize underfitting, good generalization, and overfitting |
| 6 | **The evaluation trap** | Choose the metric based on which errors cost the most (false negatives) |

---

## How to use this workshop

1. **Download** the presentation and the notebook.
2. Go through the **slides** section by section.
3. Open the **notebook** in [Google Colab](https://colab.research.google.com/) (File → Upload notebook), or in Jupyter.
4. At each checkpoint, **answer before opening the reveal**.
5. Discuss: *Did your decision change, and why?*

**Requirements:** a Google account (for Colab) or a local Jupyter installation. No programming experience is needed for the Decision Lab.

---

## Key takeaways

- The first ML decision is not "which algorithm?" but **"what real-world question are we translating into X and y?"**
- **EDA** is where most projects succeed or fail.
- A powerful feature that comes from the future is **leakage**, not insight.
- **Training performance is not the goal.** Generalization to unseen data is.
- A metric only matters relative to **which errors actually cost you.**

---

## Contact

**Farah Hammami**
📧 [farahhammami8@gmail.com](mailto:farahhammami8@gmail.com)  
💼 [LinkedIn: farah-hammami-02](https://www.linkedin.com/in/farah-hammami-02/)  
💻 [GitHub: FarahHammamii](https://github.com/FarahHammamii)

*IEEE SIGHT — Special Interest Group on Humanitarian Technology · ENSIT SIGHT Group*
