# 🧠 Fine-Tuning NLLB for Language Translation

This project fine-tunes Meta AI’s NLLB (No Language Left Behind) model to translate from **English** to **selected language (LaTn)**, especially low-resource languages. The training pipeline leverages Hugging Face’s ecosystem to tokenize data, fine-tune multilingual transformers, and evaluate translation quality using standard metrics.

---

## 📌 Project Highlights

- 🔤 Language Pair: `English → ....`
- 🧰 Model Base: [facebook/nllb-200-distilled-1.3B](https://huggingface.co/facebook/nllb-200-distilled-600M)
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
- Hugging Face – for transformers, datasets, and evaluation libraries
- JW300 / MENYO-20k / ROGENDO – multilingual parallel corpora for low-resource African languages
- Google Colab – free GPU access for prototyping and training


## Take-Away
Efficient translation models capable of an appreciable degree of accurate English-to-African-language translation. These notebooks show the implementation steps for a Seq2Seq fine-tuning process.
