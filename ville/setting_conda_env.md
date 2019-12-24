## Setting up conda environment for the course

### First build general development environment

As shown [here](https://github.com/NoobQuant/CheatSheets/blob/master/conda.txt).

### Install Stan

#### Python Stan

Install via conda:
```
conda install pystan
```

#### R Stan

conda install -c r r-rstan installs v2.17.3 and includes r-base downgrade. This is then not OK for StanHeaders which needs 3.6.2. Thus, install rstan via R.
```
install.packages("rstan", lib="C:/Users/ville_000/Documents/R/win-library/3.6", repos = "https://cloud.r-project.org/", dependencies = TRUE)
```

#### Install rethinking 

Rethinking package is not available via conda for Windows. Install via R:
```
install_github("rmcelreath/rethinking",ref="Experimental",lib="C:/Users/ville_000/Documents/R/win-library/3.6", dependencies = TRUE)
```

