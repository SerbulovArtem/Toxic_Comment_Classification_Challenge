# Main Steps of the project:

## 1: Data Augmentation, particularly back translation (from English to German and vice versa)

## 2: Train the Base Model (RoBERTa)

## 3: Pseudo-Labeling

## 4: Train the Ensemble Model (Using LightGBM)

## 5: Evaluate and Save the Ensemble Model:

# Some help for installation

## Docker Miniforge3 installation:

Make sure you did these steps:

1. Installed docker

2. docker login (you need to sign up in docker hub)

3. Installed the NVIDIA Container Toolkit

## Mamba(Conda) envs:

To get mamba env:

1. mamba env export > environment.yml\
or
2. mamba list --export > requirements.txt

To install mamba env:
My mamba env is base, take that in mind:
1. mamba env create -f environment.yml\
or
2. mamba create --name <env> --file requirements.txt