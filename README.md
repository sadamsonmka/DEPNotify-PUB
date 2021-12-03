# DEPNotify-PUB
 Public DEPNotify REPO

This code was updated and adjusted for our EDU environment.  NOTE:  Test mode is ENABLED
Included in the DEPNotify scripts are some basic logic to leverage the "ROLE" to deploy a specific set of app Policies.
I am using the roles of "Faculty, Staff, and Students" to flow into the JAMF Department field and Building to relate to campus (Primary, Middle and Upper School)

I have also been using Installomator 8.0 as part of the policies being called to assure latest deployment of key applications.

NOTICE, using Trigger of ID vs. name or CustomEvent (had some issues with that)
Change the verbiage of EULA to AUP (for EDU).  Having issues getting the aup.txt file to the /Shared/Users/aup.txt location (getting dummy text in the AUP window right now).