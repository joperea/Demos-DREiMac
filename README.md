# Demos-DREiMac

### Step 1: 
Get Python installed in your machine. I suggest using the latest Anaconda distribution: https://www.anaconda.com/products/distribution

### Step 2: 
We will first create and activate a separate conda environment for DREiMac, so that it does not conflict with any other packages in your Python installation. **Open a terminal (Linux/mac) | an Anaconda Powsershell Prompt (Windows)** and run
```
conda create -n dreimac python=3.8
```
```
conda activate dreimac
```
Next, we install the needed dependencies by running
```
pip install cython numba persim ripser jupyter screeninfo opencv-python plotly
```
Now, to install DREiMac in this isolated environment, run
```
git clone https://github.com/ctralie/DREiMac.git
cd DREiMac
python setup.py install
cd ..
```

### Step 3: 
Get the jupyter notebooks for the DREiMac demos:
```
git clone https://github.com/joperea/Demos-DREiMac.git
cd Demos-DREiMac/Demos
jupyter notebook
```

