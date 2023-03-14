# ML NOTES

## Create Jupyter Virtual Enviroment (Windows OS)
### Check python version (Terminal)
* Desktop\ml> python --version  

### Install jupyter ntebook (Terminal)
* Desktop\ml> pip install jupyter   

### Open jupyter notebook   (Terminal)
* Desktop\ml> jupyter notebook

### Python Virtual Enviroment for ML project    (Terminal)
* Desktop\ml> python -m venv venv1      (venv1 = Name of virtual enviroment)

### Activate Python virtual enviroment for ML Project   (Terminal)
* Desktop\ml> .\venv1\Scripts\activate

### ERROR: script is desable (Error during virtual enviroment activation)
* Set-ExecutionPolicy Unrestricted -Scope Process

### install ipykernel
* (venv1) PS C:\Users\asiddiqui\Desktop\ml> pip install ipykernel

### Give name to the kernel (with this name we find our kernel in jupyter notebook)
* (venv1) PS C:\Users\asiddiqui\Desktop\ml> ipython kernel install --user --name=venv1kernel


### numpy module install in Python virtul enviroment
* pip install numpy
### Check numpy module version
* pip show numpy


### numpy module install in Python virtul enviroment
* pip install numpy matplotlib
### Check numpy module version
* pip show matplotlib


### scipy module install in Python virtul enviroment
* pip install scipy


### pandas module install in Python virtul enviroment
* pip install pandas


### sklearn module install in Python virtul enviroment
* pip install sklearn
