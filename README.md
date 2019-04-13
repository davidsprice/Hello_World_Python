# Hello_World_Python
Standard Hello World program in Python, using Github

## Target :
Learning how to use Python in a Github environment.

## Problem Type :
Very rudimentary effort.

# Project Instructions
1. Clone the repository and navigate to the downloaded folder.

~~~~
git clone https://github.com/davidsprice/Hello_World_Python
cd hello_world_python
~~~~

2. Create and activate a new environment.

~~~~
conda create -n helloworlpython python=3.6 matplotlib numpy pandas keras-gpu
source activate helloworldpython
~~~~

3. Create an [IPython kernel](https://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the helloworldpython environment.

~~~~
python -m ipykernel install --user --name helloworldpython --display-name "helloworldpython"
~~~~

4. Open the notebook.

~~~~
jupyter notebook Hello_World_Python.ipynb
~~~~

5. Before running code, change the kernel to match the quadcop environment by using the drop-down menu (Kernel > Change kernel > quadcop). Then, follow the instructions in the notebook.

6. You will likely need to install more pip packages to complete this project. Please curate the list of packages needed to run your project in the requirements.txt file in the repository.
