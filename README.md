# Q24 - food manager
This application can help you to handle some problems that often arise in everyone's live. 
The main point is to help you to understand which products need to be used as soon as possible  

## Instalation

First, don't forget to create a virtual environment
```bash
python -m venv venv
```

Second, activate the venv
```bash
venv\Scripts\activate
```

The following command will install the packages according to the configuration file
```bash
pip install -r reqiueremnts.txt
```

## Configration
Configurational values are made as environmental variables.
Create the .env file in the root directory and write the appropriate configurations in it. You can find the required variables in the config.py file. 

## Database
DB will be empty so you can fullfill it by your data using PgAdmin. For a correct work of the app you will need to have some data in 'products' and 'categories' tables.

## https://q24.herokuapp.com/ 
Here you can check the deployed version of this app.
