#Just Eat Dummy Application

Source code and apk for the dummy android app of 'Just Eat'. While looking at ways to hard block myself from ordering on Just Eat I found the suggestion to create a dummy app.

Creating the dummy app was simple; followed the guide https://www.jetbrains.com/help/idea/create-your-first-android-application.html#95e5b892 with a few tweaks as I only needed an empty app. 

This dummy app stops installation and updates of the actual Just Eat app. 

Further, putting this app into a 'Secure Folder' and locking it with a throw away password will deny access and is a pain to reset. 

Then hide the secure folder via adb which hides the dummy app from the list of android apps in settings and prevents uninstallation. 
