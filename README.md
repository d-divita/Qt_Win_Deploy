# Qt_Win_Deploy
### Batch script example to quickly deploy Qt app on Windows

#### Instructions:
* Create a "deploy" folder
* Build the app with **release** profile
* Copy the app executable into the deploy folder
* Copy the script into the deploy folder
* Modify the app_name.exe inside the script to match your app name
* Modify the Qt path inside the script to match your installation path
* Run the script (32 or 64-bit according to app architecture)
* Enjoy your standalone app! ;)

Note: if your app depends on external .dll, you have to include them manually inside the deploy folder
