# ResumeAI

## Overview

The project is a MEAN project and uses node version 18.

I created a VM named MEANAppVMDebJan
Copied the entire repo from local to the machine . 
I did set up the backend server . created the .env file for frontend 
I did set up the frontend server 

A gist of commands used - 
ssh -i C:/Users/debsu/.ssh/MEANAppVMDebJan_key.pem azureuser@20.84.123.42
scp -i C:/Users/debsu/.ssh/MEANAppVMDebJan_key.pem -r "C:/Assignments_zips/Azure Assignment/ResumeAI" azureuser@20.84.123.42:/home/azureuser/
sudo apt install nano
sudo apt update
sudo apt install nodejs npm
sudo apt install nginx
npm install
sudo lsof -t -i:4292 | xargs sudo kill -9
MONGO_URI=mongodb://localhost:27017/ResumeAI
PORT=4292
mongosh
npm start
ng build prod
git clone  https://github.com/UnpredictablePrashant/ResumeAI

The current resource group "Herovired" doesnt allow me to create Appservices or proper monitoring through Azure , I can create through Grafana and prometheus which is any ways demonstrated earlier 

All screen shots included 