# Advanced Machine Learning

## Classification of Toxic Online Comments

- Luca Gandolfi 807485
- Stefano Sacco 807532

### Introduction
In this project we have developed a toxic comments classifier according to 3 different approaches. The dataset refers to a *Kaggle competition* and it's available at this link 
[https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data](url).

### Approaches
In order to obtain semantic meaningful text representation, two different approaches have been used: (1) Word Embedding sentences vectorization using pre-trained GloVe and (2) Feature Extraction from BERT base_uncased model. In particular, we provide 3 different notebooks:
1. A simple Deep Neural Network with pre-processing steps and GloVe embeddings
2. A simple Deep Neural Netowrk with Data Augmentation for 2 toxic categories
3. An Hyperparameters-optimized Deep Neural Netowk with BERT's sentence encoding vectors

### Instructions
To run the notebooks we suggest you to create a virtual environment:
> python3 -m virtualenv ~/aml_venv

Then, clone our repository where you like and run:
> source/aml_venv/bin/activate
> ipython kernel install --user --name=aml_venv

We are installing a jupyter kernel inside the venv. Now move to the git repository:
> cd progetto_aml
> pip3 install -r requirements.txt

We are installing the dependencies needed. Now we are ready to run jupyter:
> jupyter notebook

When you open a notebook now, change the kernel in:
> kernel > change kernel > aml_venv

You are now ready to run our notebooks.

### Order of execution
If you want to reproduce our work, just follow the numeration in the notebooks' name.
