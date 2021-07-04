# **CS5616 - Natural Language Processing - Assignment 4 - Text Classification

### **Author - KATS JAYATHILAKA (209338R)**

This repository is used to develop an implementation of text classification using available software tools for an assignment for the module of Natural Language Processing in MSc in Data Science, Analytics and Engineering, University of Moratuwa.

##

## **Instructions to run the code**

### <ins>1. Creating separate anaconda environment</ins>

It is better to have a separate conda environment with python3. Follow the instructions to run the code.

1. [Install Anaconda](https://www.anaconda.com/products/individual)
2. Make sure conda is automatically added to
   - Environment variables in Windows OR
   - System path in Linux (Ubuntu)
3. Anaconda will come with a base environment with preinstalled Python3.8. You can that default base environment by activating it as follows.
   - `conda activate`
4. Or else, you can create your own separate anaconda environment with just for testing this assignment and delete that environment later. My environment name was `python38test`.
   - `conda create -n yourenvname python=x.x anaconda`
5. To activate/deactivate your conda environment.
   - `conda activate yourenvname`
   - `conda deactivate`
6. ADDITIONAL STEP: To make sure Jupyter notebook and Ipykernel are installed in your conda environment.
   1. Check whether Jupyter notebok and Ipykernel
      - `conda list | grep notebook`
      - `conda list | grep ipykernel`
   2. If the above commands doesn't output anything to the terminal, install the packages as follows.
      - `conda install -c conda-forge notebook`
      - `conda install -c anaconda ipykernel`
7. Add your conda environment to jupyter notebook as a specific kernel as follows.
   - `python -m ipykernel install --user --name=yourenvname`
8. After finish grading the assignment, you can delete the conda environment you created if you want by the following command.
   - `conda remove -n yourenvname --all`
9. If you need any external assistance in conda environment setup, use this resource.
   - https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/

### <ins>2. Run</ins>

1. The code is already there in the uploaded submission just in case. But, it is better to get it cloned from the repository.
2. Clone the following git repo into your machine.
   - https://github.com/tsj1992/CS5616-NLP-A4.git
3. Activate your conda environment and navigate to inside the repository folder that you downloaded in the previous step. Then run jupyter notebook server.
   - `jupyter notebook`
4. After opening the assignment notebooks, remember to choose the kernel specified to your environment from the menu bar as follows
   - Kernel menu > Change kernel > yourenvname
5. Then go along with the instructions given in the notebook. There are some NLTK downloads that you need to do along the way. They are clearly mentioned in the notebook itself.
6. GOOD LUCK AND ENJOY !!!
