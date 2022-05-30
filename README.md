# DjangoRestShop
RestfullApi to the "VueShop"

## Project setup
## Install Python.
## Install, create and activate Virtualenv in project folder.
```
pip install virtualenv
python3 -m venv venv
venv/scripts/activate
```
## or see: [https://docs.python.org/3/library/venv.html]

### Install project requirements.
```
pip install -r requirements.txt
```

### Start api surver: in djshop folder run:
```
python manage.py runserver
```

### For payments checkout, register and get "sk" from stripe.com, in settings.py apply "sk" to "STRIPE_SECRET_KEY ="
