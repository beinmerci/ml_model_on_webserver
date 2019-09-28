# Exposing your machine learning model on webserver 

1. Using Flask : On Development/Test Server
Exposing your data science application using Flask (Flask includes a very simple built-in web server, which is good enough for development and testing environmnet)

2. Using Flask with Waitress : On Production Server
Exposing your data science application using Flask with Waitress (If you want to run Flask in production, be sure to use a production-ready web server and let your app be handled by a WSGI application server like Gunicorn (UNIX), Waitress(Windows). In this project we are using Waitress )

Steps:
1. Assumed model to predict hand written digit is already created and saved i.e. model1.pkl
2. Creat a template for loading image of hand written digit and displaying predicted result. Template(index.html) is placed in templates    folder
3. Place test images in test-imgs folder
4. Place 2_apponflask.ipynb and run this file . It generates URL http://localhost:80/
   OR
4. Place 3_apponflaskwithwaitress and run this file .It generates URL i.e. http://DESKTOP-RV05O09:8000
5  Access URL
5. Choose File/Image to be predicted
6. Click Predict to get result

    
