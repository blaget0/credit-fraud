Models used: Isolation Forest, DBSCAN, Autoencoder, Variational Autoencoder (VAE), Generative Adversarial Network (GAN).

Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

All models are trained on unlabeled data. Isolation Forest and DBSCAN use built in anomaly detection capabilities, Autoencoder and VAE detect anomalies based on high reconstruction error, GAN detects anomalies based on output class probabilities from a trained discriminator.
