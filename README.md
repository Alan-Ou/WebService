## Requirements
- Python 3.6
- Django
- requests

Or install full requirements by running:
```bash
pip install -r requirements.txt
```
# Usage
- Enter client repository 
```bash 
cd users
```
 - Run the client 
```bash
python app.py
```
# Instruction  
<!--Nothing-->

| Command Syntax                                         | Description                                                                    |
|--------------------------------------------------------|--------------------------------------------------------------------------------|
| help                                                   | Show guidance to use this service                                              |
| register                                               | Register to the service                                                        |
| login *url*                                            | Log in to the service.                                                         |
| logout                                                 | Logout from the service                                                        |
| list                                                   | View a list of all module instances and the professor(s) teaching each of them |
| view                                                   | View the rating of all professors                                              |
| average *professor_code* *module_code*                 | View the average rating of a certain professor in a certain module             |
| rate *prof_code* *mod_code* *year* *semester* *rating* | Rate the teaching of a certain professor in a certain module instance          |
