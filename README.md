# Example Python Flask Crud

 This is A Simple example python flask crud app with sqlite forked from https://github.com/gurkanakdeniz/example-flask-crud
 It is using a simple CRUD to manage entries, with a sqlite db engine;
 
## Your Task
 Make this app more suitable for production;

 1. Replace the sqlite db with any of your choice
 2. Create an e-2-e test for the *Delete* and *Get* endpoints 
 3. Package the app to run with Docker (note 1)
 4. Create a basic CI/CD pipline of your choice that runs the tests on feature branches;

### Installing (for linux)

open the terminal and follow the white rabbit.


```
git clone https://github.com/gurkanakdeniz/example-flask-crud.git
```
```
cd example-flask-crud/
```
```
python3 -m venv venv
```
```
source venv/bin/activate
```
```
pip install --upgrade pip
```
```
pip install -r requirements.txt
```
```
export FLASK_APP=crudapp.py
```
```
flask db init
```
```
flask db migrate -m "entries table"
```
```
flask db upgrade
```
```
flask run
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
