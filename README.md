# osFinal
Step-by-step task completion:

Task 1:
Screenshots of the code compilation result:
![image](https://user-images.githubusercontent.com/93382898/221348807-411d468c-9dec-4087-b8c3-ddc4250845e2.png)
![image](https://user-images.githubusercontent.com/93382898/221348811-42621a3c-daa8-489e-ae4a-15eca2c9a45f.png)

 
 

With the help of the SUDO -I command, we went into root, then added new users and created passwords for them. In the created user, we logged in and to show how we logged in, used “whoami’ and exited with the exit command

Task 2:
Screenshots of the code compilation result:
![image](https://user-images.githubusercontent.com/93382898/221348817-c0aae872-479c-4a61-add3-f892fae84fcb.png)
![image](https://user-images.githubusercontent.com/93382898/221348821-2bc3ea8d-dffe-4cd9-9c46-15458c0b2412.png)
![image](https://user-images.githubusercontent.com/93382898/221348822-a77c097c-99ef-4757-bb19-2463231cf192.png)
![image](https://user-images.githubusercontent.com/93382898/221348825-3a02c593-4334-4163-8b08-9819f0049b3d.png)
 
 
 
 

In task 2 we in task 2 we see a direct connection to Yandex using IPa direct connection to Windows IP. There is also a second part where we changed the network configuration connection, then we tried to connect using google.com

Task 3:
Screenshots of the code compilation result:
 ![image](https://user-images.githubusercontent.com/93382898/221348830-c9d7825f-8620-4ae1-8889-0380beb3f80f.png)

We have created a new block sr0 and checked it
![image](https://user-images.githubusercontent.com/93382898/221348833-8f3020be-291e-4d2f-aa4e-f52aedd3b117.png)

 

Firstly, we downloaded core from the website linux kernel archive

![image](https://user-images.githubusercontent.com/93382898/221348837-8ef5a3be-b90c-4a68-b398-561e4bbcc292.png)
 

As you can see we downloaded our core successfully, and then we had unpacked our linux core. Secondly, we should install necessary libraries and instruments, by command "apt install build-essential libncurses-dev bison flex libssl-dev libelf-dev", also "apt install isolinux genisoimage"
![image](https://user-images.githubusercontent.com/93382898/221348852-b9dca1af-6b5e-4d4e-b498-a699abb5d1ce.png)

 

To have some changes from our current core we changed some configurations in file systems. We had decided to change file system because it is easiest way to change something and don't broke a new core
![image](https://user-images.githubusercontent.com/93382898/221348856-6d1c6736-27e4-4793-864a-a2993e6d3636.png)
![image](https://user-images.githubusercontent.com/93382898/221348861-a7cfac43-77c8-40df-87bd-1cd8ef2f0245.png)

 

 

By command "make -j8 isoimage" , we finished creating our linux core
![image](https://user-images.githubusercontent.com/93382898/221348870-2dc46afb-bdbb-4aa1-b0dd-391650c5890f.png)

 

But when we play our core on oracle, we take the error, because we should so many functions to make core running
