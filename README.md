# Final Project Scripts - SYS819

Note: The scripts used in this project are only designed to work with GPUs if Apple Silicon is present.

## Virtual environment

Use `conda` to create new virtual environment:

```
conda create --name sys819_project
```

Activate virtual environment:

```
conda activate sys819_project
```

Install Python at version 3.12 to ensure compability with Pytorch libraries:

```
conda install python=3.12
```

Next, install Pythorch libraries:

```
pip install torch torchvision
```

Then install timm (library that has various pre-trained models):

```
pip install timm
```

Then install `matplotlib` to plot graphs:

```
pip install matplotlib
```

## Hyperparameter tuning script

You can run the Python file `train_hyperparameter_tuning.py` under the virtual environment by making sure the environment is active and then:

```
python train_hyperparameter_tuning.py --model tiny_vit_21m_224
```

To find a set of optiomal hyperparameters for TinyViT-21M, or:

```
python train.py --model resnet34d
```

To find a set of optiomal hyperparameters for ResNet-34.

## Train script setup

You can run the Python file `train.py` under the virtual environment by making sure the environment is active and then:

```
python train.py --model tiny_vit_21m_224
```

To train TinyViT-21M, or:

```
python train.py --model resnet34d
```

To train ResNet-34.

## Plot script setup

You can run the Python file `train_plots.py` under the virtual environment by making sure the environment is active and then:

```
python train_plots.py
```
