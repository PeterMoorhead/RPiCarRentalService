# Car rental Service hosted on a Raspberry Pi using flask
###### Peter Moorhead 
## Car Rental Service

A car rental system hosted on a raspberry pi and accessed through a combination of a Flask webapp and API.
Users will be able to register an account and login.
Search Cars available for hire
Make bookings and link their google calendar to tell them when they have their car
Cancel existing bookings if need be
Use Camera to read Qr BarCodes to retreive Engineers Profile
Use Voice Recognition for Admin to Search Specific Cars
PushBullet to send Notifications to engineers
Bluetooth to find nearby devices and match MAC address to database of Known MAC addresses

## Logins
* Username: admin1, Password: admin1
* Username: Engineer1, Password: Engineer1
* Username: Manager1, Password: Manager1

##### Installation:

clone repo
copy setup.py to same level as repo folder
copy credentials.json to same level as repo folder
copy token.pickle to same level as repo folder
copy requirements.txt to same level as repo folder
```bash
python3 -m venv venv
. venv/bin/activate
(venv) pip install -r requirements.txt
(venv) export FLASK_APP=IoTAssignment2
(venv) pip install -e .
(venv) flask run --host=0.0.0.0
```

## Trello usage

![Trello](/images/trello.PNG)


## Github usage

![Trello](/images/chill.PNG)
![Trello](/images/branches.PNG)
![Trello](/images/commits.PNG)

## Testing

move the test.py to the level above the project folder and run python3 test.py


## Task allocation
under file Task_Allocation you will find who was responsible for which features
