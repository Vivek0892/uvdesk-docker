# uvdesk-docker
UVDesk Docker manifests 3 containers deployed: Nginx:1.19.3-alpine, Mysql-server:8.0.22-1.1.18 and PHP:7.4-fpm-alpine.

STEP 1: Git me!: git clone https://github.com/schlepper-code/uvdesk-docker.git

STEP 2: Go to folder: cd uvdesk-docker and download UVdesk Open Source: wget https://cdn.uvdesk.com/uvdesk/downloads/opensource/uvdesk-community-current-stable.zip

STEP 3: unzip uvdesk-community-current-stable.zip

STEP 4: For installation, set full permissions on folder uvdesk-community-v1.0.12: chmod 777 -R uvdesk-community-v1.0.12

STEP 5:docker-compose --file docker-compose.yml up -d

Note: Edit docker-compose.yml file to change Mysql default password and database name. You will need this info later to complete setup.


Get this great Helpdesk Ticketing System running in 5 minutes in 5 easy steps!
Requirements: Linux OS with Docker, docker-compose and Git.

STEP 1: Git me!: git clone https://github.com/schlepper-code/uvdesk-docker.git

STEP 2: Go to folder: cd uvdesk-docker and download UVdesk Open Source: wget https://cdn.uvdesk.com/uvdesk/downloads/opensource/uvdesk-community-current-stable.zip

STEP 3: unzip uvdesk-community-current-stable.zip

STEP 4: For installation, set full permissions on folder uvdesk-community-v1.0.12: chmod 777 -R uvdesk-community-v1.0.12

Note: Edit docker-compose.yml file to change Mysql default password and database name. You will need this info later to complete setup.

STEP 5: Now watch this Docker magic: docker-compose --file docker-compose.yml up -d

Docker will set up 3 containers in about 5 minutes: Mysql server, PHP server and Nginx web server. Mysql will create db_uvdesk folder and at this point you can open you favorite browser and connect to your Helpdesk system: http://yourLinuxBoxIP to finish setup. Enjoy!
