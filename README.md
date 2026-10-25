# Data Analytics Learning Repository

This repository is a fork of [a-kravets/Data-Analytics-Projects](https://github.com/a-kravets/Data-Analytics-Projects). It contains upstream analytical exercises, machine-learning examples and course notebooks retained as learning references.

The examples show analytical approaches in code. Their presence here does not establish that I authored them, completed the exercises or reproduced their results.

## Attribution and contribution status

A repository audit on **25 October 2026**, before this README update, found:

- GitHub identifies this repository as a fork of `a-kravets/Data-Analytics-Projects`, created on 30 May 2024.
- The only branch was `master`, at [`f4abb96`](https://github.com/charbileigh/Data-Analytics-Projects/commit/f4abb96abbb5ad696cd324e7d7eed3a1d22ce2e5).
- All **185 reachable commits** were associated with GitHub author `a-kravets`. The history runs from 29 June 2020 to 15 September 2023.
- Comparison with upstream `master` returned **identical: 0 ahead, 0 behind**. All file paths and Git object hashes matched the upstream snapshot.
- No pull requests were present in this fork.

**Verified personal implementation contributions at that baseline: none identified in the available repository history.** Local practice or unpublished work cannot be established from this evidence. This audit does not assess my skills outside the repository.

This README update adds attribution, navigation and descriptions; it does not change the inherited analysis or models. Existing notebook outputs, results, first-person descriptions and dashboard links are upstream material. In particular, Tableau links under the Andriy Kravets profile are upstream demonstrations, not dashboards verified as mine.

The upstream repository is the immediate source of this fork, not necessarily the original source of every exercise. The TensorFlow folder explicitly identifies DeepLearning.AI/Coursera course material; other notebooks and documentation contain further dataset and learning references. Preserve those notices when adapting an exercise.

## Exercise index

All links below open material in **this fork**. The skills column describes the upstream code or documented learning topic, rather than verified personal proficiency.

| Exercise | Contents and technical topics |
| --- | --- |
| [Car Price Prediction](./Car%20Price%20Prediction/) | Notebook introducing car-price modelling without a specialised modelling library, with pandas/NumPy preparation and exploratory analysis. It references ML Bookcamp material. |
| [Churn Prediction](./Churn%20Prediction/) | Telco churn classification: categorical encoding with `DictVectorizer`, logistic regression, cross-validation, ROC AUC, model persistence, service scripts and a Dockerfile. |
| [Clothing Classification](./Clothing%20Classification/) | TensorFlow/Keras image-classification notebook, including image preprocessing and pretrained Xception examples. It references an external clothing dataset. |
| [Cohort Retention](./Cohort%20Retention/) | pandas date transformations, cohort indexing, grouping, pivot tables and retention heatmaps. The README describes a simulated trading-platform sample. |
| [Credit Risk Scoring](./Credit%20Risk%20Scoring/) | Decision trees, random forest and gradient boosting examples, plus a BentoML service and build configuration. Deployment files do not establish a running deployment. |
| [YouTube exploratory analysis](./Kaggle%20YouTube%20new/) | Exploration of category/country popularity and views, likes and dislikes using the Kaggle dataset linked in the folder README. |
| [Monthly Recurring Revenue and Churn](./Monthly%20Recurring%20Revenue%20%28MRR%29%20and%20Churn/) | Python notebooks for monthly/annual subscription revenue normalisation, churn definitions, tabular summaries and charts. |
| [Purchasing Likelihood](./Purchasing%20Likelihood/) | BigQuery SQL using joins, aggregation and window calculations for acquisition cohorts, repeat purchases and revenue. The inherited Tableau link belongs to the upstream author. |
| [Taxi Supply Data Analysis](./Taxi_SupplyDataAnalysis/) | Hourly supply/demand CSVs and a notebook exploring shortages, coverage and driver-earnings scenarios. Inherited recommendations and Tableau outputs have not been independently validated here. |
| [TensorFlow Developer Specialization](./TensorFlow%20Developer%20Specialization/) | DeepLearning.AI/Coursera labs and assignments covering neural networks, computer vision, NLP and time-series forecasting. These are course resources, not an independently authored application. |

## Reproducibility and interpretation

The audit inspected documentation, selected code/notebooks and Git history. It did **not** retrain models, run services or reproduce analytical results. Saved notebook outputs and model files are inherited artefacts.

Several examples depend on data or services outside this repository:

- Churn training expects `WA_Fn-UseC_-Telco-Customer-Churn.csv`, which is not included in the inspected tree.
- Cohort Retention reads a named CSV export that is not included in its folder.
- Purchasing Likelihood queries fixed BigQuery tables; access to those tables is not established by this fork.
- Model-serving examples require compatible dependencies and locally available trained models.

Treat business metrics and recommendations as exercise content until reproduced and checked. For example, the churn training script validates `C = 0.1` but fits the final model with `C = 1.0`; the output filename still uses the earlier value. This needs reconciliation before claiming a reproducible model result.

## Building verifiable portfolio evidence

A portfolio contribution should identify the source exercise, what was retained, the code or analysis newly developed, the decisions made, and results reproduced in a documented environment.

Keep original extensions separate from the retained exercises. Include data provenance and usage terms, setup instructions, tests, actual run evidence and commits showing the changes. Clearly label any generated data, guided work or assistance.

For a focused SQL/BI starting point, the [proposed Superstore warehouse extension](https://github.com/charbileigh/Data-Engineering-101#proposed-original-extension-superstore-sales-and-margin-reporting) in the companion repository provides a concrete scope. It is a proposal, not a completed personal project.
