# LAMD
## How to run the code
### Create folders
Create *data, log, results, saved_checkpoints, saved_models under* LAMD folder.
Run the following command if you are using Linux:

    mkdir data, log, results, saved_checkpoints, saved_models

### Preprocess the data
Paste auth dataset in *data* folder, then run:

    python utils/preprocess_data.py --data auth

### Start training

    python train_self_supervised.py --data auth

Check the results in *log, results, saved_checkpoints, saved_models under* 

## Experimental data and results

Check (https://github.com/lostecho187/Experiments)
