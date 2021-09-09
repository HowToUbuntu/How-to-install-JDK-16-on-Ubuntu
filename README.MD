![Ubuntu Java 16.jpg](https://cdn.devdojo.com/images/september2021/ubuntu-java-161.jpeg)

First of all JDK 16 is the open-source reference implementation of version 16 of the Java SE Platform, as specified by by JSR 390 in the Java Community Process. JDK 16 reached General Availability on 16 March 2021. Production-ready binaries under the GPL are available from Oracle; binaries from other vendors will follow shortly.

Well lets begin!

This tutorial is very simple and will show a install and unistall process of JDK 16!

Time to INSTALL! (remember to unistall all past JDK versions)

---
Install commands
```
sudo add-apt-repository ppa:linuxuprising/java
```
Press enter when it tells you.

This may take a while or very short amount of time.

```
sudo apt update
```
This now will take a while.

This command will now install JDK 16
```
sudo apt install oracle-java16-installer
```
Press y when it prompts you

Wait 1-5 minutes max

And you are done!

To test go to your terminal and type
```
java --version
```
![5783e68f1da9cf78fd691cc82a562c6a.png](https://cdn.devdojo.com/images/september2021/5783e68f1da9cf78fd691cc82a562c6a.png)

That is all for installation!

---
When JDK 17 comes out fully maybe you want to unistall JDK 16 to install JDK 17

The first command to unistall is 
```
sudo add-apt-repository --remove ppa:linuxuprising/java
```
This may take a a little amount of time or a while

```
sudo apt-get remove oracle-java16-installer
```
This command will usually take as long as the installation.

Once its done try typing in the command
```
java --version
```
You will get a error message!

---

That is all for Installing/Unistalling JDK 16. Try doing this on other Linux Distros to see if it works. I only tested Ubuntu and Debian. The Ubuntu Server Distro will also work!

# If you found this usful then please comment and follow me! Also check out [my website where I also post everything from here](https://howtoubuntu.xyz)