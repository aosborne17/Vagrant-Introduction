## Running the Node App VM

package managers used in VMs and modules used in Python technically do the same thing, they both 
import functionalities in which we cab use
rake spec runs the test written in ruby in the rake file
sudo apt-get install -y must be ran first before we attempt to install nginx

sudo apt-get install nginx

systemctl status nginx

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

We then enter theapp folder from within our VM and do npm install,
this installs the dependencies needed to run the app.js file

ctrl C to stop app


chmod +x nameoffile --> this makes a file executable for us
We can then do ./nameoffile ---> this will run the file 

.sh is an extension for shell script

DevOps is all about automating things

How do we do this? Automation!

```bash
inside of our nginx_installation_script.sh file
#!bin/bash  --> this must be on the first line!!

sudo apt-get update
sudo apt-get install nginx
sudo apt-get upgrade
```

So now when we run this script, all of these commands would be automatically ran


sudo apt-get remove nginx --> This can then be run to uninstall nginx, and then redownload
using automation