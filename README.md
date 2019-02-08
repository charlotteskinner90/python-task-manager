# Task Manager App
### Mini Project (Data Centric Development) for Full Stack Web Dev Course with Code Institute 
This app was created using Flask (Python framework) and MongoDB for data storage. Materialize is used throughout for UI components.

### Deployment
This application is hosted on Heroku at: https://task-manager-flask-app.herokuapp.com/ In order to deploy this app to heroku, I added a [Procfile](https://github.com/charlotteskinner90/python-task-manager/blob/master/Procfile) which tells heroku the language of the app and the name of the file that needs to be run - in this case this was [app.py](https://github.com/charlotteskinner90/python-task-manager/blob/master/app.py)
I then set up a [requirements.txt](https://github.com/charlotteskinner90/python-task-manager/blob/master/requirements.txt) file which holds the dependencies that this app requires in order to run. Both the Procfile an requirements.txt file are committed to the repository and pushed to Heroku.
I had to set up some environment variables inside Heroku in order for the app to appear on the live URL. The following are configured under Settings -> Reveal Config Vars
  - IP: 0.0.0.0
  - PORT: 5000

To run this app locally, please use the following steps:
  - Clone this repository and run it in an IDE of your choice.
  - Set your environment variables i.e. IP: 127.0.0.1 and PORT: 5000
  - Install dependencies required for the app to run from the requirements.txt file by running the following command in the terminal **pip install -r requirements.txt**
