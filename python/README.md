# Interact with TBV using the python Network Interface

This repository includes tutorials to showcase basic usage of the Turbo-BrainVoyager python network interface. Donwoload the code and follow the steps below to set up a python environment on your PC.

## 1. Set up a python environment

To set up a python enviroment to run the example pyhton script, first install miniconda. yYou can find the installer for Windows and MacOS at the following link:
https://www.anaconda.com/download/success?reg=skipped. After successfuly installation, open the miniconda prompt and create a python environment as follows:
```
cd /path_to_yml_file/
conda env create -f TBVworkshop2026_Win64_env.yml
```
## 2. Run example notebooks

After activating the newly created python environment, navigate to the code folder, run jupyter notebook and open the desired notebook.
```
conda activate TBVworkshop2026
cd /path_to_code/
jupyter notebook
```
## (Optional) Run example python code 

If you have troubles running the jupyter notebook, we have also provided the same code as simple python files. 
To run the python code, activate the newly created python environment, navigate to the code folder and run the desired code. The python code contains some embedded instruction to extend the excercises with additional tasks. If you don't have a python editor on your PC, *Sublime Text* might be a lightweight cross-platform solution for you: (https://www.sublimetext.com/). 
```
conda activate TBVworkshop2026
cd /path_to_code/
python 1-TBVPythonNetworkInterface-Basics.py
```
