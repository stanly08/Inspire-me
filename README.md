About Inspire Me
Inspire me is an application that, depending on your age recommends you something to or what you would pursue and lets you set the goals that you would like to achieve.

Features
•	User authentication: sign up, sign in and sign out functionalities.
•	Set goals
Getting started
Prequisites:
•	Python 3
•	Flask
•	SQLite or SQLAlchemy supported db
File structure
Inspire_me/
|--app.py
     templates/
	home.html
	login.html
	signup.html
	goals.html
Installation
1.clone the repo
git clone https://github.com/stanly08/Inspire-me.git
2.Navigate to the project directory
cd Inspire-me
3.Create a virtual environment
python3 –m venv myenv
4.activate virtual environment
Myenv\Scripts\activate
5.Install the dependencies
pip install -r requirements.txt
pip install flask flask_sqlalchemy flask_bcrypt flask_login
6.initialize the database
Python
>>>from app import db
>>>db.create_all
>>>exit()

Contributing
1.	Fork the repo
2.	Create a new branch
3.	Make your changes
4.	Commit your changes
5.	Push to the branch
6.	Create a new pull request
Authors
1.	STANLY ANASI
2.	ELVIS KHAMALA
License

