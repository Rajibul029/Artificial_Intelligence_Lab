# All Models

This folder contains the trained machine learning models developed for the college project.

## Available Models

| # | Model | Algorithm | Task | Dataset | Validation |
|---|---|---|---|---|---|
| 1 | Crop Recommendation | Random Forest Classifier | Multi-class Classification | Crop Recommendation Dataset | 5-Fold Stratified Cross-Validation |

---

## Crop Recommendation Model

The Crop Recommendation Model predicts a suitable crop based on soil nutrient and environmental conditions.

### Input Features

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- Soil pH
- Rainfall

### Output

- Recommended crop
- Class probability estimates

### Performance

The model was evaluated using **5-Fold Stratified Cross-Validation**.

- **Mean Accuracy:** 99.5455%
- **Standard Deviation:** 0.3214%

### Cross-Validation Scores

| Fold | Accuracy |
|---|---:|
| Fold 1 | 99.5455% |
| Fold 2 | 99.3182% |
| Fold 3 | 100.0000% |
| Fold 4 | 99.7727% |
| Fold 5 | 99.0909% |

---

## Model Package Structure

```text
crop_recommendation/
│
├── crop_model.pkl
├── label_encoder.pkl
├── feature_info.json
├── model_metrics.json
├── requirements.txt
├── requirements-full.txt
├── sample_input.json
├── input_schema.json
├── model_version.json
├── README.md
├── confusion_matrix.png
├── feature_importance.png
├── model_comparison.csv
├── classification_report.txt
└── cv_results.json
