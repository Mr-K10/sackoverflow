# sackoverflow documentations
	
## Technology Used:
python 3.6.4<br>
Django 2<br>
Reactjs

## Commands for running the project:
	python -m venv <venv name>
	(where python is accessable command for python 3.6.4)
	<venv name>\Scripts\activate(running the venv)
	pip install -r requirements.txt(installing the packages used in the project)
	DELETE the node_modules folder and webpack-stats.json
	npm install (Install the node_modules depandencies from package.json)
	node_modules\.bin\webpack --config webpack.config.js (run this command to create bundle files, run it everytime you make a change)
	[or]
	node_modules\.bin\webpack --config webpack.config.js --watch (run this command to create bundle files, it automatically watches the files youo change)
	python manage.py migrate (migrating Auth and other predefined tables)
	python manage.py runserver (Running the localserver)
	
