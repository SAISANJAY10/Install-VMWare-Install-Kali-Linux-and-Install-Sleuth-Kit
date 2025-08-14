# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Reg.No : 2122223220027
### Name : Guru Raghav Ponjeevith V
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## DESIGN STEPS:

### **Step 1: Install  VM ware Worskstation**

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


## OUTPUT:
### VIRTUAL MACHINE :

<img width="1919" height="994" alt="image" src="https://github.com/user-attachments/assets/1ca68175-9aa3-4f67-889a-08e78c17d97c" />


### KALI LINUX:
<img width="1296" height="607" alt="image" src="https://github.com/user-attachments/assets/84c9f9cf-e7d7-4f83-910e-c1872097349d" />

### SLEUTH KIT:

<img width="1422" height="112" alt="image" src="https://github.com/user-attachments/assets/804b5f46-6f90-46e0-8fc9-3c52f14ede21" />

## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
