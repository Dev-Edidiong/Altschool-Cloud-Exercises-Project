# Exercise 4

## Task: 
 
   **Install PHP 7.4 on your local linux machine using `ppa:ondrej/php package repo**

 Step 1: Run `vagrant up` to spin up VM  

 Step 2: Run `vagrant ssh`into VM
 
 Step 3: Install these depedencies using sudo privileges  `apt-get install software-properties-common` and `apt-transport-https -y`
 
 Step 4:Install `PHP` repository with sudo privileges- `sudo add-repository ppa:ondrej/php -y
 
Step 5: Ensure the apt-get repository is update by running `sudo apt-get update`

Step 6: Run `sudo apt-get upgrade`

Step 7: To install PHP 7.4,input `sudo apt-get install -y php 7.4 php7.4-common`

Step 8: Output of `php -v` is found below :

![]()






### How to Use Add-Apt-Repository Command


This is a `Python` script that allows one to add an `apt` repository to a `/etc/apt/resources.list` 

or a separate file in the `/etc/apt/sources.list.d` directory.

This command is an utility included in the `software-properties-common`package.

It has a syntax `add-apt-repository [options] repository`.

Repository here can be a regular repository entry that can be added to the sources list file like `deb http://repo.tld/ubuntu distro`component

or a PPA repository in the `ppa:<user>/<ppa-name>` format.


## How to access /etc/apt/resources.list

Step 1: Run `vagrant up` to spin up VM.  

Step 2: Run `vagrant ssh`into VM.
 
Step 3: Run `cat  /etc/apt/resources.list`.The ouput is 

![]()

 
 
