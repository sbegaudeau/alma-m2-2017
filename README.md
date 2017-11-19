### ALMA server

This repository will contain the source code of the ALMA server based on Spring Boot.

Project members:
		BELASSAL Salma (Student B,C)
		MESSAOUD Nadhir (Student A)

This project is developped under the module of project management for the MASTER 2 ALMA of Nantes University.

##Installation requirements 

the next tools are necessary for installing this project, please make sure that you have the minimun requirements below: 

git, version 2.7.4 or higher
npm, version 3.5.2 or higher
Maven, version 3.3.9 or higher
Travis, version 1.8.8
Docker, version 1.13.1

##Installation

Start by cloning the git repository using the following command: 
	git clone https://github.com/hodororganizo/alma-m2-2017.git

then, follow the instructions to execute the installation scripts

The docker command  to launch your server is :
	sudo docker run -p 8080:8080 hodororganizo/alma-server

Your server is set up and can be checker at the following address: 
	http://localhost:8080


