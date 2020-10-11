# django-rest-framework


#Method Used: 

Used Cron Jobs(https://django-cron.readthedocs.io/en/latest/introduction.html) to fetch videos after every 1 minutes using Youtube Data Api(https://developers.google.com/youtube/v3/docs/search/list) and save it to the db

#how to setup the project:

Clone the project 1.As this project is based on Django, your system need to have proper python setup, refer (https://www.python.org/downloads/)

2.Go the project through the terminal and install all dependencies by using typing pip install -r requirements.txt in the terminal

3.Inside the setting.py file, fill the variable GOOGLE_API_KEYS with all the API Keys available,the list should be filled as ['API_KEY_1','API_KEY_2',...]

4.For getting an API key follow this(https://developers.google.com/youtube/v3/getting-started)

5.Setup crontab to run Job, Follow this(https://django-cron.readthedocs.io/en/latest/installation.html)

6.Run the server using python mange.py runserver

