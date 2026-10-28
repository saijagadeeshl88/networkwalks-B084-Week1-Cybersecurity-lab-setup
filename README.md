Cybersecurity lab setup

I have completed the installation of kali linux by the following steps:

This installation process involves with three steps I. II. III.

Installing oracle virtual machine application ‘Virtual box’ Installing Kali linux for Virtual Machine Configuring Kali linux with Virtual Machine

Step1: Installing oracle virtual machine application ‘Virtual Box’ 1.) To install Virtual box use the following link https://www.virtualbox.org/wiki/downloads

2.) Here, Identify the Virtual box 6.1.22 platform packages and click Windows Hosts if you are using windows operating system and OS X hosts if you are using a mac OS.

3.) The executable file will be downloaded after which you have to run the installation process

4.) Now, make sure you also complete the downloading process of extension pack for this Oracle VM before starting the oracle VM installation.

5.) Identify, ‘Virtual Box 6.1.22 Oracle VM Virtual Box Extension pack’ menu and click ‘All supported platforms’ to complete the download process of the extension pack in order to support the use of USB inside the virtual machine

6.) Now click the executable file downloaded earlier to complete the virtual box installation process along with the support of extension pack. Step

2 **Installing Kali linux for Virtual Machine **

1.) To install Kali linux use the following link https://www.kali.org/get-kali/

2.) Now, click Virtual machines tab, which will redirect you to the versions of kali linux supported VMs including VMware and Virtual Box for 32 and 64 bits accordingly

3.) As we are utilizing virtual box, we must select virtual box option either 32 bit or 64 bit based on your system configuration.

4.) An Executable .ova (open virtual appliance) file will be downloaded for installation/importing in the Virtual box

5.) Click that file to open the Kali linux environment and to start importing the files and packages into the Virtual box application as an Instance

6.) After importing process is completed, we need to set up the kali linux instance before starting the instance in the Virtual box. Step 3:

Configuring Kali linux with Virtual Machine

1.) In Settings tab, under ‘General’, make sure that the version is set to Debian (64 bit) for a 64 bit configuration.

2.) In the ‘Systems’ section, under ‘Motherboard’, make sure you allocate atleast 2 GB RAM as a base memory dedicated for kali linux

3.) In the ‘Network’ section, under ‘Adapter 1’, make sure to enable the adapter and at the same time ensure the adapter is attached to NAT (Network address translation).

4.) Now, after this configuration, click the ‘Start’ button to initialize the Kali linux environment.

5.) Here, you will be prompted to use credentials in order to gain access to the interface, where the default username and password is ‘Kali’ through which you can login in the operating system.

6.) After this, the mouse and the keyboard in your host machine will be configured automatically to be used in the virtual environment.

7.) Now, in this interface you can explore plethora of options and predefined packages and tools for various requirements.

8.) The terminal is the place where we execute the commands for Kali linux, such as displaying directories, folders, creating and managing the users, updating and upgrading the interface packages and installing missing packages and so on.

9.) Various tools can be installed using commands and packages such as python based on the requirements and demands.
