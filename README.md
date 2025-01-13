## 🌟 Overview
This project is a **toxicity prediction tool** built using [DeepChem](https://deepchem.io/), an open-source toolkit for deep learning in chemistry, biology, 
and materials science. It uses the **Tox21 dataset**, a benchmark dataset for chemical compound toxicity classification, to predict the potential toxicity of chemical compounds.

## 📚 What is Toxicity Prediction?

Toxicity prediction involves determining whether a chemical compound can have harmful effects on human health or the environment. It is crucial for drug discovery, regulatory compliance, and environmental protection.

The Tox21 dataset includes information on **12 different toxic effects**, such as:

- Nuclear receptor signaling pathways
- Stress response pathways

## ⚙️ Features of the Project

- **Multitask Classification:** The model predicts toxicity across 12 classes simultaneously.
- **ROC AUC Metrics:** Evaluates model performance using the ROC AUC score.
- **DeepChem Integration:** Leverages DeepChem's functionality to simplify dataset handling, model training, and evaluation.

## 🚀 How It Works

1. **Dataset:** The Tox21 dataset, which includes chemical features (`X`) and toxicity labels (`y`).
2. **Model Architecture:** A fully connected neural network (Multitask Classifier) with two hidden layers.
3. **Performance Evaluation:** The ROC AUC score indicates the model's ability to distinguish between toxic and non-toxic compounds.

  
## 📖 What is DeepChem?  
DeepChem is a machine learning library tailored for scientific problems in:  
* Drug Discovery
* Material Science
* Bioinformatics

## 🤝 Contributing
Contributions are welcome! If you'd like to improve the model or add features, feel free to fork the repository and submit a pull request.

## 🌐 References
- [DeepChem Documentation](https://deepchem.readthedocs.io/en/latest/)
- [Tox21 Dataset information](https://tox21.gov/resources/)
- [ROC AUC Metrics](https://scikit-learn.org/1.5/modules/generated/sklearn.metrics.roc_auc_score.html)

