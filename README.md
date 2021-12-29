this repository is about Jenkins Config as Code

<b>First boot</b>

First off we require docker-compose.

This is very simple, using docker-compose execute the following command from the root of this repository:

docker-compose up 
you may use the bash script , just run bash docker_up.sh {up,restart,stop,etc..} -> one of this with the bash command. 

This will start up a Jenkins instance which will be accessible on the host through port 80, just open your browser and navigate to http://localhost 

