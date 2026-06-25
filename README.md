# Football Match Outcome Prediction using Deep Learning

## Overview
This project focuses on predicting football match outcomes (home win, draw, away win) using Machine Learning and Deep Learning techniques.

The system combines:
- Historical match statistics
- Team and player performance data
- Sentiment analysis extracted from match reports

## Dataset
- ~17,000 matches
- Top 5 European leagues (2015–2024)
- ~250 features per match

## Models Evaluated
- Dense Neural Network (DNN)
- LSTM
- Transformer

## Results
- Best model: DNN
- Accuracy: 57%
- Main challenge: predicting draws (minority class)

## Key Insights
- Sequential models did not outperform tabular DNN
- Draw prediction remains the main bottleneck
- Combining quantitative + qualitative features improves performance

## Tech Stack
- Python
- TensorFlow / Keras
- Pandas / NumPy

## Paper
The full paper is available in the `/paper` folder.

## Notes
Code is not publicly available, but can be shared upon request.
