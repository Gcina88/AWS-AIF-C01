# Introduction to Basic AI and ML concepts

Define 
- Artificial Intelligence: enabling computers to mimic human intelligence
- Machine Learning: enabling computers to learn on their own using data
- Deep Learning: using neural networks and deep layers to learn without intervention
- Generative AI: generating new content to expand the input data

## Traditional Programming vs AI
TP is rule-based, deterministic (output is always predictable) e.g. password verification and transparent logic.
AI is data-driven (based on evaluating historical data), adaptable (new patterns and trends over time) and less transparent - evolution of AI might be less clear.

## How do machines learn?
LLMs are trained on large amounts of data. They use deep learning techiniques (e.g. transformers) to analyse language patterns and predict word sequences (inferencing).


### Model Fit Patterns
**Model Fit** refers to how well a model has learned and how accurately it can make predictions on new, unseen data.

Underfitting a model - the model doesn't learn enough from the training set thus performs poorly on both training and test data. Too simplistic. 
Overfitting a model - model learns the data too well including the noise thus perfomrs well on training data but poorly on unseen data. Too complex.
Balanced model - model is complex enough to learn from the training data without been so complex that it overfits. Need to avoid an unfair model (avoid bias - historical or algorithmic bias).

## Different way machines learn
**Supervised learning** - models receive inputs/features and targets/labels during training, and models can then be able to predict future outputs.
**Unsupervised learning** - models categorise data based on similar features. No labels are provided.
**Semi-supervised learning** - models receive a mix of partially label data.
**Self-supervised learning** - models given random features and generates its own labels.
**Reinforcement learning** - models attempt solving problem/learning through interactions and receives feedback (e.g. rewards or penalties) and adjust accordingly to find the best outcomes. Learning from successes and mistakes.

### Types of Supervised Learning

1. Classification
   - Multi-class e.g. [cow, dog, cat]; [house, condo, townhome];[shark, seaweed, coral].
   - Binary e.g [yes, no]; [fraud, not fraud].
2. Regression
   - uses continuous values e.g. stock market, house prices.
  
### Types of Unsupervised Learning

1. Clustering - groups data into clustering based on similar features e.g. patient responses to treatment, similar lifestyles.
2. Anomaly Detection - finds outliers in data e.g. network traffic, heart-rate.

## Types of Data in AI Models
1. Structured data is easy to understand
   - tabular e.g. rows and columns
   - time-series data

2. Unstructured data is harder to analyze and doesn't have a clear structure
   - Text
   - Images and videos
   - Audio

