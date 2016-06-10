Firewall-Access-Request
=======================

This Excel spreadsheet demonstrates the RESTful APIs in Tufin SecureTrack and SecureChange.
In honour of Hacker Joe.


The spreadsheet contains the following sheets:  
- Request - submit an access request in SecureChange
- Ticket Status - get ticket status from SecureChange
- Devices - retrieve SecureTrack devices
- Rules - retrieve security rules from SecureTrack  
- Policy Analysis - fetches rules that match specific flows
- NAT Rules - retrieve NAT rules from SecureTrack  (still under work - please help to finalize)
- Network Objects - retrieve network objects from SecureTrack
- Services - requires services from SecureTrack
- Cisco ACL stats - retrieve info about Cisco ACLs from SecureTrack  
- Check Point Policy Stats -  retrieve info about Check Point policies from SecureTrack
- Zone Based Firewall Stats - retrieve info about zone based firewalls from SecureTrack
- Debug: see the REST requests and responses for debugging
- Settings: define system settings

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

Getting Ticket Status
---------------------
1. Go to the Ticket Status sheet
2. Enter the number of the first ticket you want to retrieve
3. Enter the number of ticket to retrieve (1 or more)
4. Enter the exact name of the workflow step that contains the verifier tool - Verification status will be taken from this step
5. Click Get Tickets

Getting Devices
---------------
1. Go to the Devices sheet  
2. Enter "yes" or "no" in cell B1 to define whether you want to fetch policy cleanup statistics  
3. Click the "Get Devices" button  

Getting Rules, NAT Rules and Objects from SecureTrack
-----------------------------------------------------
1. Go to the relevant sheet  
2. Enter one or more device IDs in cell B1, B2 etc. (you can get the ID from the Devices sheet)  
3. Click the button  
4. If successful, you will see the data being populated the sheet  

Policy Analysis
---------------
1. Go to the Policy Analysis sheet
2. Enter one or more device IDs in cell B1, B2 etc. (you can get the ID from the Devices sheet)  
3. Enter the Policy Analysis query in rows 4-7
3. Click the button  

Help
----
Please search Google for "Tufin Developer Community" and join the community
