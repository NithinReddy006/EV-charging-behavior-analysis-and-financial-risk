Kaggle EV Charging Dataset: Seven Research Question Notebooks

Dataset expected:
https://www.kaggle.com/datasets/nithinreddy600/ev-charging-behavior-analysis-and-financial-risk/data

How to use on Kaggle:
1. Open Kaggle.
2. Create a new notebook.
3. Add the dataset to the notebook using Add Data.
4. Upload/open one of these .ipynb notebooks.
5. Run all cells.
6. Outputs will be saved in /kaggle/working/<rq_folder>/.

Each notebook automatically searches /kaggle/input for a CSV/XLS/XLSX file.
If auto-detection does not find your dataset, set DATASET_PATH manually in the code cell.

Outputs:
RQ1:
- rq1_classification_performance/RQ1_classification_performance_table.csv
- rq1_classification_performance/RQ1_classification_performance_figure.pdf

RQ2:
- rq2_financial_predictors/RQ2_financial_predictors_odds_ratio_table.csv
- rq2_financial_predictors/RQ2_financial_predictors_forest_plot.pdf

RQ3:
- rq3_feature_block_ablation/RQ3_feature_block_ablation_table.csv
- rq3_feature_block_ablation/RQ3_feature_block_ablation_figure.pdf

RQ4:
- rq4_feature_importance/RQ4_feature_importance_table.csv
- rq4_feature_importance/RQ4_feature_importance_figure.pdf

RQ5:
- rq5_location_charger_status/RQ5_charging_location_status_table.csv
- rq5_location_charger_status/RQ5_charging_efficiency_by_location_status_figure.pdf

RQ6:
- rq6_user_segmentation/RQ6_cluster_selection_silhouette_table.csv
- rq6_user_segmentation/RQ6_user_segmentation_profile_table.csv
- rq6_user_segmentation/RQ6_cluster_assignments.csv
- rq6_user_segmentation/RQ6_default_risk_by_segment_figure.pdf

RQ7:
- rq7_charging_efficiency_regression/RQ7_regression_performance_table.csv
- rq7_charging_efficiency_regression/RQ7_regression_performance_figure.pdf

Note:
The notebooks compute actual results from the dataset that is attached in Kaggle.
They do not use dummy values.
