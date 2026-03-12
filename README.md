# hands-on_bayesian_inference

This repository contains lecture material on performing Bayesian inference using Bilby and stochastic sampling algorithms.

## Setting up

First we need to to create a conda environment and install all Python packages we need.

To check if conda is correctly installed type and launch this command line 

```
conda --help
```

  If you get a list of options, it means everything is set up for creating a conda environment and start working. 

```
conda create --name bayes_env python=3.11
conda activate bayes_env 
```

 We now connect this new conda environment to jupyter lab

```
conda install ipykernel
python -m ipykernel install --user --name=bayes_env --display-name "bayes_env"
```

and install [`bilby`](https://bilby-dev.github.io/bilby/installation.html), which is the Python library we will use for Bayesian inference:

```
conda install -c conda-forge bilby

```

We now need to clone the repository where all exercises are stored:

```
git clone https://github.com/filippo-santoliquido/hands-on_bayesian_inference.git
```

move into this new repository and open jupyter lab

```
cd hands-on_bayesian_inference
jupyter lab
```

Once jupyter lab opens in your web browser, select the conda environment we just created. Go on the top right corner and select bayes_env.

Open the jupyter notebook named `LinearInference.ipynb`



### Easter egg

Do you know what a Bilby is? 😃
