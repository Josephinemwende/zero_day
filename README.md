#**Vagrant -or - how to code in your local computer**

Sandboxes are great, but you can also do your ALX assessments on your local computer- having a virtual machine(VM) is the perfect tool for that.
Virtual Machines in the context of development area means to isolate and maintain a stable environment that will basically run the same way on any host.

_We will be using Vagrant:_
Vagrant is a tool that sits on top of a VM provider. We choose to use vagrant because it is free, reliable and well maintained.

**How to install Vagrant on your personal Computer:**

#**Mac OSx**

Download VirtualBox from this (link)
Install VirtualBox
Download Vagrant from this (link)
Install Vagrant
Open the Terminal application:
Now you will execute command line in your Terminal (each of them start with $)
Add the Ubuntu 20.04 (Focal) image to your box list: $ vagrant box add ubuntu/focal64 Warning: this step can take time
Many other images are available here
Create your first virtual machine:
$ vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine
$ vagrant up -> it will start your virtual machine
$ vagrant ssh -> now you are inside your virtual machine.

#**Windows**

Download VirtualBox from this (link)
Install VirtualBox
Download Vagrant from this (link)
Install Vagrant
Open the command prompt
Add the Ubuntu 20.04 (Focal) image to your box list:
C:\Users\julien> vagrant box add ubuntu/focal64 Warning: this step can take time
Many other images are available here

Create your first virtual machine:
C:\Users\julien> vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" -you don’t have to execute this command line everyday, only once, to create a new virtual machine
C:\Users\julien> vagrant plugin install vagrant-vbguest -> to avoid issue with the last version of Vagrant (2.2.4 or latest)
C:\Users\julien> vagrant up -> it will start your virtual machine
C:\Users\julien> vagrant ssh -> now you are inside your virtual machine.

#**Ubuntu**

Open the Terminal application:
Now you will execute command line in your Terminal (each of them start with $)
Install VirtualBox: $ sudo apt-get install virtualbox
Install Vagrant: $ sudo apt-get install vagrant
Add the Ubuntu 20.04 (Focal) image to your box list: $ vagrant box add ubuntu/focal64 Warning: this step can take time
Many other images are available here
Create your first virtual machine:
$ vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine
$ vagrant up -> it will start your virtual machine
$ vagrant ssh -> now you are inside your virtual machine.

