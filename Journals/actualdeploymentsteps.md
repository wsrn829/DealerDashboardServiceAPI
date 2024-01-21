1. `brew tap heroku/brew && brew install heroku` (install Heroku CLI - Command-Line Interface - A Command-Line Interface is a text-based interface used to interact with software and computer systems by entering commands into a terminal or command prompt.) "No, you don't need to add anything to your requirements.txt file after installing Heroku CLI with Homebrew. The requirements.txt file is used for Python dependencies that your project needs, and these are installed with pip.

The Heroku CLI is a tool that you use on your local machine to manage your Heroku apps. It's not a dependency of your project, so it doesn't need to be listed in requirements.txt."


2. `heroku login`
3. `heroku container:login`
4. `heroku create`


1. `pip install pipreqs`
2. `pipreqs .`
3. create Procfile
4. `heroku create dealer-dashboard`
https://dealer-dashboard-8d7b3aea3ae7.herokuapp.com/ | https://git.heroku.com/dealer-dashboard.git
5. pip install gunicorn
6. DEBUG = False
7. `heroku buildpacks:set heroku/python`
8. python inventory/api/manage.py collectstatic --noinput
9. create static directory as in configuration
10. correct path to wsgi.py
11. run python manage.py collectstatic inside folder with manage.py