# jump-simulation
## Experimental data
* test_data_markers: Experimental marker data
* jump_forces: Experimental ground reaction force
## Model
Scaled_Model: Model scaled by subject
## Folder
Results of CMC/FWD
## Setup_XX
Setup files of CMC/FWD/IK
## IK
* Result_IK: Desired motion calculated by IK
## CMC
* CMC_muscles_residuals_motor_control_limits: Contains limits on model actuators, which include muscles, reserve and residual actuators.(specifies the maximum and minimum excitation for each actuator)
* CMC_reserve_actuators: Contains the residual and reserve actuators
* CMC_tracking_tasks: specifying which coordinates to track and the corresponding tracking weight
## FWD
* jumper_FWD_initial_states: The initial state input to do FWD
