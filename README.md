# CMPE 255 - Assignment 3

This repository contains the completed notebooks and video walkthroughs for Assignment 3.

The notebooks are based on the provided reference Colabs and have been executed and validated in my own environment. Where an original notebook required a compatibility fix to run successfully, changes were kept minimal so the original workflow and learning objectives remained intact.

## Repository Structure

```text
.
├── README.md
└── notebooks/
    ├── 01_kmeans_and_variations.ipynb
    ├── 02_autogluon_capabilities_tour.ipynb
    ├── 03_autogluon_end_to_end_ml.ipynb
    ├── 04_rapids_gpu_vs_cpu.ipynb
    ├── 05_pycaret_capabilities_tour.ipynb
    └── 06_pycaret_mlops_end_to_end.ipynb
```

## Notebooks and Video Walkthroughs

| # | Topic | Notebook | Video Walkthrough |
|---|---|---|---|
| 01 | K-Means and Variations | [01_kmeans_and_variations.ipynb](notebooks/01_kmeans_and_variations.ipynb) | https://www.youtube.com/watch?v=dfyV5QU8w90 |
| 02 | AutoGluon Capabilities Tour | [02_autogluon_capabilities_tour.ipynb](notebooks/02_autogluon_capabilities_tour.ipynb) | [YouTube Video](YOUTUBE_LINK_02) |
| 03 | AutoGluon End-to-End ML and Metrics | [03_autogluon_end_to_end_ml.ipynb](notebooks/03_autogluon_end_to_end_ml.ipynb) | [YouTube Video](YOUTUBE_LINK_03) |
| 04 | NVIDIA RAPIDS - GPU vs CPU | [04_rapids_gpu_vs_cpu.ipynb](notebooks/04_rapids_gpu_vs_cpu.ipynb) | [YouTube Video](YOUTUBE_LINK_04) |
| 05 | PyCaret Capabilities Tour | [05_pycaret_capabilities_tour.ipynb](notebooks/05_pycaret_capabilities_tour.ipynb) | [YouTube Video](YOUTUBE_LINK_05) |
| 06 | PyCaret MLOps End-to-End | [06_pycaret_mlops_end_to_end.ipynb](notebooks/06_pycaret_mlops_end_to_end.ipynb) | [YouTube Video](YOUTUBE_LINK_06) |

## Topics Covered

### 01 - K-Means and Variations

K-means fundamentals, initialization strategies, clustering variants, evaluation methods, failure cases, and practical applications.

### 02 - AutoGluon Capabilities Tour

A tour of AutoGluon's machine-learning capabilities across different prediction tasks and data modalities.

### 03 - AutoGluon End-to-End ML and Metrics

An end-to-end AutoGluon workflow with emphasis on model evaluation, metrics, validation, calibration, and interpretation.

### 04 - NVIDIA RAPIDS: GPU vs CPU

Comparison of CPU and GPU implementations using RAPIDS, including data processing, machine learning, clustering, graph operations, and performance benchmarking.

### 05 - PyCaret Capabilities Tour

A broad tour of PyCaret across classification, regression, clustering, anomaly detection, time-series forecasting, interpretability, and related workflows.

### 06 - PyCaret MLOps End-to-End

An end-to-end PyCaret workflow covering model development and MLOps concepts including deployment, tracking, monitoring, drift, and model lifecycle operations.

## Running the Notebooks

The notebooks are stored with their execution outputs in the `notebooks/` directory.

Some notebooks require different Python and package environments because their dependency stacks are not fully compatible with one another. GPU support is also required for the RAPIDS notebook.

The notebook setup and dependency requirements are documented within the notebooks themselves.

For the submitted work, notebooks 03, 04 and 05 was run in my own environment and checked for successful execution while preserving the structure and intent of the provided reference notebook. The rest are (01, 02 and 03) executed in Colab.

## Video Walkthroughs

Each video walks through the corresponding notebook and explains the important code, outputs, experiments, and takeaways.

The final YouTube links are listed in the table above.
