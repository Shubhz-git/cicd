# Todo Node JS application with AWS EC2, Docker containerization and Jenkins automated Pipeline.

# Server side:
Creation of an EC2 instaince with allowing HTTP traffic with Port opening for Jenkins Server
Installation of jenkins [ install JDK first then jenkins ]
Creation of SSH Key [ ssh-keygen ]

# Application side:
sudo apt install nodejs
sudo apt install npm
npm install
node app.js

# nstallation of Docker 

Automated Jenkins Pipeline using Github webhooks:
docker build . -t nodeapp
docker run -d --name nodeappcontainer -p 8000:8000 nodeapp
