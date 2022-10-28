## PROJECT 4: MEAN STACK IMPLEMENTATION

___
### **STEP 1: NODEJS INSTALLATION**
___


I ran the following commands on my virtual machine to update a list of packages in the Ubuntu package manager and to upgrade the Ubuntu OS:

`sudo apt update`

`sudo apt upgrade`


Next, I added certificates by running the following commands:

`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`

`curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -`

Next, I installed NodeJS by running the command below:

`sudo apt install -y nodejs`



### **STEP 2: MONGODB INSTALLATION**

To install the MongoDB, I ran the commands below:

`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6`


`echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list`




