# GlobeCom-Airy
Dataset and pre-trained neural network parameters for Airy beam optimization, GlobeCom 2024.

A dataset containing true optimal Airy parameters is saved in training.csv.
Each data point is in the format of {O_x, O_y, d_x, d_y, R_x, R_y, bl, \Delta_y, B, \Delta_f, \Delta_\theta}, where the first 8 numbers abstract the wireless environment and the last 3 numbers are the true optimal Airy beam parameters, acquired through brute force simulations.

Pre-trained neural network model parameters are saved in model.keras, load using tf.keras.models.load_model().

Processing, neural network architecture, and training hyperparameters can be found in the notebook file training.ipynb.
