# How to version control packets in python?

In a day, if you code a python version 2.9 project in the morning, you will have to maintenance a python version 3.2 project in the evening. So, how to code multiple python version on a computer????

## That is using a Virtual Environment (virtualen). It creates a folder containing everything your program needs.

## Usage:

### Step 1: Go to your project folder and open cmd.

### Step 2: Create virtual environment by command:

```bash
python -m venv 'NAME_VIRTUAL_ENVIRONMENT'
```

Ex: 'python -m venv project_flask_env'
or 'python -m venv helloworld'

### Step 3: Run enviroment:

```bash
venv\Scripts\activate
```
#### You can turn off by command:
```bash
venv\Scripts\deactivate
```

### Step 4: Now, you can install any version you need.

### Step 5: Export python version package so other computer know your project version package.

```bash
pip freeze > requirements.txt
```

## How to install package version python in other project.

### Step 1: Clone code project.

### Step 2: Go to this project

### Step 3: Create virtual environment by command:

```bash
python -m venv 'NAME_VIRTUAL_ENVIRONMENT'
```

Ex: 'python -m venv project_flask_env'
or 'python -m venv helloworld'

### Step 4: Run enviroment:

```bash
venv\Scripts\activate
```

### Step 5: Install everything package version in requirements file by command:

```bash
pip install -r requirements.txt
```
