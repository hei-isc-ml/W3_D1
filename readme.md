# Week 3 - Halfday 1-2

## Missions & Activities:

### Activity 1
- **Problem**: Properly classify handwritten digits using Support Vector Machines (SVM).
- **Hints**:
    - Recycling: re-use & adapt the jupyter notebook you used in week 2. The ML pipelines is the same but:
        - Titanic dataset -> MNIST dataset
        - Random Forest -> Support Vector Machine
    - Utilize `from sklearn.datasets import load_digits` and `from sklearn.svm import SVC`.
- **Tools**: scikit-learn
- **New/Consolidation of ML Glossary**: Support Vector Machines (SVM)

## Expected Outcomes:
- **Halfday 1**:
    - Create 3-5 slides presenting SVM.
    - The content of your slides should enable you to answer the questions in the [Understanding SVM](#understanding-svm-provide-these-answers-in-the-slides) section below.
- **Halfday 2**: Develop a Jupyter notebook for proper classification of handwritten digits. In your notebook, systematically use markdown cells to:
    - Explain the goal of your code.
    - Comment on the results.
    - Provide direct answers to the questions listed below (Section [Implementing SVM-Based Classification](#implementing-svm-based-classification-provide-these-answers-in-the-jupyter-notebook)).

## Tasks – Classification using SVM

1. **Understanding SVM**:
   - Explain the following concepts: hyperplane of separation, soft margin, support vector, kernel (polynomial and RBF).
   - Understand and explain the kernel trick, why it a "trick", and why it's useful.
   - Discuss possible approaches for multiclass classification.

2. **Implementation of SVM**:
   - Explore the dataset.
   - Perform feature engineering/feature extraction. Consider which features represent images and whether you can create new meaningful features. Hint: test your algorithm with and without them.
   - Preprocess the data.
   - Implement classification and evaluate the results.
   - We provide a `.lock` and `.toml` file if you want to import the suggested packes with [poetry](https://python-poetry.org/docs/). Depending from your solution, you may need to [add](https://python-poetry.org/docs/cli/#add) additional packages.

## Questions:

### Understanding SVM (provide these answers in the slides)
- How does SVM select the best hyperplane of separation?
- SVM (without considering the kernel) has only one hyperparameter. What is its name, and what does it represent?
- Compare SVM vs. Random Forest: Discuss advantages and drawbacks in terms of interpretability, performance, data preparation, multiclass prediction, etc.

### Implementing SVM-Based Classification (provide these answers in the jupyter notebook)
- What types of features are present in the dataset?
- How are features correlated with each other?
- How are features correlated with the labels?