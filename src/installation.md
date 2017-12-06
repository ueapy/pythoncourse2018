# Installation instructions

**PAGE UNDER CONSTRUCTION!**

For this workshop you need to install Python on your laptop!

Follow the instructions below to set up your Python environment. The only requirement is that you have to do this **before** the course! Feel free to contact [Denis](mailto:d.sergeev@uea.ac.uk) if you have any problems with the installation (but better google them first!)

Note: **the course is designed in Python 3.6**, but for most cases will work in Python 3.5 too.

## 1. Install Python distribution using Anaconda
1.1 [Download Anaconda with Python 3.6 for your OS](https://www.anaconda.com/download/)
1.2 Make sure it works: type `python` in terminal (Linux / OSX) and make sure Python 3.6 prompt appears. On Windows open *Anaconda Prompt* in the start menu and check if runs without errors.

## 2. Download the course materials
### 2.1. Linux / OSX
Open terminal and type
```
git clone https://github.com/ueapy/pythoncourse2018-materials.git
```
```
cd pythoncourse2018-materials
```
```
conda env create -f environment.yml
```
This should create a new conda environment named "course2018".

If your default shell is NOT bash, first type `bash`. To activate or switch to your new conda environment, you should *activate* it from a command line:
```
source activate course2018
```
Note that a prefix will appear in the command line.

To deactivate the environment:
```
source deactivate
```

### 2.2 Windows
* Download and unzip the course content from [GitHub](https://github.com/ueapy/pythoncourse2018-materials/archive/master.zip).
* Open Anaconda prompt

Please stand by... More instructions to follow...


## Still having troubles?
If you are unable to install Anaconda Python 3.6 on your PC, contact the [course organisers](index.md#registration-and-enquiries).
Another option: launch the course in a cloud! [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/ueapy/pythoncourse2018-materials)
