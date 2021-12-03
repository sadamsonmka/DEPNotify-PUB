# DEPNotify-PUB
 Public DEPNotify REPO

This code was updated and adjusted for our EDU environment.  NOTE:  Test mode is ENABLED
Included in the DEPNotify scripts are some basic logic to leverage the "ROLE" to deploy a specific set of app Policies.
I am using the roles of "Faculty, Staff, and Students" to flow into the JAMF DEPARTMENT field and BUILDING to relate to our campus areas (Primary, Middle and Upper School)

I am also using Installomator 8.0 as part of the policies being called to assure latest deployment of key applications (chrome, firefox, zoom)

NOTICE, using Trigger ID vs. name or CustomEvent (had some issues with that)
Change the verbiage of EULA to AUP (for EDU).  Having issues getting the aup.txt file to the /Shared/Users/aup.txt location (getting dummy text in the AUP window right now).  Will see if I can find when to push to the location (have a PKG created in Composer that I have been running in Pre-stage but not working.