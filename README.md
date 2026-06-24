# Multiclass Hate Speech Recognition using SentimentFormer

This repository contains our implementation and analysis of multimodal sentiment classification on the MemoSen dataset based on the SentimentFormer research paper.

## Project Overview

The project explores sentiment analysis of memes using:

- SwiftFormer (Image Encoder)
- mBERT (Text Encoder)
- Intermediate Fusion
- MemoSen Dataset

The goal is to classify memes into:

- Positive
- Negative
- Neutral

by jointly analyzing the meme image and its associated text.

## Repository Structure

```text
multiclass-hate-speech/
│
├── dataset/
│   └── Dataset/
│       ├── Memes/
│       └── multi-sent.xlsx
│
├── main/
│   └── memosen-swift-mbert-intermediate-fusion.ipynb
│
└── working/
```

Download the dataset from:

https://github.com/eftekhar-hossain/MemoSen
