# GNN-RNN-Based-Trajectory-Prediction-ITSC2021
This repo contains the code for the paper 'Graph and Recurrent Neural Network-based Vehicle Trajectory Prediction For Highway Driving' at ITSC-2021.
## Data Pre-processing
Select the vehicles which have change their lanes only once through out the study area.

`python once_lc_veh_selector.py`

Preprocess data for the single trajectory prediction task.

`python stp_data_pre.py`

### Models
The proposed two channel model with GNN & RNN is implemented in:

`stp_gr_model.py`

The proposed interaction-only one channel model is implemented in:

`stp_g_model.py`

The proposed dynamics-only one channel model is implemented in:

`stp_r_model.py`
