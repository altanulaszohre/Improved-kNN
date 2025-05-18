# 🤖 Text Classification with BERT

This project demonstrates how to perform **text classification** using **BERT (Bidirectional Encoder Representations from Transformers)**. The model classifies news articles into categories using a dataset (BBC news) and leverages the powerful transformer-based architecture for state-of-the-art accuracy.

---

## 📌 Project Highlights

- Fine-tuning **BERT** for text classification tasks
- Visual analysis of data distribution and training metrics
- Prediction module for classifying new input texts
- Dataset: Pre-labeled BBC news dataset

---

## 📁 Folder Structure

```
Text-Classification-with-BERT/
│
├── Code/
│   ├── BERT_Train_Model.ipynb      # Fine-tuning BERT model on dataset
│   ├── prediction.ipynb            # Using trained model to predict new examples
│   └── data_visualization.ipynb    # Data distribution and EDA
│
├── Data/NLP/
│   └── bbc_data.csv                # BBC News Dataset
│
├── trained_model/
│   └── config.json                 # Saved BERT model config
│
├── LICENSE
└── README.md
```

---

## 📊 Data Distribution Overview

The dataset contains news articles categorized into multiple topics such as tech, business, politics, etc.

![Data Distribution](https://github.com/altanulaszohre/Text-Classification-with-BERT/assets/111522957/b36425a6-280d-41af-a3fd-1f2c1f0349bb)

![Class Distribution](https://github.com/altanulaszohre/Text-Classification-with-BERT/assets/111522957/535cc5ec-bb55-4448-9ca3-c6e0e3bbbe16)

---

## 🏋️ Model Training Overview

We fine-tune a pretrained BERT model using HuggingFace Transformers and visualize training accuracy and loss during epochs.

![Training Accuracy](https://github.com/altanulaszohre/Text-Classification-with-BERT/assets/111522957/9fb5ee3f-bae8-4410-81f6-b96c4003daab)

![Training Loss](https://github.com/altanulaszohre/Text-Classification-with-BERT/assets/111522957/c8a37a3f-a6d4-4bda-904d-ecc76912fbae)

---

## 🧪 Prediction Results

The model can accurately classify new examples into the correct category.

![Prediction](https://github.com/altanulaszohre/Text-Classification-with-BERT/assets/111522957/cc7ae654-fc88-4b17-b613-d169e77a58ae)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Text-Classification-with-BERT.git
   cd Text-Classification-with-BERT/Code
   ```

2. Install required libraries:
   ```bash
   pip install transformers torch scikit-learn pandas matplotlib
   ```

3. Open and run the notebooks in the following order:
   - `data_visualization.ipynb`
   - `BERT_Train_Model.ipynb`
   - `prediction.ipynb`

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for details.

---

## 🙌 Acknowledgments

Thanks to:
- [HuggingFace Transformers](https://huggingface.co/transformers/)
- [PyTorch](https://pytorch.org/)
- The BBC dataset provider
