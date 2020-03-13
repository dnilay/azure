Steps to deploy webapps
1. az webapp deployment user set --user-name [username] --password [password]
2.cd ~/helloworld/target
curl -v -X POST -u [username]:[password] https://[sitename].scm.azurewebsites.net/api/wardeploy --data-binary @helloworld.war
