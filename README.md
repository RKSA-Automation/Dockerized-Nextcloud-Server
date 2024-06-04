# Installation Process

1. git clone first the repositories using this command ```git clone https://github.com/RKSA-Automation/Dockerized-Nextcloud-Server.git```
2. Go to the Dockerized-Nextcloud-Server folder
3. Inside the folder run this command: ```chmod +x -R .start-compose```
4. Then, you can now start execute the filename .compose. Go to the .start-compose folder first.
5. Lastly, run this command ```./.compose.``` And you may now choose options to proceed installation.

# Note

If you encountered error from execution of .compose file. Please install the dos2unix.

1. ```apt-get install dos2unix``` = to install dos2unix
2. ```dos2unix .compose``` = to convert the file

# Access the Nextcloud App
access by URL, http://IP-Address:8001

# Access the Adminer to control the Mysql Server or access the database
Located to URL, http://IP-Address:8080
