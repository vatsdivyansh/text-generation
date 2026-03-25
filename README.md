# Text Generation — From RNN to Transformer

A project where I built three text generation models from scratch using PyTorch — Simple RNN, LSTM, and Transformer — and compared their ability to generate text on the same dataset.

The goal was to understand how language models evolved over time and why each architecture was invented to fix the limitations of the previous one.

## What I Built

Starting from NLP basics like tokenization and embeddings, I progressively built a Simple RNN, then an LSTM, and finally a Transformer with self attention from scratch. All three models were trained on Shakespeare text and evaluated on text generation quality and training loss.

## Key Observation

On this small dataset LSTM produced the most coherent text. The Transformer struggled without enough data — which is exactly why models like GPT are trained on billions of tokens with massive compute.# text-generation
