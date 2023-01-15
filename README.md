# Todo Node JS application with Docker containerization and Jenkins automated Pipeline.

Application side:
sudo apt install nodejs
sudo apt install npm
npm install
node app.js

Automated Jenkins Pipeline:
docker build . -t nodeapp
docker run -d --name nodeappcontainer -p 8000:8000 nodeapp
