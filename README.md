# Welcome to Microblog!

## Setup
Install Python version 3.5 or above and run:
```bash
$ python -m venv venv
```
activate your brand new virtual environment you use the following command:
```bash
$ source venv/bin/activate
(venv) $ _
```
If you are using a Microsoft Windows command prompt window, use this activation command instead:
```bash
$ venv\Scripts\activate
(venv) $ _
```
Afterwards, ensure you have the latest pip version installed in your virtual environment by running: 
```bash
(venv) $ python -m pip install --upgrade pip
```
You can now install the app's dependencies by running:
```bash
(venv) $ python -m pip install -r requirements.txt
```

## Running Tests

To run the unit tests succesfully, first make sure you have redis installed and running on port `6379` (check how to [here](https://redis.io/topics/quickstart)). Enter the following command in your terminal to run the app's unit tests
```bash
(venv) $ python tests.py
```