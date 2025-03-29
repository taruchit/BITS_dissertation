# To Establish Baseline for Threat Detection

**1. Objective: -** To build binary and multi-class classifiers for differentiation between benign and malicious events, and type of malicious events over a large and imbalanced cybersecurity dataset.

**2. Feature selection: -** Nature inspired Heuristic alhgorithms were used
<br />
  2.1 Artificial Bee Colony optimization (ABC)
<br />
  2.2 Flower Pollination Algorithm (FPA)

**3. Machine Learning algorithm: -** KNN (K Nearest Neighbor)
   
**4. Objective function for feature selection: -** Recall - Penalty
<br />
  Recall: To maximize True positives and minimize False negatives
<br />
  Penalty: To reduce the number of features obtained out of feature selection

**5. Evaluation: -** 13 metrics were used to evaluate performance of classifiers

**6. Dataset: -** CIC dataset (Canada Institute of Cybersecurity)

**7. Scaling approaches: -** Two independent methods were used
<br />
   7.1 Standard Scaler
<br />
   7.2 Robust Scaler

**8. Results: -**
<br />
   8.1 When number of generations=5, models trained using FPA performed better than ABC.
<br />
   8.2 When number of generations=100, models trained using ABC performed better than FPA.
<br />
   8.3 Models trained with Standard scaler performed better than the models trained with Robust Scaler, irrespective of feature selection method and the number of generations.
