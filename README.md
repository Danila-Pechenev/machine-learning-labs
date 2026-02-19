# Machine Learning Labs – M1 Data Science, Centrale Lille

This repository collects my lab work from the **Machine Learning** course sequence in **M1 Data Science** (first year of the Master's program) at Centrale Lille (2025-2026).

The labs focus on hands-on implementation of classical machine learning, advanced supervised models, and deep learning. Many notebooks build algorithms from scratch first, then compare them with standard Python machine learning libraries.

---

## Course overview

| Course | Main focus | Labs |
| --- | --- | --- |
| **Machine Learning 1 – Fundamentals** | Core supervised and unsupervised learning methods | k-nearest neighbors, linear regression, gradient descent, regularization, clustering, PCA |
| **Machine Learning 2 – Advanced Models** | Model behavior, linear classifiers, margin methods, and ensembles | k-nearest neighbors regression, bias-variance analysis, perceptron, logistic regression, SVM, decision trees, bagging |
| **Machine Learning 3 – Deep Learning** | Neural networks and modern deep learning architectures | logistic regression with gradient descent, MLPs, backpropagation, CNNs, autoencoders, VAEs, RNNs, time-series forecasting |

---

## Repository structure

```
machine-learning-labs/
├── ml1_fundamentals/
│   ├── lab1_knn_classification/
│   ├── lab2_linear_regression/
│   ├── lab3_gradient_descent_regularization/
│   └── lab4_clustering/
├── ml2_advanced_models/
│   ├── lab1_knn_regression_bias_variance/
│   ├── lab2_linear_classifiers/
│   ├── lab3_support_vector_machines/
│   └── lab4_trees_ensemble_methods/
├── ml3_deep_learning/
│   ├── lab1_logistic_regression_gradient_descent/
│   ├── lab2_multilayer_perceptron_from_scratch/
│   ├── lab3_convolutional_neural_networks/
│   ├── lab4_autoencoders/
│   ├── lab5_variational_autoencoder/
│   └── lab6_recurrent_neural_networks/
├── README.md
└── requirements.txt
```

Each lab folder contains the completed Jupyter notebook(s), along with supporting datasets, images, or assignment PDFs when they were provided. Some later deep learning labs were distributed directly as notebooks, so the assignment prompts are preserved inside the notebooks themselves.

---

## Lab index

| Course | Folder | Contents |
| --- | --- | --- |
| ML1 | `lab1_knn_classification/` | K-nearest neighbors classification notebook |
| ML1 | `lab2_linear_regression/` | Linear regression and least-squares notebook |
| ML1 | `lab3_gradient_descent_regularization/` | Gradient descent, ridge regression, and Lasso notebook |
| ML1 | `lab4_clustering/` | K-means, agglomerative clustering, and PCA notebook |
| ML2 | `lab1_knn_regression_bias_variance/` | KNN regression notebook, train/test CSV files, and data-generation helper |
| ML2 | `lab2_linear_classifiers/` | Perceptron and logistic regression notebook, CSV datasets, and supporting images |
| ML2 | `lab3_support_vector_machines/` | SVM notebook and CSV datasets |
| ML2 | `lab4_trees_ensemble_methods/` | Decision trees and bagging notebook with CSV datasets |
| ML3 | `lab1_logistic_regression_gradient_descent/` | Logistic regression with gradient descent notebook and assignment PDF |
| ML3 | `lab2_multilayer_perceptron_from_scratch/` | MLP and backpropagation notebook and assignment PDF |
| ML3 | `lab3_convolutional_neural_networks/` | CNNs for image classification notebook |
| ML3 | `lab4_autoencoders/` | Autoencoders on simulated data and MNIST notebooks |
| ML3 | `lab5_variational_autoencoder/` | Variational autoencoder notebook |
| ML3 | `lab6_recurrent_neural_networks/` | RNN learning-recursion and time-series forecasting notebooks |

---

## Technologies

- Python
- NumPy, Pandas, SciPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook / JupyterLab
- PyTorch, torchvision, PyTorch Lightning

---

## Skills demonstrated

- Implementing machine learning algorithms from scratch
- Training, validating, and comparing supervised learning models
- Applying regularization and optimization methods
- Performing clustering and dimensionality reduction
- Building neural networks with manual and framework-based backpropagation
- Training CNNs for image classification
- Building autoencoders and variational autoencoders for representation learning
- Modeling sequential data with recurrent neural networks
- Maintaining reproducible notebook-based experimental workflows

---

## Author

Danila Pechenev

M1 Data Science – Centrale Lille
