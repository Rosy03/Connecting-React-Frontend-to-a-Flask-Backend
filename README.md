# Requirements ,Usage and Installation
## Backend - Flask
### Installation
                    
### 1 .Clone the git repo and create an environment 
          
Depending on your operating system,make a virtual environment to avoid messing with your machine's primary dependencies
          
**Windows**
          
```bash
git clone https://github.com/Dev-Elie/Connecting-React-Frontend-to-a-Flask-Backend.git
cd Connecting-React-Frontend-to-a-Flask-Backend/backend
py -3 -m venv venv
```
          
**macOS/Linux**
          
```bash
git clone https://github.com/Dev-Elie/Connecting-React-Frontend-to-a-Flask-Backend.git
cd Connecting-React-Frontend-to-a-Flask-Backend/backend
python3 -m venv venv
```

### 2 .Activate the environment
          
**Windows** 

```venv\Scripts\activate```
          
**macOS/Linux**

```. venv/bin/activate```
or
```source venv/bin/activate```

### 3 .Install the requirements

Applies for windows/macOS/Linux

```pip install -r requirements.txt```
### 4 .Migrate/Create a database - Optional during initial set up

Applies for windows/macOS/Linux

```python manage.py```

### 5. Run the application 

**For linux and macOS**
Make the run file executable by running the code

```chmod 777 run```

Then start the application by executing the run file

```./run```

**On windows**
```
set FLASK_APP=main
flask run
```
OR 
`python routes.py`

## Frontend - React
### Installation

This section involves creating of a new react app and then replacing the contents with that of the previous folder "frontend"
into the newly created react app

> You can manoeuvre around this in any way you find suitable provided you have a react app with the node modules and contents from the previous frontend folder

```
cd Connecting-React-Frontend-to-a-Flask-Backend/backend
npx create-react-app front-end
cd front-end
```
Copy the contents of the other folder,replace the existing ones

`npm start`

