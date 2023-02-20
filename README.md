# Flask-basic
This is flask starter template with one blueprint registered (main). Environment variables are in separate file(.env). Config variables are loaded using python-dotenv which is recommended way. Application factorie is used, you can have multiple instances of the same application running in the same application process.

### How to use it:

- git clone https://github.com/kummicko/Flask-basic.git
- folder with name Flask-git will be created
- from your terminal run: cd Flask-basic or rename folder name and cd into it
- create virtual enviroment
- activate it
- create file .env in the project root and add these three lines inside, this file is not on repo so as virtual environment, SECRET_KEY should consist letters, numbers and special characters, longer the better - this way no need to export variables to run flask application

```sh
FLASK_APP=run.py  
FLASK_DEBUG=1   
SECRET_KEY='*******************************'
```

- pip install -r requirements.txt
- flask run
