
# 🚀 NLP Challenges & Workspaces

<p align="center">
  <a href="https://github.com/Suman18-bit/NLP_CHALANGES">
    <img src="https://img.shields.io/github/stars/Suman18-bit/NLP_CHALANGES?style=for-the-badge&color=8A2BE2" alt="Stars">
  </a>
  <a href="https://github.com/Suman18-bit/NLP_CHALANGES/issues">
    <img src="https://img.shields.io/github/issues/Suman18-bit/NLP_CHALANGES?style=for-the-badge&color=red" alt="Issues">
  </a>
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/spaCy-v3.x-09A3D5?style=for-the-badge&logo=explosion&logoColor=white" alt="spaCy">
</p>

<p align="center">
  <strong>A structured workspace for core Natural Language Processing tasks, vectorization techniques, and custom spaCy sequence-labeling models.</strong>
</p>

---

## 🎯 Project Architecture & Modules

### ⚙️ 1. Text Representations & Feature Engineering
Transforming raw text spaces into numerical mathematical matrices ($X \in \mathbb{R}^{m \times n}$).

| Notebook / File | Concept Covered | Approach Type |
| :--- | :--- | :--- |
| `One_Hot_Encoding.ipynb` | Categorical Token Vectors | Binary Sparse Arrays |
| `Bag_Of_Words.ipynb` | Frequency-based Representation | Count-based Matrix |
| `Tfiidf_Vertorizer.ipynb` | Term Frequency-Inverse Document Frequency | Statistical Weighting |
| `N_Grams.ipynb` | Contiguous Sequence Extraction | Contextual Windowing |
| `Word2Vec.ipynb` | Distributed Continuous Word Embeddings | Neural Word Semantics |

### 🧠 2. Named Entity Recognition (NER) & spaCy V3 Pipelines
End-to-end industrial model compilation using spaCy's configuration ecosystem.

* **Notebooks:**
  * `NER.ipynb` — Out-of-the-box rule-based and pre-trained extraction.
  * `01_03_data_annotation_for_named_entities.ipynb` — Custom dataset token labeling and boundary formatting.
  * `Custom_model_training_with_spacy.ipynb` — System optimization and neural training loop initialization.
* **Pipeline Infrastructure Assets:**
  * `base_config.cfg` $\rightarrow$ `config.cfg` $\rightarrow$ `default_config.cfg` — High-fidelity hyperparameter training layouts.
  * `train.spacy` / `test.spacy` — Serialized binary DocBin streams for standard ingestion.

### 📊 3. Semantic Analysis & Text Foundations
* **Basic Processing:** `NLP.ipynb`, `NLP2.ipynb`, `NLP3.ipynb`, `Precktice.ipynb` — Tokenization, Lemmatization, Stop-word scrubbing, and regex validation.
* **Topic Modeling:** `Topic_modeling.ipynb` — Latent semantic structural mining across text datasets.
* **Corpus & Data Targets:** `feedback_data.csv`, `ch4_feedback_data.csv`, `sentiment_examples.txt`.

---

## 📂 Directory Layout

```bash
📂 NLP_CHALANGES
├── 📂 configs/
│   ├── base_config.cfg         # Initial spaCy pipeline template
│   ├── config.cfg              # Auto-generated full train config
│   └── default_config.cfg      # Backup default fallback specs
├── 📂 data/
│   ├── train.spacy            # Binary training dataset 
│   ├── test.spacy             # Binary evaluation dataset
│   ├── feedback_data.csv      # Sentiment/Topic evaluation dataset
│   └── sentiment_examples.txt # Plaintext target samples
└── 📂 notebooks/
    ├── NLP_Basics_1_to_3.ipynb # Text pre-processing modules
    ├── Vectorizers_and_BoW    # Word representation spaces
    └── Custom_NER_Training    # Production model development pipelines

```
## 🛠️ Installation & Execution Blueprint
Clone the setup and construct a sterile isolated Python environment:
```bash
# Clone the repository
git clone [https://github.com/Suman18-bit/NLP_CHALANGES.git](https://github.com/Suman18-bit/NLP_CHALANGES.git)
cd NLP_CHALANGES

# Initialize virtual environment
python -m venv environment
source environment/bin/activate # Win: environment\Scripts\activate

# Install required system packages
pip install --upgrade pip
pip install spacy nltk pandas numpy notebook scikit-learn

# Download required language models
python -m spacy download en_core_web_sm

```
## 👨‍💻 Developer Ecosystem
**Suman Seth**
 * GitHub Profile
<p align="center">
🛡️ Give a star ⭐ if this repository helped your NLP development setup!
</p>

