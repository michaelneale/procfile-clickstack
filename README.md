## Procfile support on CloudBees.

This provides support for Procfile apps on CloudBees. 

To use: 

bees app:deploy -t go -RPLUGIN.SRC.go=https://s3.amazonaws.com/clickstacks/admin/procfile-plugin-0.1.1.zip -a michaelnealeclickstart2/testpfile1 go-procfile.zip 

The go-procfile.zip is a sample "google go" app.


