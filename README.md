# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Name: K.JEEVANSURYA
### Reg No: 212222040061
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version
   
## PROGRAM:

## OUTPUT:
**VIRTUAL BOX:**
<img width="1301" height="844" alt="image" src="https://github.com/user-attachments/assets/7e93c9db-1fda-44c1-8fbe-f15e6f7c3263" />
<img width="1302" height="834" alt="Screenshot 2025-08-15 181641" src="https://github.com/user-attachments/assets/45da0fad-b37b-4a3b-9e73-df89e72f9dc2" />


**KALI LINUX:**
<img width="1774" height="909" alt="Screenshot_2025-08-15_08_45_31" src="https://github.com/user-attachments/assets/b6902228-ab35-473f-80ff-172d9ecea9ca" />
<img width="1920" height="944" alt="Screenshot_2025-08-15_08_48_29" src="https://github.com/user-attachments/assets/67818017-1de8-457b-ae77-46d62038b329" />



**SLEUTH-KIT:**

<img width="1482" height="757" alt="image" src="https://github.com/user-attachments/assets/8f6e56c4-c178-48a7-bd56-4c810f133e34" />
<img width="1482" height="756" alt="image" src="https://github.com/user-attachments/assets/63f3ad69-fdea-41bb-be4a-ed0a4519571a" />


## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
