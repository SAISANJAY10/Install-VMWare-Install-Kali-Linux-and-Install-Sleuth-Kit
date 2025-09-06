# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Reg.No : 2122223040178
### Name : SAI SANJAY R
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## DESIGN STEPS:

### **Step 1: Install  VM ware Worskstation**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualMAchine Ware Workstation website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VMware to verify the installation.


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

<img width="1918" height="1076" alt="Screenshot 2025-09-06 140115" src="https://github.com/user-attachments/assets/c79e73e8-a840-467b-86da-469c78827918" />
<img width="950" height="1071" alt="Screenshot 2025-09-06 142012" src="https://github.com/user-attachments/assets/9c6341b0-6f6a-4cc7-84c0-bdd09a03814e" />
<img width="952" height="1077" alt="Screenshot 2025-09-06 142251" src="https://github.com/user-attachments/assets/65b2bff6-9a8f-4a49-a8d3-516af9a16527" />
<img width="1474" height="678" alt="Screenshot 2025-09-06 143345" src="https://github.com/user-attachments/assets/982cd0e5-28d8-4191-b361-34bc65a83a44" />


## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
