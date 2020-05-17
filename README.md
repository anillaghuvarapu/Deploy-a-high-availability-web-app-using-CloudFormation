# IAC
Deploy a high-availability web app using CloudFormation
# Project 2 - Deploy a High-Availability Web App using CloudFormation 

1. In this project (Myworlddevops), I deployed web servers for a highly available web app using CloudFormation.
2. I wrote the script that creates and deploys the infrastructure and application for an myworlddevops from the ground up.
3. The script begin deploying the networking components followed by servers, security roles and software.

## The files included are:
* create.sh : Cloudformation create stack script. 
* update.sh : Cloudformation update stack script.
* destroy.sh : Cloudformation delete stack script.
* network.yml : myworlddevops Project's CloudFormation network script.
* network-parameters.json : myworlddevops Project's CloudFormation script network parameters.
* server.yml : myworlddevops Project's CloudFormation server script.
* server-parameters.json : myworlddevops Project's CloudFormation script server parameters.

## Instruction of deploy: execute below visual code

./create.sh myworlddevopsApp network.yml network-parameters.json

./create.sh myworlddevopsApp server.yml server-parameters.json
