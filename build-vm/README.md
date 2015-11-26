## Instructions to set up VM using Vagrant.

###Environment
__Virtual Box used:__ [Ubuntu/trusty32](https://atlas.hashicorp.com/ubuntu/boxes/trusty32)

### Steps:
* Download and Install [VirtualBox](https://www.virtualbox.org/) and [Vagrant](http://www.vagrantup.com/).
* Create a new folder and place this [Vagrantfile](https://github.com/SoftwareEngineeringToolDemos/ICSE-2012-EXSYST/blob/master/build-vm/Vagrantfile) in it.
* Run the command "vagrant up" in terminal in the folder created in above step. This will create a new ubuntu 14.04v virtual machine and installs oracle java 6 in it.
* There are two ways to login into this virtual machine.
  * Use the gui provided by the Virtualbox.
  * Use ssh client(like putty or vagrant ssh) to start a new ssh session.
* Credentials for login.
  * Username: vagrant
  * Password: vagrant

### References:
* https://docs.vagrantup.com/v2/getting-started/up.html
* https://docs.vagrantup.com/v2/getting-started/boxes.html
* http://www.webupd8.org/2012/11/oracle-sun-java-6-installer-available.html
