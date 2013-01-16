## Procfile support on CloudBees.

This provides support for Procfile apps on CloudBees. 

To use: 

bees app:deploy -t go -RPLUGIN.SRC.go=https://s3.amazonaws.com/clickstacks/admin/procfile-plugin-0.1.1.zip -a michaelnealeclickstart2/testpfile1 go-procfile.zip 

The go-procfile.zip is a sample "google go" app. Unzip it to take a look at what makes it tick. 
You can package up your own apps similarly.
Make sure you set executable permissions on the scripts/programms that the Procfile refers to. 
(the Procfile file itself only has to be readable.)

Note: procfile does not install dependencies for you - you need to bundle them with your app.



