# Model Performance Evaluation using TOPSIS

This project demonstrates how to evaluate and rank different machine learning models based on multiple performance criteria using the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** method. The models are assessed on the following criteria:

- **Accuracy**
- **Precision**
- **Recall**
- **Inference Time**

TOPSIS is a multi-criteria decision-making method that ranks alternatives by considering both the ideal and the worst-case scenario in relation to the given criteria.

## Models Compared

The following models are evaluated in this project:

- GPT-3
- T5
- ELECTRA
- ERNIE
- DeBERTa

## Key Steps

1. **Data Preparation**: The performance data for each model is provided in terms of Accuracy, Precision, Recall, and Inference Time.
2. **Normalization**: The data is normalized to bring all the metrics to a comparable scale.
3. **Weighted Scoring**: Each criterion is assigned a weight according to its importance.
4. **Ideal and Worst Scenarios**: The ideal and worst performance scenarios are calculated for each criterion.
5. **TOPSIS Calculation**: Using the Euclidean distance to the ideal best and worst case, the TOPSIS score for each model is computed.
6. **Ranking**: Models are ranked based on their TOPSIS score, with the highest score being the best.

## Requirements

- Python 3.x
- `numpy`
- `pandas`
- `matplotlib`

You can install the required packages using `pip`:

```bash
pip install numpy pandas matplotlib
