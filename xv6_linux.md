# xv6 Installation Instructions for Linux

1. **Install qemu** 
   ```bash
   sudo apt-get install qemu-system
   ```

   To download and clone from git 
   ```
   git clone https://gitlab.com/qemu-project/qemu.git
   cd qemu
   ./configure
   make
   ```

   Refer website for more details [click here.](https://www.qemu.org/download/#source)

2. **Clone the xv6 repository:**
   ```bash
   git clone https://github.com/sakshamrathi21/CS236-Spring-2025-Labs
   cd CS236-Spring-2025-Labs/xv6-mac
   ```

    In the below cases, make sure to remove the -Wall flag from the MakeFile.

    
   Alternatively download tarball from [OS course webpage](https://www.cse.iitb.ac.in/~mythili/os/) or clone the latest version of xv6 from the repo 
   
      ```bash
   git clone https://github.com/mit-pdos/xv6-public
   ``` 

5. **Compile xv6:**
   ```bash
   make clean
   make
   ```

6. **Start the QEMU emulator:**
   ```bash
   make qemu
   ```
7. **User tests:** (for testing)

   A separate window will pop up (displaying the qemu emulator window). Run the following command:
   ```bash
   usertests
   ```
   If the following command displays "All tests passed", then you are good to go.


---

It is recommended that you create separate copies of this xv6 folder for every problem you solve (so that you do not disturb the original files). If applicable, directly copy the templates files using the `mv` command into a fresh copy of the xv6 folder. 
