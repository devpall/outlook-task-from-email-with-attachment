---------------
README
---------------

Copyright 2011 Michael Caruso
Licensed under the GPL, version 3 (see http://www.gnu.org/licenses/gpl.txt)

Provided with no warranty of any kind -- use at your own risk.  I don't have access to Outlook anymore, so I can't test this script currently.  Make sure to backup all data before testing this script.

I wrote a VBA script that turns an email into an Outlook task. Just forward the email to yourself and include "@task" in the subject line.  The script turns the subject (minus "@task") into the task and the body of the email (with attachments) becomes the body of the task.  You can find the script below.

----------------------------
Requirements and Limitations
----------------------------
The script requires:
* Outlook 2000 with access to the Scripts Editor

This script is provided without any warranty, use at your own risk.  Remember the backup first!  If you would like to improve the script, please feel free to fork it on GitHub.

---------------------
How To Use The Script
---------------------
* Download the script
* Set the attachment location in the script (it's currently set as C:\Email_Attachments)
* Open your Outlook VBA Editor (at Tools->Macros->Macros in Outlook 2000)
* Copy the script into Project1 (this document should open when you load the macro editor -- do not overwrite any other information in Project1 unless you know why you're overwriting it)
* Save the script and test it!

--------
Download
--------
After reading the above, download the script here:
http://github.com/michaelcaruso/outlook-task-from-email-with-attachment

-------
Contact
-------
Michael Caruso
http://michaelcaruso.net/
Another project I'm working on: Evergreen Sessions - find and recommend sustainable outdoor gear (http://evergreensessions.com/)
mike@michaelcaruso.net
