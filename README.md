Firewall-Access-Request
=======================

An Excel spreadsheet for:  
1. Submitting firewall access requests in SecureChange  
2. Retrieving device and policy information from SecureTrack  

The spreadsheet contains the following sheets:  
1. Request (requires SecureChange)  
2. Devices (requires SecureTrack)  
3. Rules (requires SecureTrack)  
4. Network Objects (requires SecureTrack)  
5. Services (requires SecureTrack)  
6. Cisco ACL stats (requires SecureTrack)  
7. Check Point Policy Stats (requires SecureTrack)  
8. Zone Based Firewall Stats (requires SecureTrack)  
9. Settings: define system settings  

Configuration
-------------
1. Install Tufin SecureTrack or SecureChange (you may also use the free SecureChange Basic which comes with SecureTrack)  
2. Open the spreadsheet  
3. Enable macros (if Excel asks you)  
4. Go to the Settings sheet and fill in the details  
5. Use any of the other sheets  

Submitting access requests
--------------------------
1. Go to the Request sheet, fill in the access request and submit it  
2. If all goes well a popup will say "Ticket was submitted successfully."  
3. If you get an error message check that settings and make sure that the request matches the workflow settings  

Getting Devices
---------------
1. Go to the Devices sheet  
2. Enter "yes" or "no" in cell B1 to define whether you want to fetch policy cleanup statistics  
3. Click the "Get Devices" button  

Getting Rules and Objects from SecureTrack
------------------------------------------
1. Go to the relevant sheet  
2. Enter one or more device IDs in cell B1, B2 etc. (you can get the ID from the Devices sheet)  
3. Click the button  
4. If successful, you will see the data being populated the sheet  

Help
----
Please contact support@tufin.com  
