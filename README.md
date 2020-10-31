# Docker-CE Installation on RHEL
The Redhat Linux OS that is installed on the Virtual Machine or on the PC, has to be configured with the yum repositories to install the docker.

If at all the OS launched from the cloud, the configuration of the YUM will be done by default. I am using putty in this tutorial, to access the instance launched.

![image](https://user-images.githubusercontent.com/60057551/97770897-7bed7480-1b5d-11eb-8f86-937a351a06a0.png)

Now, to access the folder where the repo files are present.
![image](https://user-images.githubusercontent.com/60057551/97770958-16e64e80-1b5e-11eb-8972-2674c9691132.png)

Install the VIM to create and edit the files in RHEL.
![image](https://user-images.githubusercontent.com/60057551/97770987-780e2200-1b5e-11eb-8c75-ffeaa84d4522.png)

Create and Open a repository for installation of docker using vim
![image](https://user-images.githubusercontent.com/60057551/97771041-21edae80-1b5f-11eb-9d2e-7d3a83668fa1.png)

Configure the repo file accordingly with the URL to download docker (http://download.docker.com/linux/centos/7/x86_64/stable)
![image](https://user-images.githubusercontent.com/60057551/97771052-3e89e680-1b5f-11eb-8e02-2a9c5c2344ea.png)

Install the Docker-CE stable version using yum
![image](https://user-images.githubusercontent.com/60057551/97771105-b5bf7a80-1b5f-11eb-84f8-f3b49e32b6fe.png)

After successful installation check the installed version of the docker
![image](https://user-images.githubusercontent.com/60057551/97771154-0e8f1300-1b60-11eb-85e0-51a45e14bdd6.png)

Start the docker 
![image](https://user-images.githubusercontent.com/60057551/97771170-3ed6b180-1b60-11eb-8617-93895a9d9388.png)

Execute few commands to know about the docker
![image](https://user-images.githubusercontent.com/60057551/97771210-b86e9f80-1b60-11eb-8595-e803fb4c395b.png)

Now, install an OS using and check the names of commands from hub.docker.com
![image](https://user-images.githubusercontent.com/60057551/97771335-c375ff80-1b61-11eb-8a95-d0d817b3e97d.png)

This is all about the installation of Docker-CE on RHEL. Happy Reading

 
