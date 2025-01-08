# Gender Identification
Group Project for the Machine Learning 2023/2024 Course at PoliTo.
Mario Todaro, Vincenzo Dalia

# Project Description
This project focuses on developing a classifier to identify gender (male or female) from high-level features representing face images. Such tools can be applied, for example, as preprocessing for gender-dependent face recognition models.

The provided dataset consists of image embeddings: low-dimensional representations of face images mapped to a common manifold (typically a few hundred dimensions) using neural networks. For simplicity, synthetic data is used, and the embeddings have significantly lower dimensionality compared to real-world use cases.

# Dataset Details
Embeddings: Continuous-valued 12-dimensional vectors and have no physical interpretation. The data are unbalanced and the samples belong to three different age groups, each with distinct embedding distributions. However, age information is not provided.
Labels:
  0: Male
  1: Female

# Goals
The primary goal of this project is to analyze the dataset and develop a classification model capable of identifying gender based on embeddings representing face images. This involves studying the dataset's characteristics and comparing various classification techniques, including different models, hyperparameter values, and preprocessing strategies. The models are trained exclusively on the training set, with validation data extracted from it as needed.

Once a candidate model is selected, its performance is evaluated on the test set. This evaluation not only measures its effectiveness for the primary application but also examines how the model would perform in alternative scenarios. Finally, a post-evaluation analysis is conducted to compare the selected model with alternative solutions that were initially discarded. This ensures the chosen solution is optimal or close to optimal for the task.
