# System_performance_tracker
System performance tracker using PyQt5 for the UI and python source code. SQL Database is used and is compatible with Linux and Microsoft OS.
# SYSTEM PERFORMANCE TRACKER
It is a Python based application to track the system functionalities in Real-Time.
I have used PyQt5 widgets and Qtdesigner produced .ui files for the User Interface. 
![image](https://user-images.githubusercontent.com/89335295/210090582-3357db62-4f5f-4c04-973d-bbf1d5ec0795.png)
I have used SQL to store login details.
## Dependancies
Many python libraries must be installed.
You can use pip or if your using an Anaconda Enivronment u can use "conda install" statements.
I prefer you use this command line 
```bash
python -m pip install "name of library"
```
**THE LIST OF LIBRARIES:**
```python
speedtest-cli
GPUtil
shutil
pyside2
psutil
datetime
platform
```
In SQL youll have to run the following commands to set-up the database.

**its quite simple:**
```bash
create database se;
use se;
create table users(uname varchar(20),pass varchar(20));
```

## Running 
Recommended to use VS Code . Execute the file LOGIN_PAGE.py.
This pops up the login page.

***connect to database by clicking connect.***

You can setup a new user id and password. Click login to login and the page redirects to main page .

**IF YOU DONT WANT TO USE THE LOGIN PAGE YOU ACN DIRECTLY RUN THE MAIN_APP.py **

###THANK YOU
