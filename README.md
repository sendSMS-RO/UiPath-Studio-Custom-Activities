# UiPath-Custom-Activities-With-sendSMS.ro-connector.
How To Use UiPath Custom Activities With sendSMS.ro connector
UiPath Custom Activities With sendSMS.ro connector has nine activities :

1. SMS Application Scope - General configuration and test the connection
2. sendSMS - Simple activity of sending a short message in a mobile network in over 170 countries, here you will find some optional parameters like: 
  a. SHORT - for automatic short link creation  
  b. GDPR - creates a unique short unsubscribe link at the end of the message for each mobile number, which has 25-30 characters
3. Get Messages - This function returns all inbound (MO) messages for the user which have an ID larger than 'last_id'. It is a function used for inbound messages (MO) in the case of bidirectional communications.
4. Get Balance - Gets the user balance in EURO
5. Add Contact - Add a contact in your address book
6. Delete Contact - Delete a contact from your address book
7. Blocklist add - Add the given number to block list
8. Blocklist delete - Delete the given number from the block list
9. Blocklist Check - Check if the given number is in the block list  

You can add this activities directly from UiPath Marketplace, here is a direct link : https://connect.uipath.com/marketplace/components/connector-for-sendsmsro
