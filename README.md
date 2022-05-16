# Demos-DREiMac

### Step 1: 
Get Python installed in your machine. I suggest using the latest Anaconda distribution: https://www.anaconda.com/products/distribution

### Step 2: 
Install the DREiMac library https://github.com/ctralie/DREiMac

We will first create and activate a separate conda environment for DREiMac, so that it does not conflict with any other packages in your Python installation. 
```
conda create -n dreimac python=3.8.3
conda activate dreimac
```
Now, to install DREiMac in this isolated environment, run
```
git clone https://github.com/ctralie/DREiMac.git
cd DREiMac
pip install cython
pip install -r requirements.txt
python setup.py install
```
