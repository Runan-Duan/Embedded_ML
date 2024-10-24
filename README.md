# Embedded_ML
This repository contains regular exercises from the Embedded Machine Learning course given by Holger Fröning, University of Heidelberg.



### Installation

#### Get the Package

You need go to the Gitlab repository:https://github.com/Runan-Duan/Embedded_ML.git to get the source package.

```
git clone https://github.com/Runan-Duan/Embedded_ML.git
```

#### Install Dependencies

All required packages are contained in the **environment.yml** file, you can install the Python environment on your computer

```
conda env create -f environment.yml
```

#### Activate the environment

The environment name is **eml**, you can activate this environment to execute the main script.

```
conda activate eml
```

For development and further contributions, please use pre-commit hooks
and the configuration file named  **.pre-commit-config.yaml** is in the root of the repository.

```
pre-commit install
```
