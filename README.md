# NCERT Doubt Solver
# Biology LLM Fine-Tuning (LoRA)

## 🚀 Problem

Students struggle to get clear answers from NCERT Biology in an interactive way.

## 💡 Solution

Built a domain-specific LLM by fine-tuning a base model on Biology Q&A data using LoRA.

## ⚙️ Pipeline

1. Extract data from Excel (NCERT dataset)
2. Convert to instruction format (JSONL)
3. Tokenize using HuggingFace tokenizer
4. Fine-tune model using LoRA (Unsloth)
5. Save trained adapters

## 🧠 Tech Stack

* Python
* HuggingFace Transformers
* Unsloth (LoRA fine-tuning)
* Pandas

## 🔥 Key Concepts

* Instruction tuning
* Tokenization
* Parameter-efficient fine-tuning (LoRA)

## 📌 Future Improvements

* Add RAG (retrieval system)
* Add multilingual support
* Build UI using Gradio

## 👨‍💻 Author

Ishaan Sharma
