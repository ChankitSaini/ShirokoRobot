worker: python3 -m ShirokoRobot
ps:scale worker=1
web: gunicorn --bind 0.0.0.0:$PORT --chdir Web app:app
