# osFinal
Step-by-step task completion:

Task 1:
Screenshots of the code compilation result:
![image](https://user-images.githubusercontent.com/93382898/221348788-b83a2124-179f-4381-ade0-b91167560e0a.png)

 
 

With the help of the SUDO -I command, we went into root, then added new users and created passwords for them. In the created user, we logged in and to show how we logged in, used “whoami’ and exited with the exit command

Task 2:
Screenshots of the code compilation result:
 
 
 
 

In task 2 we in task 2 we see a direct connection to Yandex using IPa direct connection to Windows IP. There is also a second part where we changed the network configuration connection, then we tried to connect using google.com

Task 3:
Screenshots of the code compilation result:
 
We have created a new block sr0 and checked it

 

Firstly, we downloaded core from the website linux kernel archive

 

As you can see we downloaded our core successfully, and then we had unpacked our linux core. Secondly, we should install necessary libraries and instruments, by command "apt install build-essential libncurses-dev bison flex libssl-dev libelf-dev", also "apt install isolinux genisoimage"

 

To have some changes from our current core we changed some configurations in file systems. We had decided to change file system because it is easiest way to change something and don't broke a new core

 

 

By command "make -j8 isoimage" , we finished creating our linux core

 

But when we play our core on oracle, we take the error, because we should so many functions to make core running
