# Vagrant

## What is Vagrant

- Vagrant is a Vagrant is a tool for building and managing virtual machine environments in a single workflow 
with an easy-to-use workflow and focus on automation.

![Diagram](images/VM_Vagrant_Diagram_automating_Node.png)

## Downloading the Dependencies Necessary

In order to run our Virtual Machine we would need to download these softwares

### Ruby
 

### Vagrant 

Ensure to install vagrant version 2.2.7, click [Here](https://releases.hashicorp.com/vagrant/) ensuring you download the correct software for your Operating
System

### Virtual Box


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



