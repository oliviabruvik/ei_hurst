# Simulation parameters for recurrent network model:

## Network size
size_factor = 100 # downscale the size of the network <br>
weight_factor = 100 # increase the synaptic weights to compensate it

## Simulation_params
"experiment_id": "Sim3", <br>
"simtime": 10000., <br>
"simstep": 0.1, <br>
"siminterval": 10000., <br>
"trials": 1, <br>
"num_threads": 15, <br>
"toMemory" : True,<br>
"decimate": False, <br>
"computeMP": False <br>

## External input rates
ext_rates = [2.0] # (spikes/s)

## g_ex and g_in
g_ex_range = np.linspace(0.625,2.0,num = 20) <br>
g_ex_range[6] = 1.0 <br>
g_in_range = np.linspace(0.5,1.6,num = 20) <br>
g_in_range[9] = 1.0
