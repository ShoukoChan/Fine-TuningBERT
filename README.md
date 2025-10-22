# Fine-TuningBERT
Question Answering with fine-tuned BERT using Hugging Face Transformers and PyTorch on CoQA dataset

## Overview

* **Objective:** Use a pre-trained BERT model to answer questions based on text passages from the CoQA dataset.
* **Model Used:** `bert-large-uncased-whole-word-masking-finetuned-squad`
* **Dataset:** [CoQA (Conversational Question Answering)](https://stanfordnlp.github.io/coqa/)
* **Libraries:** `transformers`, `torch`, `pandas`, `numpy`


### Python Libraries Used
* `torch==1.7.1`
* `transformers==4.4.2`
* `pandas`
* `numpy`

## Dataset Description
* **Source:** [Stanford CoQA Dataset](https://stanfordnlp.github.io/coqa/)
* **Format:** JSON
* **Fields Used:**
  * `story` (context)
  * `questions.input_text` (question)
  * `answers.input_text` (answer)

# Steps Involved:

### 1. Data Preprocessing

### 2. Model Loading

### 3. Sample Inference
* Tokenization & Input Preparation
* Get Answer from Model

### 4. Final Answer Reconstruction

### 5. Interactive Q&A Function

### 6. Chat Interface



## References

* [Hugging Face Transformers](https://huggingface.co/transformers/)
* [CoQA Dataset](https://stanfordnlp.github.io/coqa/)
* [BERT Paper](https://arxiv.org/abs/1810.04805)

