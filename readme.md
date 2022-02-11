# TRAVLR Developer Software Kit (Windows)

## SDK's / CLI
- .NET 6, netcore 3.1, netcore 2.1
- NodeJs (14.x)
- AWS CLI
- Chocolately CLI (Windows)
- Kubernetes CLI (kubectl)

## Software's
##### Editor
- Visual Studio Code -- open single files or simple files, configuration files, PHP Project, etc
- Visual Studio Community (Free) -- Open any TRAVLR Project's
- Jetbrains Product (Paid) :
    - Jetbrains Rider -- .NET Project's
    - Jetbrains PHPStorm -- PHP Project's
    - Jetbrains WebStorm -- Typescript/Javascript based Project's (currently: SSO)
 
##### Tools
- Docker -- Running any infrastructure like MySql Database, Redis, elastic search, rabbitmq, etc
- MySql Workbench (Windows) -- visual tools for creating, executing, and managing SQL queries and databases

## Configuring Your Device
- Configure yarn cli
    - Open terminal and run command: 
      ``choco install -y python2``
      ``npm i -g windows-build-tools``
    - If you are using Powershell to running the yarn command, you need to execute this command first (one time):
      ``Set-ExecutionPolicy Unrestricted``
- Configure AWS cli
  - Open terminal and run command:
    ``aws configure --profile travlr``
    Please ask your team mate for the ``Access Key`` and ``Secret Key``
- Configure kubetcl cli (Kubernetes Cluster)
  We use kubectl to port forwarding our services in the AWS to our local machine. So we can use our services from our local machine.
