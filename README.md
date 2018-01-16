# sackoverflow documentations

## This project is under development, Don't expect much

## About
This is an SPA(SINGLE PAGE APPLICATION) web app made by using routing deployed on HEROKU (with postgres database as an add-on), which is quite useful for the farmers as they can post their queries and the experts can answer them. A farmer can also log in and log out,view his dashboard.A farmer and an expert can also upvote the answers.

## Website Link: https://sackoverflow.herokuapp.com

## Technology Used:
	Django 2.1(Python 3.6.4 framework)
	Reactjs
	Materialize

## Commands for running the project[ONLY FOR HEROKU CONTRIBUTORS OF THIS PROJECT]:
	python -m venv <venv name>
	(where python is accessable command for python 3.6.4)
	<venv name>\Scripts\activate(running the venv)
	pip install -r requirements.txt(installing the packages used in the project)
	[DELETE the node_modules folder and webpack-stats.json]
	npm install (Install the node_modules depandencies from package.json)
	node_modules\.bin\webpack --config webpack.config.js (run this command to create bundle files, run it everytime you make a change)
	[or]
	node_modules\.bin\webpack --config webpack.config.js --watch (run this command to create bundle files, it automatically watches the files youo change)
	python manage.py migrate (migrating Auth and other predefined tables)
	python manage.py runserver (Running the localserver)
	Installing any package in node_modules
	npm install --save <name of the package>
	


