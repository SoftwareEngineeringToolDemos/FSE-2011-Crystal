###Please follow these steps to spin up a virtual machine for Crystal using vagrant script:
1. Download and Install [Vagrant](https://www.vagrantup.com/downloads.html) on the host machine.
2. Download and Install [Virtual Box](https://www.virtualbox.org/wiki/Downloads) on the host machine.
3. Download the [Vagrantfile](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-Crystal/blob/master/build-vm/Vagrantfile) from [build-vm](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-Crystal/tree/master/build-vm) directory to your machine.
4. In the host, cd into the directory that contains the Vagrantfile and run the command "vagrant up".
5. The command "vagrant up" will create a Ubuntu (64-bit) VM with Java installed in it.

###Note:
* The VM boots up quickly and can be viewed from VirtualBox. But the "vagrant up" command runs up approximately for 15-20 minutes.
* In case VM login details are required:

  Username: vagrant
  
  Password: vagrant

###Acknowledgements:
Used vagrant virtual box image of [ubuntu-desktop by rudolfochrist](https://atlas.hashicorp.com/rudolfochrist/boxes/ubuntu-desktop).

###References:
https://docs.vagrantup.com/v2/getting-started/

https://www.digitalocean.com/community/tutorials/how-to-install-java-on-ubuntu-with-apt-get
