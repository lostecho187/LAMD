# LAMD
## How to run the code
### Create folders
create *data, log, results, saved_checkpoints, saved_models under* LAMD folder
run the following command if you are using Linux:

  mkdir data, log, results, saved_checkpoints, saved_models

### Preprocess the data
paste auth dataset in *data* folder, then run:

  python utils/preprocess_data.py --data auth

### Start training

  python train_self_supervised.py --data auth

check the results in *log, results, saved_checkpoints, saved_models under* 
