# Human Activity Recognition Final Project Python Analysis

Notebook : Human_Activity_Prediction_Jupyter.ipynb
Powerpoint : Human_Activity_Recognition_PowerPoint.pptx

Before you need to install the requirements (packages) from requirements.txt file in your python virtual environment

## Instructions :

- To use the model in Django API, just copy the saved model file and put it in DjangoRestML/models, in your case we generate model from .ipynb file named : best_model_svc
- Start the django server by entering the following command:
```python
python manage.py runserver
```
- Go to the follow url in your web brower : 
```html
http://127.0.0.1:8000/App/predict/
```
- Click on << Options >> button in blue
- Copy the the entry from api_test_xx file (your input should be in this format) and paste it into content box
- Click on post and you will see the predicted label on page.