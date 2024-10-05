# Pretrained Recorder-Like Model with Local Self-Attention for Faster Training

## Overview

This project focuses on building a **recorder-like model** (similar to GPT architectures) that uses **local self-attention** mechanisms for faster training and inference. By leveraging this mechanism, we aim to reduce the computational complexity typically associated with global self-attention, making the model more efficient without sacrificing accuracy, especially on long sequences.

The model is pretrained on the **FineWeb Edu** dataset, which is tailored for educational content processing and understanding. The dataset consists of diverse textual data focusing on structured and unstructured educational material, enabling the model to handle tasks such as summarization, question answering, and content generation in the education domain.

## Key Features

- **Decorder-like Architecture**: A transformer-based architecture focused on autoregressive modeling, like GPT, but optimized for more efficient sequence processing.
- **Local Self-Attention**: Restricts attention to a localized window of tokens, reducing complexity while preserving model effectiveness.
- **Pretraining on FineWeb Edu Dataset**: The model is pretrained on a specialized dataset, making it well-suited for tasks in the education domain.
- **Efficient Training**: Faster and more memory-efficient compared to traditional transformer models.

## Dataset: FineWeb Edu

The **FineWeb Edu** dataset includes educational texts that span various subjects and levels. It consists of:

- **Textbooks and course materials**
- **Research papers and summaries**
- **Structured educational data like quizzes, tests, and exams**
- **Unstructured data like student notes and discussions**

The dataset is designed to help the model learn contextual understanding, content generation, and summarization in educational settings.

