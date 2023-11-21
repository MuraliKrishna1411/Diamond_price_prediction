# this is my end to end project

# first initialize the git

```
git init
```

```
git add abc.txt
git add .
```
```
git commit -m "this is my first commit"
```

```

git pull

```

```
bash your_file_name.sh
```

```
python setup.py install
```

# another way you can mention -e . in your requirement file and you can run

```
pip install -r requirements.txt
```

# we cannot push the empty folder in github, so we use .gitkeep - in futrure if we may use this folder but now it is empty

.gitignore file will ignore files which we list in the gitignore file

# utils.py

helper module, open any file or any other details using utils file


# logger file

This will provide detils regarding when file is logged or when, it will provide time when data extracted, ingested
everything

exception file

If any exception has occured when file is running or using code, we can easily navigate that code and check the details

# Proceedure to run all the Model

## First use git bash as terminal

## second run below command to create env and install the requirement

```
bash init_setup.sh
```

## third  -  if virtual environment is created but did'nt get activated then use

```
source activate ./env
```

## fourth - after activating environment, check using pip list, whether local package directory and modules are intalled
## if not the use

```
python setup.py install
```

# additonal step which missed - creating all folders which are required, which was already listed in template.py file
# we need to execute template.py file to generate all the folder

```
python template.py
```

## fifth -  after intallation of packages or modules - if you have build the model from data ingestion to model training
## then all necessary commands to execute the model will be avialable in training_pipeline, to check the training_pipeline or run the training_pipeline

```
python src/DimondPricePrediction/pipelines/training_pipeline.py
```


## Generally above above / will be like \, we need to change every where and to run the previous executed code of line in bash use

```
clt + p
```

## above short cut will provide last execute line of code


# Process
## 1 Data ingestion
## 2 EDA - Exploratory data analysis
## 3 FE  - Feature Engineering
## 4 Model Building
## 5 Evaluation
#1