# GoogleAddressVBA
I created this application as the system we use at work is all Access based and we had a free form Address entry which created some errors.
This is a much cleaner way to do it.
Its current set at country au - change to your own country to get your results.
Depending on the country Google formats the address differently so you may need to play around with the Instring markers

Instructions

Open DB (dont forget to hold shift!)
Ctrl G to bring up code window
Go the Google Places API and get a key https://developers.google.com/places/web-service/
you need to add the key into two different spots
the first spot is on the "on Change" event of text7
the second is in a module called GoogleMod
