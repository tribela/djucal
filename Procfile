web: uwsgi --master --die-on-term --module app:app --http :5000
dev: FLASK_app=app.py FLASK_DEBUG=1 flask run