# Installation instructions

For this workshop you need to install Python on your laptop!

Follow the instructions below to set up your Python environment. The only requirement is that you have to do this **before** the course! Feel free to contact [Denis](mailto:d.sergeev@uea.ac.uk) if you have any problems with the installation (but better google them first!)

Note: **the course is designed in Python 3.6**, but for most cases will work in Python 3.5 too.

## 1. Install Python distribution using Anaconda
1.1. [Download Anaconda with Python 3.6 for your OS](https://www.anaconda.com/download/)

1.2. Install it following [these instructions](https://docs.anaconda.com/anaconda/install/)

## 2. Download course materials
The material for the workshop can be cloned from our [GitHub repository](https://github.com/ueapy/pythoncourse2018-materials) or can be directly downloaded as a [zip file](https://github.com/ueapy/pythoncourse2018-materials/archive/master.zip).

### Option 1: Using Git
#### 2.1. Install Git
If you don't have git version control system installed, you can install it following these instructions:
##### Linux
Use your package manager. For example, using aptitude you would run the following terminal command: `sudo apt-get install git`
##### Mac
* The XCode command line tools need to be installed.
* Install XCode if it isn’t already. XCode is available in the Mac App Store for free.
* Launch XCode and accept the license agreement.
* Quit XCode.
* Open a new terminal and run the command xcode-select --install
* Select install on the pop-up menu.
##### Windows
Download and install the [GitHub desktop tools](https://desktop.github.com/).

##### 2.2. Clone the repository
2.2.1. Open the command line (terminal or cmd.exe)
2.2.2. (Optional) Change to a suitable directory (e.g. `C:\Users\myname\Downloads`)
2.2.3. Clone the repo by typing
```
git clone https://github.com/ueapy/pythoncourse2018-materials.git
```
This should create a local copy of the course materials in the current directory.

### Option 2: Download ZIP file
Download the materials as a [zip file](https://github.com/ueapy/pythoncourse2018-materials/archive/master.zip) and unpack it in a suitable directory, for example, in `Downloads` folder.


## 3. Create the environment
3.1. Make sure Anaconda is installed and the course materials are downloaded

3.2. Open the command line (e.g., OS X terminal on Mac, cmd.exe on Windows)

3.3. Navigate to the cloned / downloaded folder (using `cd` command), for example:

```
cd C:\Users\myname\Downloads\pythoncourse2018-materials\
```

3.4. Create the environment using `conda` package manager:

```bash
conda env create -f environment.yml
```
This will take some time depending on your Internet speed (<15 minutes).

## 4. Activate the environment
### Linux / Mac
If your default shell is NOT bash, first type `bash`. Activate the relevant environment by typing:
```bash
source activate course2018
```
### Windows
Still in the command line (cmd.exe), type:
```
activate course2018
```

## 5. Launch Jupyter
Once the environment is activated, type 
```
jupyter notebook
```
in the command line. This should open Jupyter Notebook in your browser. 

## Still having troubles?
If you are unable to install Anaconda Python 3.6 on your PC, contact the [course organisers](index.md#registration-and-enquiries).
Another option: launch the course in a cloud! [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/ueapy/pythoncourse2018-materials)
