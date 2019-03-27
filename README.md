# Install Instructions
This is how i setup my work envrionment in ubuntu.
- Anaconda : Go to Anaconda-Navigator >> Environment >> Click On "base(root)" (Green Right Pointin Arror) >> Open Terminal
	```
		conda update -n root conda
		conda update --all
	```
- Why ? Because it installs the rewuired packages in the anaconda environment.
- NodeJS
- MySQL
	```
		sudo apt-get update
		sudo apt-get install mysql-server
	```
- MySQLdb : 
	```
		sudo apt-get install python3-dev libmysqlclient-dev
		pip3 install mysqlclient
	```
- ElasticSearch :

	```
		>>> sudo apt-get install -y openjdk-7-jre openjdk-7-jdk
		>>> Download "tar.gz" of elasticsearch and unzip it. 
	```
