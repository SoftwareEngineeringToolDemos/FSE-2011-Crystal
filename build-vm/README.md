###Please follow these steps to spin up a virtual machine for Crystal:
1. Install [Vagrant](https://www.vagrantup.com/downloads.html) and [Virtual Box](https://www.virtualbox.org/wiki/Downloads) on the host machine.
2. Download the [Vagrantfile](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-Crystal/blob/master/build-vm/Vagrantfile) from [build-vm](https://github.com/SoftwareEngineeringToolDemos/FSE-2011-Crystal/tree/master/build-vm) directory to your machine.
3. In the host, cd into the directory that contains the Vagrantfile and run the command "vagrant up".

###Note:
* The VM boots up quickly and can be viewed from VirtualBox. But the "vagrant up" command runs up approximately for 20 - 30 minutes.
* The basebox on which this VM is built is Ubuntu Desktop 15.04.
* In case VM login details are required:

  Username: vagrant
  
  Password: vagrant

###Acknowledgements:
Used vagrant virtual box image of [ubuntu1504-desktop by box-cutter](https://vagrantcloud.com/box-cutter/boxes/ubuntu1504-desktop)
