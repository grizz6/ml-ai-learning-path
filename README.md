# ML/AI Learning Path

My personal roadmap and to-do list for learning machine learning and AI, from the ground up. This repo has no code — it's just a living checklist I update as I go.

**Currently focused on:** Foundations (math + NumPy/Pandas) before moving into Core ML.

**How I use this:** check items off as I complete them, add notes/links under a topic when I find a good resource, and add new topics as I discover what I don't know yet.

## Contents

- [Foundations: Math & Programming](#foundations-math--programming)
- [Core Machine Learning](#core-machine-learning)
- [Deep Learning](#deep-learning)
- [Natural Language Processing / LLMs](#natural-language-processing--llms)
- [Computer Vision](#computer-vision)
- [MLOps & Deployment](#mlops--deployment)
- [Projects to Build](#projects-to-build)
- [Resources & Books](#resources--books)
- [Communities & Datasets](#communities--datasets)
- [Certifications to Consider](#certifications-to-consider)
- [Progress Log](#progress-log)

## Foundations: Math & Programming

- [ ] Linear algebra (vectors, matrices, eigenvalues/eigenvectors, matrix decomposition)
  - Focus areas: dot products, matrix multiplication rules, why eigenvectors matter for PCA later
- [ ] Calculus (derivatives, gradients, chain rule, partial derivatives)
  - Goal: understand gradient descent well enough to explain it without notes
- [ ] Probability & statistics (distributions, Bayes' theorem, hypothesis testing)
  - Includes: normal/binomial/Poisson distributions, p-values, confidence intervals
- [ ] Information theory basics (entropy, cross-entropy, KL divergence)
- [ ] Python fundamentals (already comfortable, but revisit idiomatic patterns)
- [ ] NumPy — array operations, broadcasting, vectorization
  - Practice: rewrite a few for-loops as vectorized NumPy ops and compare speed
- [ ] Pandas — data wrangling, cleaning, merging
- [ ] Data visualization (Matplotlib / Seaborn)

## Core Machine Learning

- [ ] What is ML? Supervised vs. unsupervised vs. reinforcement learning
- [ ] Linear & logistic regression
  - Implement both from scratch with just NumPy before using scikit-learn's version
- [ ] Decision trees & random forests
- [ ] Gradient boosting (XGBoost, LightGBM)
- [ ] Support vector machines
- [ ] k-nearest neighbors
- [ ] Clustering (k-means, hierarchical, DBSCAN)
- [ ] Dimensionality reduction (PCA, t-SNE, UMAP)
- [ ] Model evaluation (train/test split, cross-validation, metrics)
  - Metrics to know cold: accuracy, precision, recall, F1, ROC-AUC, confusion matrix
- [ ] Bias-variance tradeoff, overfitting/underfitting
- [ ] Feature engineering & selection
- [ ] scikit-learn — hands-on practice

## Deep Learning

- [ ] Neural network basics (perceptrons, activation functions, backprop)
  - Build a tiny neural net from scratch (no framework) to really understand backprop
- [ ] PyTorch fundamentals
- [ ] TensorFlow/Keras fundamentals (compare with PyTorch)
- [ ] Convolutional neural networks (CNNs)
- [ ] Recurrent neural networks (RNNs, LSTM, GRU)
- [ ] Transformers & attention mechanisms
  - Read "Attention Is All You Need" once I have the RNN/LSTM context to appreciate it
- [ ] Optimizers (SGD, Adam, learning rate schedules)
- [ ] Regularization (dropout, batch norm, weight decay)
- [ ] Transfer learning & fine-tuning
- [ ] Training on GPUs, mixed precision basics

## Natural Language Processing / LLMs

- [ ] Text preprocessing (tokenization, embeddings, stopwords)
- [ ] Word2Vec, GloVe — classic embedding methods
- [ ] Transformer architecture deep dive (attention, positional encoding)
- [ ] Pretraining vs. fine-tuning vs. prompting
- [ ] Large language models — how GPT/Claude-style models work at a high level
- [ ] Prompt engineering fundamentals
  - Practice: zero-shot vs few-shot vs chain-of-thought prompting, system vs user prompts
- [ ] Retrieval-augmented generation (RAG)
- [ ] Fine-tuning an LLM (LoRA / PEFT basics)
- [ ] Evaluation of generative models
- [ ] Hugging Face ecosystem (transformers, datasets, tokenizers)

## Computer Vision

- [ ] Image basics (pixels, color spaces, augmentation)
- [ ] Classic CV techniques (edge detection, filters) before deep CV
- [ ] Image classification with CNNs
- [ ] Object detection (YOLO, Faster R-CNN basics)
- [ ] Image segmentation
- [ ] Vision transformers (ViT)
- [ ] Generative image models (diffusion models, GANs) — at least conceptually

## MLOps & Deployment

- [ ] Model versioning & experiment tracking (MLflow, Weights & Biases)
- [ ] Packaging a model for serving (FastAPI, Flask)
- [ ] Containerizing with Docker
- [ ] Model monitoring & drift detection
- [ ] Basics of cloud ML platforms (AWS SageMaker / GCP Vertex AI / Azure ML — pick one)
- [ ] CI/CD for ML projects
- [ ] Vector databases for embeddings (Pinecone, Chroma, FAISS)
- [ ] Basic system design for ML-backed products

## Projects to Build

- [ ] Simple regression/classification project on a Kaggle dataset
- [ ] Image classifier from scratch (CNN)
- [ ] Sentiment analysis / text classifier
- [ ] A small RAG app over my own documents
- [ ] Fine-tune a small open-source LLM on a custom dataset
- [ ] End-to-end project: data → model → deployed API → simple frontend
- [ ] Kaggle competition (just to compete, not necessarily win)
- [ ] Recommender system (collaborative filtering or content-based)
- [ ] Time series forecasting project

## Resources & Books

- [ ] *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow* — Aurélien Géron
- [ ] *Deep Learning* — Goodfellow, Bengio, Courville
- [ ] fast.ai — Practical Deep Learning for Coders
- [ ] Andrew Ng's Machine Learning Specialization (Coursera)
- [ ] CS231n (Stanford, CNNs for visual recognition) — lecture notes/videos
- [ ] Hugging Face NLP course
- [ ] 3Blue1Brown neural network video series
- [ ] StatQuest (YouTube) for intuitive stats/ML explanations
- [ ] Papers With Code — for staying current on new research

## Communities & Datasets

- [ ] Join r/MachineLearning and r/learnmachinelearning
- [ ] Set up a Kaggle account and browse beginner-friendly datasets
- [ ] Follow a few ML practitioners/researchers for paper summaries
- [ ] Explore UCI Machine Learning Repository for classic datasets
- [ ] Bookmark Papers With Code's trending section

## Certifications to Consider

- [ ] Google TensorFlow Developer Certificate
- [ ] AWS Certified Machine Learning – Specialty
- [ ] DeepLearning.AI TensorFlow / NLP specializations
- [ ] Microsoft Certified: Azure AI Fundamentals (if I go the Azure route)

## Progress Log

Quick notes to self as I go — dated entries, most recent on top.

- **2026-08-29** — Repo created. Laid out the full roadmap across foundations, core ML, deep learning, NLP, CV, MLOps, projects, and resources. Starting point: comfortable with Python, need to build up math intuition and hands-on ML/DL practice.
