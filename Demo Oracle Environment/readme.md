This entire folder is a work in progress. None of these really work except for oracle-port settings.

Currently working on installing Teleport, and setting up a Teleport Bastion on an Oracle Cloud Environment.

Current Working Files:

OraclePortSettings.yml
This file opens up the ports needed to set up a basic web server using IP Tables (80/443) on Oracles Cloud Hosting (OCI).

DockerPortainerInstall.yml
This file currently installs Docker, Docker-CE and Portainer to be exposed to the Teleport Bastion Host as an Application/proxy.