# Linux Server Configuration

#### Project Overview
> A baseline installation of a Linux server and preparing it to host our web applications, 
securing it from a number of attack vectors, installing and configuring a database server, and deploying our one of your existing web applications onto it.

#### Link to Project: [ItemCatalog](http://18.221.43.193/)

  * Public IP Address:** 18.221.43.193
  * Accessible SSH port:** 2200

#### 2. Access VM using SSH
  * Download the private key from Udacity to your local machine.
  * use the below command to connect.
  * ssh -i Privatesshkey grader@18.221.43.193 -p 2200  

#### 3. Restart Apache if required to launch the app

   
    $ sudo service apache2 restart
   
#### 4. Firewall has been set for ports 2200, 80,123 

#### 5. grader user sshkey permissions has been set for accessing the machine. 

#### 6. Below is the list of third-party software resources installed on the VM
	* sudo apt-get update
	* sudo apt-get upgrade
	* sudo dpkg-reconfigure tzdata
	* sudo apt-get install apache2 libapache2-mod-wsgi git
	* sudo apt-get install libpq-dev python-dev
	* sudo apt-get install postgresql postgresql-contrib
	* sudo apt-get install python python-pip python-all-dev -y
	* sudo pip install SQLAlchemy
	* sudo pip install flask
	* sudo pip install oauth2client
	* sudo pip install requests
	* sudo apt-get install curl

#### 7. Installed git, Apache, Postgresql softwares.












