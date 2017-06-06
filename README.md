## Docker Server

This playbook create a docker server for production environment, using LVM storage driver with thinkpool.
It install the last docker version (Docker Community Edition)

Dependences:

* Centos 7 
* 1 Aditional disk device named /dev/sdb 

Roles:

* init
* common
* docker-ce

These roles can be found [here](https://github.com/jenciso/roles.git)

