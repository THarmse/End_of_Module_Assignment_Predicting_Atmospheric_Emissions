# End_of_Module_Assignment_Predicting_Atmospheric_Emissions
CSCK503 Machine Learning in Practice - End Module Assignment

Data

https://data.london.gov.uk/download/london-atmospheric-emissions-inventory--laei--2019/17d21cd1-892e-4388-9fea-b48c1b61ee3c/LAEI-2019-Emissions-Summary-including-Forecast.zip

Models 

Ensure installation of python and run following
1. Python  (3.11 to be used)
2. python -m ensurepip --upgrade
3. pip install setuptools
4. python -m pip install --upgrade pip
5. pip install xlsxwriter


Setup code repo
1. Download Git LFS from the official site: https://git-lfs.com/
2. Run the installer.
3. After installation, open a new Command Prompt or PowerShell and run:
	1. git lfs install
4. Restart Visual Studio (or related application)


Data Processing
Execute:   pip install -r requirements.txt
pip install --upgrade pandas

Run Notebook

If issue running with error on openpyxl, open conda/miniconda and run
conda activate <environment_name>
conda install -c conda-forge openpyxl
then, restart kernel in jupyter notebook