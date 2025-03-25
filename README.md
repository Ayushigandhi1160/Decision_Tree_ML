# Understanding Decision Trees and the Role of Pruning

This repository provides a complete tutorial on how Decision Trees can be optimized using pruning techniques. The focus is on comparing **pre-pruning** (early stopping) and **post-pruning** (cost-complexity pruning) using real-world data. Visualizations, accuracy metrics, and theory are included to help learners understand the trade-offs in model complexity.

## Contents

- decision_tree_pruning_tutorial.ipynb : Main notebook with code, explanations, and plots
- README.md : Project overview and setup guide
- requirements.txt : Python dependencies for this tutorial
- tutorial.docx / tutorial.pdf : Full written report (optional academic submission)
- LICENSE : (optional) License file for open-source distribution

## Dataset

We use the Breast Cancer Wisconsin dataset from scikit-learn. It includes 30 numeric features describing tumor characteristics and a binary classification target (`benign` or `malignant`).

## Learning Objectives

- Understand Decision Tree structure and overfitting
- Apply pre-pruning techniques (`max_depth`, `min_samples_leaf`)
- Use cost-complexity pruning (post-pruning) to simplify trees
- Compare unpruned, pre-pruned, and post-pruned models
- Visualize trees and interpret their structure

## How to Run

1. Clone this repository:
```
git clone https://github.com/Ayushigadhi1160/decision-tree-pruning.git
cd decision-tree-pruning
```

2. Install the required packages:
```
pip install -r requirements.txt
```

3. Launch the notebook:
```
jupyter notebook decision_tree_pruning_tutorial.ipynb
```

---

## Accessibility Features

- Markdown cells written in full sentences with clear headings
- All visuals labeled with titles and axis descriptions
- Colorblind-friendly palettes and contrast
- Logical code structure and semantic layout
- Compatible with screen readers and academic formatting tools

---

## GitHub Submission Instructions

Include the following in your report when submitting the assignment:

```
GitHub Repository:
https://github.com/Ayushigandhi1160/decision-tree-pruning
```

Ensure that your repository contains:
- A complete notebook (.ipynb)
- A `README.md` with project info and usage instructions
- A `requirements.txt` file for reproducibility
- A `.docx` or `.pdf` report (if required)
- A license file (if public distribution is intended)

---

## Acknowledgements

- Breast Cancer dataset from UCI via scikit-learn
- Tree visualization using `sklearn.tree.plot_tree`
- Inspired by academic work from Breiman et al. (1984), Quinlan (1986), and Pedregosa et al. (2011)
