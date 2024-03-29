# How to start with PIPNET dental
## 1. Clone the github repo
## 2. Create a virtual environment with python -m venv venv
## 2.1 Activate the virtual environment with source venv/bin/activate
## 3. Install the required packages with pip install -r requirements.txt
## 4. Create the folder "data-kaggle" in the root of the project
## 5 Create folder ".kaggle" in the root of your computer. Go to root through "cd /"
## 5.1 Create folder ".kaggle" with "mkdir .kaggle"
## 5.2 Create file  in root/.kaggle with touch kaggle.json
    open the kaggle.json file with "vi kaggle.json"
    add your api key in the file with the following format:
    {
        "username":"your_kaggle_username",
        "key":"your_kaggle_api_key"
    }
## 6. go the data folder in the project with "cd PIP-Net/data-kaggle"
## 4.1 Clone the dataset from Kaggle with : kaggle datasets download -d imtkaggleteam/dental-radiography
## 4.2 Unzip the dataset with: unzip dental-radiography.zip
