# PhoneIMSILookup
Django App to perform IMSI Lookup

# HOWTO:
clone to repo - git clone https://github.com/cybersafeblr/PhoneIMSILookup
 
# ACTIVATE ENV
python3 -m venv env && source /env/bin/activate

# INSTALLDEPENDENCIES:
requests
python3 -m pip install -r requirements.txt

# RUN SERVER
python3 manage.py migrate
python3 manage.py runserver

App will run on https://localhost:8000

