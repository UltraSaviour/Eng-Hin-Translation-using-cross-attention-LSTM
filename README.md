# 🇬🇧→🇮🇳 English to Hindi Translation using Cross-Attention LSTM 🧠

This repository implements a sequence-to-sequence neural machine translation (NMT) model that translates English sentences into Hindi using an **LSTM-based encoder-decoder architecture with a cross-attention mechanism**.

> 🚀 Automated setup scripts included to get started quickly!

---

## 📁 Project Structure

```
.
├── Sentence pairs in English-Hindi - 2025-02-11.tsv  # Main dataset
├── auto-dir-setup.sh        # Sets up directory structure for deployment
├── auto-setup.sh            # Creates virtualenv and installs requirements
├── lib-install.sh           # Installs necessary libraries
├── requirements.txt         # Python dependencies list
├── src.ipynb                # Jupyter Notebook with the model
└── .gitignore               # Ignore unnecessary files
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/UltraSaviour/Eng-Hin-Translation-using-cross-attention-LSTM.git
cd Eng-Hin-Translation-using-cross-attention-LSTM
```

2. **Make setup scripts executable**
```bash
chmod +x *.sh
```

3. **Run the full setup**
```bash
./auto-dir-setup.sh      # Set up necessary directories
./auto-setup.sh          # Create virtual environment and install requirements
./lib-install.sh         # Install additional libraries (if any)
```

4. **Start the notebook**
```bash
jupyter notebook src.ipynb
```

---

## 🧠 About the Model

- **Encoder**: Bidirectional LSTM
- **Decoder**: LSTM with attention
- **Attention Mechanism**: Dot-product cross-attention over encoder states
- **Training**: Trained on parallel English-Hindi sentence pairs
- **Framework**: TensorFlow + Keras

---

## 📊 Dataset

- Format: `.tsv` file with two columns – English and Hindi
- File: `Sentence pairs in English-Hindi - 2025-02-11.tsv`
- Feel free to replace or extend this dataset for better results

---

## 🧪 Sample Output

| English Input             | Hindi Translation              |
|---------------------------|---------------------------------|
| How are you?              | आप कैसे हैं?                   |
| I love machine learning.  | मुझे मशीन लर्निंग पसंद है।      |

---

## 📦 Requirements

All required Python libraries are listed in `requirements.txt`.

```bash
pip install -r requirements.txt
```

Or just run the setup script (`auto-setup.sh`) to install everything automatically.

---

## 🙋‍♂️ Author

**Prateek Sharma**  
B.Tech Data Science – Poornima University  
GitHub: [UltraSaviour](https://github.com/UltraSaviour)

---
