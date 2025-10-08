# Fine-Tuning GPT for Fake News Generation

The Jupyter notebook `Дообучение_GPT,_генерация_фейковых_новостей.ipynb` demonstrates **fine-tuning a GPT-based language model** on a custom dataset of news articles to generate realistic-looking fake news.

## 🧠 Fine-Tuning GPT for Fake News Generation

- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1a2_OfmguNoDJ6v8R3shKLZK6B1k1zxYZ?usp=sharing)

## 🎯 Project Goals
- Understand the **fine-tuning process** for GPT models on domain-specific data.  
- Demonstrate changes in model behavior after training.  
- Build a simple fake news generator capable of producing plausible short news stories.  

## 🧠 Workflow
1. **Data preparation** — collect and clean a dataset of real and synthetic news texts.  
2. **Text preprocessing** — tokenization, stopword removal, normalization.  
3. **Model fine-tuning** — train a pre-trained GPT model (`GPT-2` / `distilgpt2`) using the `transformers` library.  
4. **Text generation** — generate new news examples using the fine-tuned model.  
5. **Evaluation** — compare generated texts with the original ones by structure and fluency.  

## 🧰 Libraries
- `transformers`, `datasets`, `torch`  
- `pandas`, `numpy`, `matplotlib`  
- `tqdm`, `re`, `nltk`  

## 📊 Results
- The model was successfully fine-tuned on the custom dataset.  
- Generated texts mimic real news style and syntax.  
- The project demonstrates practical GPT fine-tuning for NLP tasks.  

## 📁 Project Structure
```
├─ data/
│  ├─ train.csv
│  ├─ valid.csv
│  └─ tokenizer/
│
├─ Дообучение_GPT,_генерация_фейковых_новостей.ipynb
└─ README_EN.md
```

## 📝 Output Data
- Generated news texts produced by the fine-tuned GPT model.  
- Training logs and metrics.
