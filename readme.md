# Flask RESTful API 

This is a simple RESTful API developed using the Flask web framework.

* Users can register and authorize themselves in order to:
* Create/Read/Update/Delete stores
* Create/Read/Update/Delete items that belong to a store.

## Install guide

##### Clone the repo

```bash
$ git clone https://github.com/Emircan92/stores-rest-api.git
$ cd stores-rest-api
```

##### Create the virtualenv and activate it
```bash
$ python3 -m venv venv
$ . venv/bin/activate
```

##### Or on Windows cmd::
```bash
$ py -3 -m venv venv
$ venv\Scripts\activate.bat
```

##### Install dependencies
```bash
$ pip install -r requirements.txt
```

##### Run the app
```bash
$ python app.py
```
