[![MLOPs Template](https://github.com/mohelwah/MLOps_template/actions/workflows/main.yml/badge.svg)](https://github.com/mohelwah/MLOps_template/actions/workflows/main.yml)

# Project Type: MLOps Template
# Project Name : Template
this is scaffold template for MLOps 
 Create the following:
 - Makefile
 - requirement.txt
 -Linux system:
    - virtial enviroment: python -m venv ~/.MLOps
    - activate venv envi: source ~/.MLOps/bin/activate
 - Windows system:
    - virtial enviroment: python -m venv c:\venv\MLOps
    - activate venv envi:   C:\venv\MLOps\Scripts\activate.ps1
 - hello.py file
 - test_hello.py file 
 - to check the python version:
    - in linux : which python  
    - in windows: Get-Command python | fl *
 - get pack version:
    - pip freeze | grep packName 
    test


## run jupyter notebook
  - jupyter noteboke: - install ipykernel
  - run command: - ipython kernel install --user --name=scrape
       
