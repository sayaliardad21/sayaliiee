# 🧠 T5 Text Summarizer

This project builds a text summarizer using the **T5 Transformer model** from Hugging Face 🤗. It takes long input text (like news articles) and generates short, human-readable summaries.

## 📚 Tools & Libraries
- Python
- Google Colab
- 🤗 Hugging Face Transformers
- 🧠 T5ForConditionalGeneration
- CNN/DailyMail Dataset
- 🪄 Weights & Biases (WandB)

## 🏗️ Model Details
- Model: `t5-small`
- Tokenizer: `T5Tokenizer`
- Trained on subset of `cnn_dailymail` dataset
- Fine-tuned using Hugging Face `Trainer`
- Epochs: 3

## 📈 Evaluation
- Loss function: Cross Entropy
- Tracked using: WandB
- Validation on small subset

## 🧪 Example Input & Output

**Input:**
India became the first country to land a spacecraft near the Moon’s south pole on Wednesday — a historic voyage to uncharted territory that scientists believe could hold vital reserves of frozen water and precious elements. The Indian Space Research Organization (ISRO) confirmed that the Chandrayaan-3 lander successfully made a soft landing on the lunar surface. This achievement puts India in an elite club of nations, alongside the United States, China, and the former Soviet Union, who have managed to reach the Moon.


**Output:**
India successfully landed a spacecraft near the Moon’s south pole, becoming the first nation to do so, marking a historic scientific achievement.
