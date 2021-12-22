1.Clone this repository.
2.Create a virtualenv and install the requirements.
3.Open a second terminal window and start a local Redis server (if you are on Linux or Mac, execute run-redis.sh to install and launch a private copy).
4.Open a third terminal window. Then start a Celery worker: venv/bin/celery -A app.celery worker --loglevel=info.
5.Start the Flask application on your original terminal window: venv/bin/python app.py.
6.Go to http://localhost:5000/ and enjoy this application!