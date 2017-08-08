## dev_ops_notes
It is related to devops

# Setting Up an Environment for Chef-Solo

## Using the Omnibus installer
The Omnibus installer is a full installation and an executable script.They provide the executable script to install packages and dependencies.

#### Execute the following script by using the following command:

##### For Mac should be instaling with root

```sh 
$sudo su-

sh-3.2#

 sudo curl -L https://www.opscode.com/chef/install.sh | bash
 ```
 # TIP
Curl utility is not installed by default. You can install by using the following command:

(ubuntu)
```sh 
$ sudo apt-get install curl 
```

 (Rehat, CentOS)
 ```sh 
 $ sudo yum install curl
 ```
 
 (Mac OSX)
 ```sh 
 $ brew install curl
 ```
