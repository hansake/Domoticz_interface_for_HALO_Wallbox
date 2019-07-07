# Domoticz_interface_for_HALO_Wallbox
Domoticz interface for HALO Wallbox Electric Car Charger

This dzVents script is using the API towards the HALO Wallbox cloud service.
To get the needed API key you have to contact Charge Amps (https://charge-amps.com/).

First create a virtual sensor:
Create a dummy hardware device of type "Electric (Instant+Counter)"
* Setup > Hardware > Dummy (Does nothing, use for virtual switches only)
* Create Virtual Sensors > Electric (Instant+Counter)
* Name the virtual device in this example is "Billaddare"

User Variables used by the script for a HALO Wallbox, all with type "string":
* chargeAmpsApiKey
* chargeAmpsSerial
* chargeAmpsChargerCode

Create the event script:

Setup -> More Options -> Events -> create new dzVents event script called "charge_amps".
