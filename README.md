# hoiqel tomography env
Tomography measurement environment setup, of HoiQEL.

# requirements
1. Use windows >= 7 computer.
2. Have installed anaconda or miniconda on the computer.
3. Have installed git on the computer.

# setup the env
1. create a folder to be the tomography workspace.
2. put `auto_setup.bat` inside that folder and double click to run it.
3. download `exp_example.ipynb` and run it as testing.

# About `auto_setup.bat`
1. setup anaconda env named `tomography` if not exist.
2. git clone repo into current folder.
3. pip install modules, to the env.
> [!Tip]
> This batch file can be used multiple times. It will not create a new environment
> or install duplicate modules if the requirements are already satisfied.
> So every group member can create their own folder to be tomography workspace 
> and copy this batch file into it to setup the env.
