#
### Exercise 1

## Task:

### Setup of Ubuntu 20.04 LTS on my local machine using vagrant.

#### Steps:


Following the instructor's steps on LMS,I was able to successfully setup ubuntu 20.04 lts on my machine by firstly,downloading and installing virtualbox then the necessary settings were enabled.

From vagrantup website ,I downloaded vagrant and configured with recommended version of ubuntu via the box.

Running an ls-al command gave an ouput of a list of all my hidden files and directories.A screenshot of my vagrantfile is found below:


![ifconfig](https://imgur.com/59dqlk9) 



## Customization of Vagrant file

#### Steps

The customization of vagrant file as required was achieved by editing the vagrantfile using nano editor.

I replaced on the line that has private_network,ip:"192.168.33.10" with private_network,type:dhcp

I ran vagarant ssh and ifconfig and the output was the screenshot below

![vagrantfile](https://imgur.com/Qb3tL86)



