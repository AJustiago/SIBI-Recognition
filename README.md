# SIBI Rekognition

## Overview

This project implements a real-time SIBI (Indonesian Sign Language) recognition system using MediaPipe. It detects hand landmarks and recognizes SIBI signs based on trained machine learning models.

## Installation

To set up the required environment, follow these steps:

1. Clone this repository:

```bash
git clone https://github.com/your-username/sibi-rekognition.git
Gunakan kode dengan hati-hati. Pelajari lebih lanjut
```

2. Install dependencies:

```bash
pip install -r requirements.txt
Gunakan kode dengan hati-hati. Pelajari lebih lanjut
```

## Dataset

The dataset is from https://pmpk.kemdikbud.go.id/sibi/.

## Additional Information

Supported SIBI signs: A, B, C, D, E, F, G, H, I, **J NOT INCLUDE**, K, L, M, N, O, P, Q, R, S, T, U, V, X, Y, **Z NOT INCLUDE** 

Future work: 
- Add main.py to run the model
- Improve the Supported SIBI Signs such as **J** and **Z**
- Add Video Dataset and Recognize the sign is letter or word