DockerInstallCloud.yml is a playbook that installs Docker and DockerCE  (plus updates Ubuntu and installs dependancies) an ARM instance (adjust accordingly for AMD instance) onto a Cloud Instance (in this case for Oracle but it's cloud agnostic)

DockerInstallLocal.yml is a playbook that installed Docker, DockerCE, and Portainer (plus updates Ubuntu and installs dependancies) on an AMD64 instance that is local to my network. This will use Portainer (and portainer Agent) to connect to the cloud instance to install the remaining docker containers. Each instance will be a mirror of each other.

