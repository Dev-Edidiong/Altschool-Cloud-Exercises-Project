# Exercise 1

## Task:

### Setup of Ubuntu 20.04 LTS on my local machine using vagrant.


Following the instructor's steps on LMS,I was able to successfully setup ubuntu 20.04 LTS on my machine  by firstly,downloading and installing virtualbox then the necessary settings were enabled.

From vagrantup website,I downloaded vagrant and configured with recommended version of ubuntu via the box.

Running an **ls-al** command gave an ouput of a list of all my hidden files and directories.

A screenshot of my vagrantfile is found below:


![vagrantfile](https://github.com/Dev-Edidiong/Altschool-Cloud-Exercises-Project/blob/07653403998382df5a7793979dbdfe14f9e58e5d/Exercise%201/vagrantfile.png)

### Customization of Vagrant file

The customization of vagrant file as required was achieved by editing the vagrantfile using nano editor.

I replaced on the line that has **private_network, ip:"192.168.33.10" with private_network, type: dhcp**

I ran **vagarant ssh** to connect the VM using SSH ,installed net-tools then ran **ifconfig** and the output was the screenshot below:

![ifconfig](https://github.com/Dev-Edidiong/Altschool-Cloud-Exercises-Project/blob/bf3dfa20f271dc40b795da8027c4b1d21abe04ae/Exercise%201/ifconfig.png)
