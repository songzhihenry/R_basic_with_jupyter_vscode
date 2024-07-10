# R Programming with VSCode and Jupyter

## Introduction
Welcome to the repository, designed for basic R programming using VSCode along with its Jupyter Notebook extension. This combination offers a streamlined and informative environment for learning and executing R code, making it easier to follow along and understand the process step-by-step. The basic R programming materials are from [R Programming Tutorial](https://www.youtube.com/watch?v=_V8eKsto3Ug).

## Getting Started
First of all, **R** should be installed beforehand, depending on which operating system you are working on.   
Next, **VSCode** and **Jupyter Extension** are expected to be ready since R programming with **VSCode** is not recommended if you don't work on it in your routine.  
Additionally, **Anaconda** is expected to be installed since prevalent applications such as Jupyter and Python are commonly associated with **Anaconda**.
The following instructions are based on a combination of [R in Visual Studio Code](https://code.visualstudio.com/docs/languages/r) and [Using R in a Jupyter Notebook](https://izoda.github.io/site/anaconda/r-jupyter-notebook/). 
To begin exploring R programming with VSCode and Jupyter, follow these simple steps:

1. **Install necessary R package in your R Console:**
```bash
install.packages("languageserver")
```

2. **Install R Extension in Vscode:** Open VSCode, go to the Extensions view, and search for "R". Install the extension on the top search.

After the R extension installation, you can reopen your VSCode and try to open and run an R script to check if VSCode can properly execute the R kernel.

3. **Setup conda environment:** Creat a specific conda environment if you need to. Otherwise, skip to step 4.
```bash
conda create -n r-kernel
conda activate r-kernel
```
4. **Install R kernel in conda:**
```bash
conda install r-recommended r-irkernel
```
You should be able to run R in VSCode with Jupyter extension. Please make sure to select the R kernel when executing cells. 

