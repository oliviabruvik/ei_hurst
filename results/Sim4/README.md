# Simulation parameters for recurrent network model:

## Network size
size_factor = 100 # downscale the size of the network <br>
weight_factor = 100 # increase the synaptic weights to compensate it

## Simulation_params
"experiment_id": "Sim4", <br>
"simtime": 200000., <br>
"simstep": 0.1, <br>
"siminterval": 200000., <br>
"trials": 1, <br>
"num_threads": 15, <br>
"toMemory" : True,<br>
"decimate": False, <br>
"computeMP": False <br>

## External input rates
ext_rates = [2.0] # (spikes/s)

## g_ex and g_in
g_ex_range = [1.78289473684, 1.20394736842, 0.842105263158, 2.8] <br>
g_in_range = [1.0] <br>
