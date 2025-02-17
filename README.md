<h1>Spatio-Temporal SST Prediction Using ConvLSTM with Koopman Loss</h1>
<h3>Overview</h3>
This repository contains the implementation of a ConvLSTM-based model for predicting Sea Surface Temperature (SST) over a spatio-temporal domain. The project explores baseline models, a standard ConvLSTM architecture, and an enhanced ConvLSTM with Koopman-guided loss function to improve long-term prediction accuracy. It also includes comprehensive evaluations of the model's performance on the Gulf of Mexico and Nino 3.4 regions.

<h4>Features</h4>
<h6>Baseline Models: Includes Average and Persistence models for n-day predictions.</h6>
<h6>ConvLSTM Model: Captures spatial and temporal dependencies using convolutional layers and LSTMs.</h6>
<h6>Koopman-Guided Loss: Enhances predictions by incorporating a physics-inspired loss function.</h6>
<h6>Heatmaps and Visualizations: Tools for comparing model predictions against ground truth.</h6>
<h6>Flexible Dataset Handling: Supports predictions for specific regions of interest with global scaling.</h6>

<h4>Requirements</h4>
Python 3.8+<br>
PyTorch 2.0+<br>
NumPy<br>
Matplotlib<br>
Cartopy<br>
xarray<br>
Scipy
