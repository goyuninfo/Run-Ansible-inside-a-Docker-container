# Run-Ansible-inside-a-Docker-container

## Build the Docker Image
docker build -t ansible:latest .

## Run your Docker image with Ansible
docker run -it ansible

$ docker run  ansible ansible --version
ansible 2.10.8
  config file = None
  configured module search path = ['/root/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/local/lib/python3.8/dist-packages/ansible
  executable location = /usr/local/bin/ansible
  python version = 3.8.5 (default, Jan 27 2021, 15:41:15) [GCC 9.3.0]
