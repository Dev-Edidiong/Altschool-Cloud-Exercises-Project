#
 
## Exercise 2

### Task :

**A list of ten Linux commands with screenshots**


<<<<<<< HEAD
## uname -a

 **uname** simply means Unix name. Here Uname command with **(-a)** option simply prints all the system information 

 in the following order : Kernel name, Network node host name, kernel release date, kernel version, machine hardware name, hardware platform, operating system.  

 ![ uname -a](https://imgur.com/a/NYgnKYb"linux command 1")


## env

 It is used to print out a list of all environmental variables 

![env](https://imgur.com/j7F0nVL"linux command 2")
=======
Following the instructor's steps on LMS,I was able to successfully setup ubuntu 20.04 lts on my machine by firstly,downloading and installing virtualbox then the necessary settings were enabled.

From vagrantup website ,I downloaded vagrant and configured with recommended version of ubuntu via the box.

Running an **ls -al** command gave an ouput of a list of all my hidden files and directories. A screenshot of my vagrantfile is found below:


![ifconfig](https://github.com/Dev-Edidiong/Altschool-Cloud-Exercises-Project/blob/33769e2870f71e79454894ff1fb13809ac382451/Exercise%201/ifconfig.png) 
>>>>>>> 919ab9b5954c9ed5b7420ac220b09162e1079fe0



 **History**

 This command is basically used to view the previously executed Command. It shows a whole list of the command. 

<<<<<<< HEAD
 ![history](https://imgur.com/aFq1oWB"linux command 3")


 

## ps ax 

 The command **ps** means process status. It is used to inspect all the computer running processes at all times.

 However the **"ax"** option together with ps means that option **"a"** lists other users processes not just one's own while **"x"** option shows processes not linked to any terminal in other words processes not initiated by users through a terminal. 

 ![ ps ax](https://imgur.com/UfkuTa6"linux command 4")





## top 

 This command is used to display dynamic real information about running processes in the system


 ![ top](https://imgur.com/OX3P2Ak"linux command 5")






## demidecode 

 This command is rendered to as Desktop Management Interface table decoder, record data from DMI table and produce it in human readable format.

 Without options, this command displays system's hardware related information such as processes, Ram(DIMMs), Bios detail, memory, serial numbers etc. 

 ![demidecode]( https://imgur.com/JOHU81z"linux command 6")



## pstree

 This command shows the running processes as a tree but in a hierarchical format. 

 ![pstree](https://imgur.com/RqlSehT"linux command 7")




## Id

 The **Id** command without options shows the ID of current user UID and GID

 ![Id](https://imgur.com/XTlLwNl"linux command 8")





## df

 **df** as a command without options displays the space available on all currently mounted file system

 ![df](https://imgur.com/kbKByE6"linux command 9")




## findmnt

 It is a command line tool in Linux, it lists the all-mounted file system on the system 

 ![findmnt](https://imgur.com/iqWHikx"linux command 10")
=======
The customization of vagrant file as required was achieved by editing the vagrantfile using nano editor.

I replaced on the line that has **private_network, ip:"192.168.33.10" with private_network, type: dhcp**

I ran vagarant ssh and ifconfig and the output was the screenshot below :

![vagrantfile](https://github.com/Dev-Edidiong/Altschool-Cloud-Exercises-Project/blob/33769e2870f71e79454894ff1fb13809ac382451/Exercise%201/ifconfig.png)
>>>>>>> 919ab9b5954c9ed5b7420ac220b09162e1079fe0



