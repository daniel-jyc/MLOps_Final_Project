# MLOps_Final_Project

This project consists of two parts: prompt engineering and instruction-tuning. There are five questions to test the LLMs:

1. What types of exercise are best for people with asthma?
2. How is obsessive-compulsive disorder diagnosed?
3. When are you more likely to get a blood clot?
4. How should you lift objects to prevent back pain?
5. How can you be smart with antibiotics?

## Base Model
LlaMa-2 7B
Mistral 7B

## Prompt Engineering
We are using comparing the answers generated with the following four different prompts:
1. Zero-Shot 2. Few-Shot 3. Chain-of-Thought 4. retrieval augmented generation (RAG)
   
## Instruction-tuning
We are using instruction tuning with data from MASHQA (Multiple Answer Spans Healthcare Question Answering) Research Paper: https://people.cs.vt.edu/mingzhu/papers/conf/emnlp2020.pdf
GitHub link: https://github.com/mingzhu0527/MASHQA

## Huggingface Links for tuned models

1. Llama-2: Danieljyc/Llama-2
  https://huggingface.co/Danieljyc/Llama-2
2. Mistral: Danieljyc/Mistral_7B_llr
  https://huggingface.co/Danieljyc/Mistral_7B_llr
