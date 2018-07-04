## Introduction To DevOps 
Standalone Project 

## Steps to Setup. 

Lab setup includes the following tasks needs to be performed.

### 1. Creating CentOS Server Instances.

![screenshot from 2018-07-04 02-19-46](https://user-images.githubusercontent.com/8659694/42260029-e0bd0cb6-7f30-11e8-9174-d7c99f2fa3c2.png)

### 2. run a script for custom configurations of server 
          
          --> curl https://raw.githubusercontent.com/Venukannuri/Standalone-DevOps/master/init-script.sh | bash     

### 3. Create exisiting CentOS Server Instance to Image 

![screenshot from 2018-07-04 02-27-04](https://user-images.githubusercontent.com/8659694/42260311-e9143da2-7f31-11e8-8b36-cfc4719177e7.png)

### 4.  Configure Stack with three different servers. 
   
   ### Install Web Server.

        yum install httpd -y
       
   ### Install App Server.
       
        yum install tomcat -y
   
   ### Install App Server.
        
        yum install mariadb-server -y
