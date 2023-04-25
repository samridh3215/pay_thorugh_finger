# Integrated Payment System with Student's Fingerprint

**This project reqires a raspberrypi 3/4, r307 fingerprint module and an oled display to work**

## Installing the dependencies 

Run ```pip install -r requirements.txt``` to install dependencies

## Using the project
- There are two parts to this project, registering the fingerprint to the server with name, SRN and amount
- Verifying and processing payment at the eateries/canteens where the vendor selects the items according to the order

You will need a uri to store and verify the fingerprints. Create a mongodb database and get the uri and store that in a .env file as
```uri="<your uri>"```

- Run the RegisterFinger.py to enroll yourslef 
- Then run the Server.py
- Once thats running, run Shop.py


