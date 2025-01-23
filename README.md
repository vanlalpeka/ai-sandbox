# Introduction
This repository is a work-in-progress. The notebooks are used to explore different methods for interpretable AI, and will be updated as I learn more about the topic.

### Table of Contents
- [Interpretable AI](#interpretable-ai)
- [Notebooks](#notebooks)
- [References](#references)

# Interpretable AI
Interpretable AI is a subfield of AI that focuses on making AI models more interpretable. This is important for a number of reasons, including:
- Understanding how the model makes predictions
- Debugging the model
- Ensuring that the model is fair and unbiased
- Building trust with users
- Complying with regulations

There are a number of methods for making AI models more interpretable. Some of these methods include:
- Feature importance
- Partial dependence plots
- Shapley values
- LIME
- Rule-based models
- Surrogate models
- And many more

# Notebooks
The following notebooks are available in this repository:
<!-- - [Feature Importance](feature_importance.ipynb) -->
- [Partial Dependence Plots](PDP/partial_dependence_plots.ipynb)
<!-- - [Shapley Values](shapley_values.ipynb) -->
- [LIME](LIME/LIME.ipynb)
- [SHAP (SHapley Additive exPlanations)](SHAP/SHAP.ipynb)
- [Counterfactual](counterfactual/counterfactual.ipynb)
<!-- - [Rule-based Models](rule_based_models.ipynb)
- [Surrogate Models](surrogate_models.ipynb) -->

# References
- [Interpretable Machine Learning, Christoph Molnar](https://christophm.github.io/interpretable-ml-book/)
- LIME ["Why Should I Trust You?": Explaining the Predictions of Any Classifier, Marco Tulio Ribeiro, Sameer Singh, Carlos Guestrin, 2016](https://doi.org/10.48550/arXiv.1602.04938)
- SHAP (SHapley Additive exPlanations) ["A Unified Approach to Interpreting Model Predictions" Lundberg et al., 2017](https://proceedings.neurips.cc/paper_files/paper/2017/file/8a20a8621978632d76c43dfd28b67767-Paper.pdf)
- Counterfactual ["Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR", Wachter et. al., 2017](https://arxiv.org/pdf/1711.00399)
- Evaluating LIME and SHAP using Counterfactuals["Towards Unifying Feature Attribution and Counterfactual Explanations: Different Means to the Same End", Mothilal et. al., 2021](https://arxiv.org/pdf/2011.04917)
