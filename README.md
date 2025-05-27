# 🧠 Fine-Tuning NLLB for English–Wolof Translation (Latin Script)

This project fine-tunes Meta AI’s NLLB (No Language Left Behind) model to translate from **English** to **Wolof (LaTn)**, a low-resource language using the Latin script. The training pipeline leverages Hugging Face’s ecosystem to tokenize data, fine-tune multilingual transformers, and evaluate translation quality using standard metrics.

---

## 📌 Project Highlights

- 🔤 Language Pair: `English → Wolof (LaTn)`
- 🧰 Model Base: [facebook/nllb-200-distilled-1.3B](https://huggingface.co/facebook/nllb-200-distilled-1.3B)
- ⚙️ Tools: Hugging Face Transformers, Datasets, Evaluate, and Colab (or local GPU)
- 📄 Format: Python code implemented in a Jupyter Notebook

---

## 🚀 Example Usage

### ✅ Install Required Packages

```bash
pip install transformers datasets sacrebleu evaluate sentencepiece ...
```

## 🧪 Evaluation
After training, the model is evaluated using:

BLEU Score – Measures n-gram overlap between candidate and reference translations.

## 🙏 Acknowledgements
- Meta AI – for releasing the NLLB-200 model
- Hugging Face – for transformers, datasets, and evaluate libraries
- JW300 / MENYO-20k / ROGENDO – multilingual parallel corpora for low-resource African languages
- Google Colab – free GPU access for prototyping and training


## Warning
Translations in some way are not very accurate. However, this note shows the implementation steps for a Seq2Seq fine-tuning process.
