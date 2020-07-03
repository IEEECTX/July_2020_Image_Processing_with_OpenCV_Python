

# Downloading Python 3.7 version of Anaconda and OpenCV
---

## Windows
```bash
md AnacondaBinary
cd  AnacondaBinary
wget https://repo.anaconda.com/archive/Anaconda3-2019.07-Windows-x86_64.exe
```

## Mac
```bash
mkdir AnacondaBinary
cd  AnacondaBinary
wget https://repo.anaconda.com/archive/Anaconda3-2019.07-MacOSX-x86_64.pkg
```


## Linux
```bash
mkdir AnacondaBinary
cd  AnacondaBinary
wget https://repo.anaconda.com/archive/Anaconda3-2019.07-Linux-x86_64.sh
```
Go to this link https://repo.anaconda.com/archive/ and search for the latest packges
Based on you operating system, after successful download, execute the binary and follow the instructions in the GUI.  


After you Anaconda installation ensure to update your packages
```bash
# First update conda package installer itself.
conda update conda -y

# Update all packages here.
conda update --all -y
```

# Jupyter Notebook
My preference for testing would be Jupyter Notebook
You can use **GUI** to open Jupyter Notebook or from the **command prompt** using the syntax below:
```bash
jupyter-notebook
```
<img src="Images/abc.png"
## Jupyter Notebook Browser
Jupyter Notebook Homepage <img src="../Images/Screen_Shot_2019-09-08_10.01.20_AM.png">


## Open a new Notebook
Click on the **New** drop down box and Choose **Python3**

New Jupyter Notebook <img src="../Images/Screen_Shot_2019-09-08_10.40.28_AM.png">


## Jupyter Notebook Editor

Jupyter Notebook <img src="../Images/Screen_Shot_2019-09-08_10.43.12_AM.png">

## Save your Notebook for later usage
Double click on the **Untitled** text beside the Jupyter Logo.
> By default auto save will be enabled

Saving Your Work <img src="../Images/Screen_Shot_2019-09-08_10.48.34_AM.png">

## Working with Notebook
Type in Python syntax and press ``` Shift Enter ```

Working with Notebook <img src="../Images/Screen_Shot_2019-09-08_10.51.09_AM.png">


For more details refer to 
[Jupyter Notebook Documentation](https://jupyter.readthedocs.io/en/latest/running.html)


# Installing OpenCV after the installation of Anaconda
---
Open a command prompt (for windows) or open a shell (Linux/MacOS)

```bash
  conda install -c conda-forge opencv
```

or if you wish to install a specific version follow the instructions below
```bash
  conda install -c conda-forge opencv=3.4.1
```





