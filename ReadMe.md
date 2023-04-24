This is test for Java project to test.
Java test project created at local which we build using build trigger using windows batch command.
Checking with Jenkins job so that once commit happens it will trigger jenkins job
http://localhost:8080/job/GithubTriggerJob/
https://6919-83-99-255-160.eu.ngrok.io/github-webhook

Added below in http://localhost:8080/job/GithubTriggerJob/configure build steps so that java program run and provide output hello-world
************************************************
cd F:\Devops\Jenkins\Git Repo\Jenkins-Demo

F:

javac JavaDemo.java

java HelloWorld
************************************************

This project used to Git integration (SCM).
