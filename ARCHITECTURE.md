# System Architecture

## Architecture Diagram

```
Historical Forex Dataset
            │
            ▼
    Data Preprocessing
            │
            ▼
   Feature Engineering
            │
            ▼
      Feature Scaling
            │
            ▼
   Machine Learning Models
      ├── ELM
      ├── BPNN
      └── FLANN
            │
            ▼
        Prediction
            │
            ▼
     Performance Metrics
            │
            ▼
      Visualization
```

---

## Components

### Dataset

Historical exchange rate data collected for EUR/USD and GBP/USD.

### Data Preprocessing

Cleaning missing values and preparing the dataset for analysis.

### Feature Engineering

Generation of technical indicators to improve predictive performance.

### Feature Scaling

Normalization of features before training.

### Machine Learning

Multiple prediction models are trained and compared.

### Evaluation

Performance measured using Mean Squared Error (MSE).

### Visualization

Prediction graphs and comparison charts are generated.

---

## Design Principles

- Modular pipeline
- Reproducible workflow
- Feature-driven learning
- Comparative model evaluation
