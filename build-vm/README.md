## Instructions to set up VM using Vagrant.

###Environment
__Virtual Box used:__ [box-cutter/ubuntu1404-desktop](https://vagrantcloud.com/box-cutter/boxes/ubuntu1404-desktop)

### Steps:
* Download and Install [VirtualBox](https://www.virtualbox.org/) and [Vagrant](http://www.vagrantup.com/).
* Create a new folder and place this [Vagrantfile](https://github.com/SoftwareEngineeringToolDemos/ICSE-2012-EXSYST/blob/master/build-vm/Vagrantfile) in it.
* Run the command "vagrant up" in terminal in the folder created in above step. This will create a new ubuntu 14.04v virtual machine and installs exsyst.jar, oracle java 6 and all required files in it.
* Wait for the GUI to show up and then can start using
* Credentials for login.
  * Username: vagrant
  * Password: vagrant


### References:
* https://docs.vagrantup.com/v2/getting-started/up.html
* https://docs.vagrantup.com/v2/getting-started/boxes.html
* http://www.webupd8.org/2012/11/oracle-sun-java-6-installer-available.html
* http://askubuntu.com/questions/159008/how-to-add-startup-applications-in-lubuntu
* https://help.ubuntu.com/community/AutoLogin
* http://askubuntu.com/questions/418407/how-do-i-create-a-desktop-file-to-launch-eclipse
