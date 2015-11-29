###Please follow these steps to spin up a virtual machine for Crystal using vagrant script:
1. Download and Install [Vagrant](https://www.vagrantup.com/downloads.html) on the host machine.
2. Download and Install [Virtual Box](https://www.virtualbox.org/wiki/Downloads) on the host machine.
3. Download the [Vagrantfile](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-Crystal/blob/master/build-vm/Vagrantfile) from [build-vm](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-Crystal/tree/master/build-vm) directory to your machine.
4. In the host, cd into the directory that contains the Vagrantfile and run the command "vagrant up".
5. The command "vagrant up" will create the following: 
   * Ubuntu (64-bit) VM with Java
   * TortoiseHg (Mercurial)
  * Crystal 
  * 3 test repositories under folder "Tool-Demo" on desktop.
  * README.txt, Installation.txt, License.txt, Tool Executable-Binary folder and link to Youtube video of tool on desktop.

### Important Note:
* When you enter "vagrant up" command, the VM boots up for the first time without anything on desktop because the script
 is still running. 
* Wait for the script to finish. It can take approximately 20-30 minutes. After that time, the VM reboots for the second time.   At this point you should be able to see everything on the desktop and tool will automatically open up. 
* No configuration of Crystal is needed from the user.
* To test the tool, you will see a folder "Tool-Demo" on desktop with 3 repositories inside it. "Master", "Karan" and "Priya".
* These repositories are created so that the testing of tool can be done easily and in minimal time.
* "Master" represents the Master repository and "Karan" and "Priya" are clone to "Master".
* In case VM login details are required:

  Username: vagrant
  
  Password: vagrant

###Acknowledgements:
* Used vagrant virtual box image of [ubuntu-desktop by rudolfochrist](https://atlas.hashicorp.com/rudolfochrist/boxes/ubuntu-desktop).

* For disabling the usb settings in vagrant, used the code from: http://hameedullah.com/vagrant-101-basic-virtual-machine-customizations.html

* For access permissions to file (chmod) , used the command from:
http://askubuntu.com/questions/303593/how-can-i-chmod-777-all-subfolders-of-var-www

* For disabling the screen lock, used the command from: 
http://ubuntuhandbook.org/index.php/2013/07/disable-screen-lock-ubuntu-13-04/

###References:
https://docs.vagrantup.com/v2/getting-started/

https://www.digitalocean.com/community/tutorials/how-to-install-java-on-ubuntu-with-apt-get
