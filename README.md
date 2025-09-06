# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Name:Yendluri Chandana
### Reg No: 212223100063
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
<img width="1916" height="1014" alt="image" src="https://github.com/user-attachments/assets/4fd66c7f-61e6-464a-8a8d-a8cf14c21ec3" />


**KALI LINUX:**

![WhatsApp Image 2025-09-06 at 13 19 46_076eaa87](https://github.com/user-attachments/assets/ed657e42-37ea-4427-970e-a476abec72d6)


**SLEUTH-KIT:**
![WhatsApp Image 2025-09-06 at 13 20 14_64013741](https://github.com/user-attachments/assets/e74828db-fcd2-48bf-bc77-8b66bfd96f88)



## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
