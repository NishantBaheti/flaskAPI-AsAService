# flaskAPI-AsAService

### Running Python-Flask API as a Service in Ubuntu OS.

1. Preferably create a python virtual env using "virtualenv" or "python venv".
1. Use "requirement.txt" file to install all the required libs.
1. Use "app.py" file as main app file and add more end points as per requrement.
1. Create a service file(.service) with the configurations of the service.
1. Use "gunicorn" or "wsgi" (production servers) to host flask api.


### create a service
1. Copy flaskapi.service file in "/etc/systemd/system/".
1. Run Command -
	1. sudo systemctl daemon-reload
	1. sudo systemctl start flaskapi
1. To check the status run -
	1. sudo systemctl status flaskapi

