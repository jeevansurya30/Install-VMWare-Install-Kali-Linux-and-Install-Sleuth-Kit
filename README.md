![WhatsApp Image 2025-09-06 at 14 21 35_63eb06a1](https://github.com/user-attachments/assets/e30ca93f-e844-458a-b7ed-106458b19f84)# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## DESIGN STEPS:

**Step 1: Install VirtualBox**

**Installation Steps:**

1.Download the Windows hosts .exe file from the official VirtualBox website.

2.Run the installer and follow the on-screen instructions.

3.Once installed, launch VirtualBox to verify the installation.


**Step 2: Install Kali Linux on VirtualBox**

🔗 Download Kali Linux VM: (https://www.kali.org/get-kali/#kali-platforms)


**Installation Steps:**

1.Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian 
(64-bit).

2.Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.

3.Go to Settings > Storage, click Empty under Controller: IDE.

4.Select Graphical Install, follow the prompts to set language, location, username, and password.

5.Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.



**Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**

🔗 Download Sleuth Kit: https://www.sleuthkit.org/


**Installation Steps:**

1.Download the Windows ZIP package from the official website.

2.Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).

3.Add the bin folder to Windows PATH:

    Open Control Panel → System → Advanced System Settings.
    
    Click Environment Variables → Edit Path.
    
    Add the Sleuth Kit bin folder path and save changes.
    
**Step 4.Verify installation by running:**

![image](https://github.com/user-attachments/assets/792b0c65-3121-4732-a4c4-d24655131ff5)



## OUTPUT:
```
Name: Jeevansurya k
Reg No: 212222040061
```
**VIRTUAL BOX:**


![WhatsApp Image 2025-09-06 at 14 21 35_63eb06a1](https://github.com/user-attachments/assets/a9250f06-e116-4797-8da6-7a82808b7069)




 
**KALI LINUX:**

![WhatsApp Image 2025-09-06 at 14 23 09_c3c9ca2a](https://github.com/user-attachments/assets/1e8e6cf1-0631-438a-b700-182fefaf7463)




**SLEUTH-KIT:**

<img width="1201" height="470" alt="Screenshot 2025-09-06 142112" src="https://github.com/user-attachments/assets/c8225cf0-1725-4a81-b680-da414ea63b33" />



## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
