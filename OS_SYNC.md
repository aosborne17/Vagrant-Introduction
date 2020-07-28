## Syncing files from our OS to be available on our VM

```
config.vm.synced_folder, ..
```
After having synced the node app onto our VM, we can then work with the app within the VM.

## Ensuring the Success Of a Project

Communication between the DevOps, testers and front end is key.

It is important to know what languages and frameworks different teams are using to implement their apps.
By knowing this, we would know what dependencies need to be downloaded for the app to work successfully

## Running the Node App VM

package managers used in VMs and modules used in Python technically do the same thing, they both 
import functionalities in which we cab use
rake spec runs the test written in ruby in the rake file
sudo apt-get install -y must be ran first before we attempt to install nginx

sudo apt-get install nginx

systemctl status nginx

sudo apt-get install git 

sudo apt-get install nodejs -y

Now we need to install npm and pm2

To do this we must first do "sudo su" to navigate to the root directory
Once here run "apt install npm"
Once npm is installed we can run "npm install -g pm2" 

"sudo apt-get install python-software-properties"
# this curl goes directly to the url
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -

sudo apt-get install -y nodejs

sudo npm install pm2 -g

sudo apt-get update --> this would install the whole source list



We then enter the app folder from within our VM and do npm install,
this installs the dependencies needed to run the app.js file

ctrl C to stop app


chmod +x nameoffile --> this makes a file executable for us
We can then do ./nameoffile ---> this will run the file (by adding this to our vagrant file, when our vagrant file runs
this execution would follow suit)
Only works for .sh extension files


.sh is an extension for shell script

### DevOps is all about automating things

How do we do this? Automation!
Automation involves using 
```bash
su#!bin/bash  --> this must be on the first line!!

sudo apt-get update
sudo apt-get install nginx
sudo apt-get upgrade
```

So now when we run this script, all of these commands would be automatically ran


sudo apt-get remove nginx --> This can then be run to uninstall nginx, and then redownload
using automation

top --> This commands shows all the programs running in the background,
a very powerful tool.ps --> this commands gives the programIF

### Changing directory permissions in Liunx

chmod +rwx filename to add permissions
chmod  -rwx directoryname to remove permissions
chmod +x or chmod -x --> This would either allow or remove executable permissions

chown --> change file ownership

```
cat nameoffile
```
cat stands for concatenate
Allows us to the check the content of the file without opening it
"r" ---> read
"w" ---> write
"x" ---> executable

This is beneficial where we would like others to read our files without the capabilites of editing them.
