# Vagrant

## What is Vagrant

- Vagrant is a Vagrant is a tool for building and managing virtual machine environments in a single workflow 
with an easy-to-use workflow and focus on automation.

![Diagram](images/VM_Vagrant_Diagram_automating_Node.png)

## Installing the Dependencies Necessary 

In order to run our Virtual Machine we would need to download these softwares, we have specified specific versions to install
as the project has already been trialled and tested on these versions, thus removing the chances of any unknown errors

### Ruby
 
 For this demonstration we will download Ruby version 2.6.6 which can be downloaded
 [Here](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.6.6-1/rubyinstaller-devkit-2.6.6-1-x64.exe)

### Vagrant 

Install vagrant version 2.2.7, click [Here](https://releases.hashicorp.com/vagrant/) 
ensuring you download the correct software for your Operating System

### Virtual Box

Vagrant uses VirtualBox to actually create the virtual machine, we want to download version 6.1 
[Here](https://www.virtualbox.org/wiki/Downloads)
## How to open and use Linux Virtual Machine Step By Step

- First open git bash and make your way to the folder where the vagrant file is located,
On my PC this is C:\vagrant

- Then within this folder do 'vagrant up', which runs our VM

- We can run 'vagrant status' which would tell us the status of our VM

- Once the VM is running we then use 'vagrant ssh' which is what allows us to access the VM

### Other commands that can be run on our vagrant file
- vagrant halt -- This pauses the VM

- vagrant destroy -- this command is used to stop the running of the VM and remove traces
of the VM on our system

- vagrant reload -- This reruns the VM, thus if we have made changes to the vagrant
file we would need to reload the VM to see those changes in effect


Note that Vagrant files are written in Ruby

Once inside the VM, the operating system is Linux and thus linux commands must be used



