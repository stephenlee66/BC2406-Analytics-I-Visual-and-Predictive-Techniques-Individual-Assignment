# 📝 Individual Assignment: Misinformation Detection

## 🎯 Objective
Develop and evaluate predictive models to identify and classify misinformation in digital content.

## 📊 Results

#### 📈 Logistic Regression

**Confusion Matrix**

|                | Predicted Positive | Predicted Negative |
|----------------|------------------|------------------|
| Actual Positive | 74 (TP)          | 6 (FN)           |
| Actual Negative | 6 (FP)           | 64 (TN)          |

**Performance Metrics**

| Metric        | Value  |
|--------------|--------|
| Accuracy     | 92.0%  |
| Precision    | 92.5%  |
| Recall       | 92.5%  |
| Specificity  | 91.4%  |

#### 🌳 CART (Decision Tree)

**Confusion Matrix**

|                | Predicted Positive | Predicted Negative |
|----------------|------------------|------------------|
| Actual Positive | 80 (TP)          | 0 (FN)           |
| Actual Negative | 8 (FP)           | 62 (TN)          |

**Performance Metrics**

| Metric        | Value  |
|--------------|--------|
| Accuracy     | 94.7%  |
| Precision    | 90.9%  |
| Recall       | 100.0% |
| Specificity  | 88.6%  |

## 🔬 Model Comparison

The CART model outperforms Logistic Regression in recall, achieving perfect detection of misinformation (100% recall), making it more suitable for risk-averse classification scenarios. Logistic Regression performs well overall but slightly underestimates positive cases compared to CART.
