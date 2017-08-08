# dev_ops_notes
It is related to devops

# Setting Up an Environment for Chef-Solo

        Using the Omnibus installer
The Omnibus installer is a full installation and an executable script.They provide the executable script to install packages and dependencies.

Execute the following script by using the following command:

For Mac should be instaling with root 
# $sudo su-
sh-3.2#
 sudo curl -L https://www.opscode.com/chef/install.sh | bash
 
TIP
Curl utility is not installed by default. You can install by using the following command:

$ sudo apt-get install curl (ubuntu)
$ sudo yum install curl (Rehat, CentOS)
$ brew install curl (Mac OSX)
