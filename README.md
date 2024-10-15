# GenerativeAI
This repository contains two main folders, each focusing on different aspects of natural language processing and computer vision using large language models.
## 1. Mistral 7B
This folder contains a notebook for inference using the Mistral 7B model.
### Features:

- Model loading using sharding and BitsAndBytes config for 4-bit quantization
- Utilizes HuggingFace Transformers pipeline
- Two types of queries available:

  - General question answering
  - In-context question answering



## 2. Fine-tuning
This folder contains a notebook for both inference and fine-tuning using the Llama 3.2 Vision 11B model.
### Features:

- Inference setup for Llama 3.2 Vision 11B
- Fine-tuning implementation using a custom iPhone 16 dataset
- Dataset available on Hugging Face: iphone16-dataset
- Utilizes LoRA (Low-Rank Adaptation) for efficient fine-tuning
- Implements the Transformers Trainer class for the fine-tuning process
