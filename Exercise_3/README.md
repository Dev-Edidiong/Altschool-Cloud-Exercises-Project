# Exercise 3

## Task :


**Create 3 groups -admin,support & engineering and add the admin group to sudoers**

Step 1 : Run `vagrant ssh` into the VM

Step 2 : Create an admin group by using sudo privilege to run `sudo groupadd admin`,output - admin already exists!

Step 3 : Create support and engineering groups using sudo privileges by running `sudo groupadd support`  `&&` `sudo groupadd engineering`

Step 4 : Run `sudo tail  /etc /group` to display below:

![etc.group]() 

Step 5 : Since the admin group already exists,it implies the admin group is already in the sudoer's file

Step 6 : Run `sudo visudo /etc / sudoers`to edit the sudoer's file 

Step 7 : Inside the file,locate and modify **%admin ALL=(ALL)ALL** to **ALL=(ALL:ALL)ALL**

Step 8 : Run `sudo tail  /etc/sudoers`.It displays the output below:

![etc.sudoers]() 


**Create a user to each group**

Step 1: Using sudo privileges,run `sudo useradd -g admin -m -s /usr/bin/bash Rose` to add Rose to admin group

This implies that user rose should be added to aan admin group,with a home directory and has a bash shell

Step 2: Run `sudo useradd -g support -m -s /usr/bin/bash  Johnson`  to add Johnson to Support group

Step 3 Run `sudo useradd -g engineering -m -s /usr/bin/bash Linda` to add Linda to Engineering group 

Step 4: Run `sudo tail /etc /passwd`.This returns the output below:

![etc.passwd]()


**Generate SSH KEY for the user in the admin group**

Step 1: Using sudo privilege, run `sudo su - rose`

Step 2: Run `ssh-keygen`,this generates both public and private keys for Rose respectively.
 












