\#nextcloud lab

\##overview

this project demonstrates how to deploy local private cloud using docker desktop on Win 11.

the environment contains:

1-next cloud

2-mariadb

3-docker compose

4-docker volume

5-next cloud desktop sync

6-git version control

\#architecture

windows 11

|

installed docker desktop

|

created nextcloud container + MariaDB container + docker volume

\##requirements

Win 11, WSL2, Docker Desktop, Web Browser

\##setup

1-cloned the repository ---> use this command in powershell to cloning: git clone https://github.com/kiatgrimes/NextCloud-Lab.git

2-create folder in C:\\ and named NextCloud

3-create .env file (replace with your own password)

4-start docker desktop

5-run in powershell this command

docker compose up -d

6-open browser and type this address http://localhost:8080

