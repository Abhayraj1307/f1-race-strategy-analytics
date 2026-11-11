# Formula 1 | Race Strategy Analytics

Stevens team project analyzing how lap pace and overtaking relate to finishing position in the 2024 Formula 1 season.

## Archived team results

| Evaluation | Result |
| --- | --- |
| First finishing-tier classifier | 77% accuracy; 0.75 macro F1; 137 evaluation observations |
| Second finishing-tier classifier | 79% accuracy; 0.70 macro F1; 137 observations |
| Exploratory K-means analysis | Three driver behavior clusters |

The results measure finishing-tier classification. The features use observed race information, so the evaluation does not establish pre-race forecasting accuracy, pit or tire prediction accuracy, or performance in another season.

Open the [team notebook](notebooks/team-race-analysis.ipynb) and [earlier analysis](notebooks/earlier-analysis.ipynb) in Jupyter. Update the notebook paths and supply the original merged race workbook separately.
