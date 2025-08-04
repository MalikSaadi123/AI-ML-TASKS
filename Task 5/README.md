# Task 5: Mental Health Support Chatbot

## Objective
Develop a chatbot that provides supportive and empathetic responses for stress, anxiety, and wellness.

## Dataset
- **Name**: EmpatheticDialogues
- **Source**: Hugging Face
- **Description**: Human-human empathetic dialogues for emotional support

## Steps Performed
- Loaded dataset from Hugging Face
- Tokenized using GPT-2 tokenizer
- Fine-tuned DistilGPT-2 using Hugging Face Trainer API
- Built CLI interface for testing chatbot responses

## Tools & Libraries
- Hugging Face Transformers
- Datasets
- PyTorch
- Accelerate

## Key Results
- Model responds with supportive and context-aware messages
- Maintains empathetic tone and avoids harmful suggestions

