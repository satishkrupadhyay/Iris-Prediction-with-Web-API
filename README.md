# Iris-Prediction-with-Web-API

This is a sample model to demonstrate how a Machine Learning model can be implemented in Production as a API and how it can be consumed.

Here I have used very famous Iris Dataset and Scikit Learn (Support Vector Machine Algorithm) to predict species of Iris(Iris  Setosa, Iris Virginica and Iris Versicolor.

I have used Flask (Flask is a microframework for Python) to create and use the API. For more details you can check the below link:
http://flask.pocoo.org/docs/1.0/quickstart/#quickstart

The pickle module implements binary protocols for serializing and de-serializing a Python object structure. For more details check the below link:
https://docs.python.org/3.7/library/pickle.html#module-pickle

# Steps:

1. Install Flask using Pip or conda.

2. Create Iris_Prediction_model.py file and import all library in to your current notebook.

3. Write code for your choice of model and dataset.

4. Run the notebook file(code), it will create a Pickle file and will be stored in models directory.

5. Create another file server.py and import Flask and other library.
   This code will run the app and provide and API to predict the species.

6. Run the code server.py, Server will start on port number 5000 (by default) and respective link will be displayed in the comand prompt.

7. Jupm to the Web brouser and type the URL along with the arguments.
    URL:  http://127.0.0.1:5000/predict?sepal_length=6.0&sepal_width=2.5&petal_length=5.5&petal_width=0

8. Output will be desplayed in to the browser with predicted value.
   Output:  Predicted Iris Class: 2
   
   # Great!!!
   So now we have our model runing on local server, we can use the API along with arguments and get the prediction.
   We can also create a simple form in HTML and required field with textbox and then submit our request.
