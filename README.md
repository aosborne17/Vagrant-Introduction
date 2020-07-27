
## How to open and use Linux Virtual Machine
First open git bash and make your way to the folder where the vagrant file is located,
On my PC this is C:\vagrant


vagrant up

vagrant status

vagrant ssh

sudo apt-get update -y

nano name_of_file allows us to create a new file within the linux command line

touch nameoffile allows us to create a file in linux
mkdir nameofdirectory allows us to create a directory

how to go inside a directory cd nameofdir
how to exit a directory -- "cd -"
how to return to the root directory -- "cd /"
 
- Sudo works by allowing us to run a command in admin

Where am I? - pwd command shows the current file location
Who am I? -
What do I have in the current directory? ls is the command for this, shows available files
How to find hidden files in a directory? - ls -a (a stands for all)
How to find the name of operating system? we use 'uname' 
- apt-get is a package manager where we can update/install packages
- the -y means that we will not be prompt whether we want to download something or not, the default is yes

vagrant halt
vagrant destroy
vagrant reload
