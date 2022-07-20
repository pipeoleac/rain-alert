# rain-alert

App que avisa cuando va a llover, utilizando apis, api keys, longitud y latitud

import requests
import os
from twilio.rest import Client
from twilio.http.http_client import TwilioHttpClient

RECORDAR: poner tus propios datos desde twillio
RECORDAR: Pueden usar free proxy servers de la version FREE de pythonanywhere
https://www.twilio.com/es-mx/

OWM_Endpoint = "https://api.openweathermap.org/data/2.5/onecall"

api_key = os.environ.get("API_KEY")   (Usar pythonanywhere para gestionar tus enviroments)


account_sid = "ACCOUNT SID"


auth_token = os.environ.get("AUTH_TOKEN")

LATITUDE y LONGITUDE



