# More on Machine Learning & Deep Learning

Find more of my deep learning models on the following links:

- [Car Detection](https://github.com/Rakib1508/car-detection)
- [Emoji Generator](https://github.com/Rakib1508/emojify)
- [Face Recognition](https://github.com/Rakib1508/face-recognition)
- [Machine Translation](https://github.com/Rakib1508/machine-translation)
- [Neural Style Transfer](https://github.com/Rakib1508/neural-style-transfer)
- [Trigger Word Detection](https://github.com/Rakib1508/trigger-word-detection)
- [Word Vector Representation](https://github.com/Rakib1508/word-vector-representation)

More ML/DL models in the following links:

- [Fundamental Machine Learning Models](https://github.com/Rakib1508/ml-projects)
- [Machine Learning with MatLab](https://github.com/Rakib1508/Machine-Learning)

# Deep Learning (DL)

This repository consists a collection of simple Deep Neural Network models I developed with Python and Jupyter Notebook. My other more advanced deep learning models can be found in different other repositories on my [Github Repositories](https://github.com/Rakib1508?tab=repositories). I have used Jupyter notebook to build the models for the most part, but some contains additional python files to provide supporting functions to keep the notebook more organized.

The Python machine learning ecosystem has grown exponentially in the past few years, and is still gaining momentum. Developing my [ML Projects](https://github.com/Rakib1508/ml-projects), I got to learn about ML/DL implementation using Python, and decided to build some simple neural network models. Those models are collected in this repository together.

For this project, I have used:

- Jupyter notebook to train and develop the actual model.
- Python codes to write supporting functions for the model.
- Datasets for different models have been collected from different sources.

## Downloading the Assignments

To get started, you can start by either downloading a zip file of these assignments by clicking on the `Clone or download` button. If you have `git` installed on your system, you can clone this repository using :

    git clone https://github.com/Rakib1508/dl-projects.git

Each project is contained in a separate folder, and each root level folder has been named according to the model or tools that has been focused in the notebook. Each project contains:

- Necessary `jupyter` notebooks, which have `.ipynb` extensions. All the code which you need to write will be written within this notebook.
- In some cases, a `~utils.py` and `tests.py` files containing additional python functions.
- Datasets used to build that model. Depending on the projects, the train and test sets can be separate as well.
- Figures used in the notebook are saved in a folder named `images` in most of the projects.

## Requirements

These assignments has been tested and developed using the following libraries:

    - python==3.9.4
    - numpy==1.20.0
    - scipy==1.6.3
    - matplotlib==3.4.2
    - jupyter==6.4.0
    - jupyter-client==6.1.12

We recommend using at least these versions of the required libraries or later. Python 2 is not supported.

## Python Installation

We highly recommend using anaconda for installing python. [Click here](https://www.anaconda.com/download/) to go to Anaconda's download page. Make sure to download Python 3.9 version.
If you are on a windows machine:

- Open the executable after download is complete and follow instructions.
- Once installation is complete, open `Anaconda prompt` from the start menu. This will open a terminal with python enabled.

If you are on a linux machine:

- Open a terminal and navigate to the directory where Anaconda was downloaded.
- Change the permission to the downloaded file so that it can be executed. So if the downloaded file name is `Anaconda3-5.1.0-Linux-x86_64.sh`, then use the following command:

  `chmod a+x Anaconda3-5.1.0-Linux-x86_64.sh`

- Now, run the installation script using `./Anaconda3-5.1.0-Linux-x86_64.sh`, and follow installation instructions in the terminal.

Once you have installed python, create a new python environment will all the requirements using the following command:

    conda env create -f environment.yml

After the new environment is setup, activate it using (windows)

    activate machine_learning

or if you are on a linux machine

    source activate machine_learning

Now we have our python environment all set up, we can start working on the assignments. To do so, navigate to the directory where the assignments were installed, and launch the jupyter notebook from the terminal using the command

    jupyter notebook

This should automatically open a tab in the default browser. To start with a project, open the notebook `./"project-name"/"notebook-name".ipynb`.
