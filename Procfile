web: newrelic-admin run-program gunicorn --pythonpath="$PWD/solutions-provider" wsgi:application
worker: python solutions-provider/manage.py rqworker default