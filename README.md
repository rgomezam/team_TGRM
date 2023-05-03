# TGRM team 

to the rescue 

Kaggle project:
https://www.kaggle.com/competitions/store-sales-time-series-forecasting


Time-series course:
https://www.kaggle.com/learn/time-series


Kaggle API (to download and submit from local) - I havent tried it yet (R):
https://github.com/Kaggle/kaggle-api

`conda install -n <env_name> -c conda-forge kaggle`

need to create an API token from your kaggle account:
https://www.kaggle.com/settings/account



# create a conda environment from file
(all this can also be done from the interface of anaconda navigator or similar programmes, maybe from VScode?)

`conda env create -f environment.yml`

`conda activate myenv`

once you have installed everything you want in the environment you can also use `conda env export > environment_droplet.yml` to export it to a yml file for the future (or other people) and then update your environment with `conda env update --file local.yml --prune`  (not sure you really need the `prune`)