

# WEAKLY-SUPERVISED NEURAL NETWORKS FOR IMAGE SEGMENTATION

---

## Overview

This project explores the development of **weakly-supervised neural networks for image segmentation**, aiming to achieve strong segmentation performance with minimal annotation effort.

We implement and evaluate both a **baseline model** and an **improved model**, supported by systematic experimentation and analysis.

### Key Contributions

* Engineered a **weakly-supervised segmentation model** using PyTorch and TensorFlow to reduce dependency on fully labeled data.
* Conducted **comparative experiments and ablation studies** to identify performance improvements.
* Achieved **enhanced segmentation results** with reduced labeling requirements.
* Delivered **data-driven insights** through statistical evaluation and model performance metrics.

---

## Requirements

Ensure that Python is installed on your system.

* Python version: **3.9 or higher**
* Dependencies are automatically installed via the main script

---

## Folder Structure

```
|-- additionals
|   └── Contains all additional experiments conducted
|
|-- weakly_supervised_segmentation_baseline
|   └── Baseline model used for experiments
|
|-- weakly_supervised_segmentation_improved_model
|   └── Improved model developed through experimentation
|
|-- run_all_code.py
|   └── Script to automate experiment execution and setup
|
|-- instruction.pdf
|   └── Coursework instructions (PDF)
|
|-- report.pdf
|   └── Individual written report (methodology, experiments, results, and conclusions)
```

---

## Running the Experiments

Execute the following command to run all experiments:

```bash
python3 run_all_code.py
```

### This script will:

* Install all required libraries
* Run the **baseline segmentation model**
* Run the **improved segmentation model**
* Execute additional experiments and analyses

---

## Methodology

The project follows a structured experimental workflow:

### 1. Baseline Model

* Implementation of a weakly-supervised segmentation approach
* Establishment of benchmark performance

### 2. Model Improvements

* Architectural refinements and training optimizations
* Integration of insights from initial experiments

### 3. Ablation Studies

* Systematic removal or modification of components
* Evaluation of their impact on performance

### 4. Evaluation

* Use of segmentation metrics (e.g., IoU, accuracy)
* Statistical comparison between baseline and improved models

---

## Results

* The improved model achieves **higher segmentation performance** compared to the baseline
* Demonstrates **effective learning with limited annotations**
* Provides **insight into efficient weakly-supervised learning strategies**

---

## Contributions

* **Team Contribution:**

  * Development and implementation of baseline and improved models
  * Experimental setup and execution

* **Individual Contribution:**

  * Authored the complete written report (`report.pdf`), including:

    * Methodology
    * Experimental design
    * Results and analysis
    * Conclusions

---

## Notes

* The project is fully reproducible using `run_all_code.py`

---

## Authors

Applied Deep Learning Group 10 Team
