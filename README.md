# Thai news headlines analysis for Google extension (Machine Learning part)

The machine learning model of Thai news headlines analysis for Google extension is developed using Python language for classify Thai news headline that is receive from the extension.

## Dataset
The dataset is in the format of a `.csv` file which contains two labels including `category` of the news headline and `texts` or the news headline content. The data were collected from Anti-Fake News Center Thailand.<br/>
<br/>Follow this link for more information about the dataset source: https://www.antifakenewscenter.com <br/>
<br/> In this project, a total of 2,570 news headlines were collected in this dataset.

## ML Models that are experimented in this project
* K Nearest Neighbor(k-NN)
* Support Vector Machine(SVM)
* Multinomial Naive Bayes(NB)
* XGBoost Random Forest(xgbRF)

## Installation
### Requriments ###
Note: if you prefer to use Google Colab you can skip the following steps.
* #### Use Python version 3.9.13 or newer version ####
* #### Create a virtual environment (recommend) ####
1. Open the terminal and change your directory (cd) into the the directory that you want to train the model
2. Create your Python3 virtual environment using this command:
```python
python3 -m venv [virtual environment name]
```
3. `Activate` the virtual environment by:
```python
source [virtual environment name]/bin/activate
```
4. Upgrade the version of virtual environment
```python
python3 pip install pip --upgrade
```
5. `Deactivate` the virtual environment after using it, enter this command in the terminal:
```python
deactivate
```
* #### Install the requirements of requriments.txt using this command in the terminal: ####
```python
pip install -r requirements.txt
```
* #### Additional: install missing Python package (not found) by using this command in the terminal: ####
```python
pip3 install [package name]
```

## Model training
The model training can be done by the following steps:
1. Open the Integrated Development Environment(IDE) that you prefer to use, Visual Studio Code or Google Colab is recommended.
2. Choose the model that you want to train, in this repository, the available models include:
* K Nearest Neighbor(k-NN)
* Support Vector Machine(SVM)
* Multinomial Naive Bayes(NB)
* XGBoost Random Forest(xgbRF)
3. Run the model code in the IDE and wait until the code is finished complied.
4. Once the code is finish complied, the output will be the pickle file `.pkl` of the model which is store in folder `pkl`.<br/>
5. (Additional) If you prefer to change the model parameters you can do it.

Note: you can use those `.pkl` for the classification in `extension.py`
You can follow this link for the extension part of this project: https://github.com/komcharn018/Thai-news-headlines-analysis-for-Google-extension_Extension
