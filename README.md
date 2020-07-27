Note that Linux is a blank screen, there is no user interface


## How to open and use Linux Virtual Machine
First open git bash and make your way to the folder where the vagrant file is located,
On my PC this is C:\vagrant


vagrant up

vagrant status

vagrant ssh

sudo apt-get update -y

- Sudo works by allowing us to run a command in admin
- apt-get is a package manager where we can update/install packages
- the -y means that we will not be prompt whether we want to download something or not, the default is yes

vagrant halt
vagrant destroy
vagrant reload