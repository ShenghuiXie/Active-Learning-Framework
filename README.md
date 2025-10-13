# A Wasserstein Autoencoder-Physical Feature Interaction Active Learning Framework for Enhancing Piezocatalytic Performance
The main content consists of nine code files and two datasets.
**Feature.ipynb** contains feature data analysis used to select the optimal feature combinations.
**WAE.ipynb** is the core framework file, primarily responsible for latent space generation and sampling. It includes steps such as Wasserstein Autoencoder, Gaussian Mixture Model clustering, Monte Carlo sampling, and classifier training.
**t-SNE.ipynb** is used to assess the similarity between the original data and the data reconstructed by the WAE model.
**SHAP-BT.ipynb** is used to calculate the SHAP values of the elements.
**NN.ipynb**, **GBDT.ipynb**, **SVR.ipynb**, and **RF.ipynb** are four training and prediction models. Using the original datasets in combination with Bayesian optimization, these four models are trained to find their optimal hyperparameters.
**Resemble module.ipynb** integrates NN and GBDT, using the best-trained models from the previous steps to predict the sampling results.
![figure](https://github.com/ShenghuiXie/image/blob/main/Active%20Learning%20Framework.png)
