# xv6 Installation Instructions for Mac

1. **Install Homebrew** (if not already installed):
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. **Install Required Packages:** (this step might take time)
   ```bash
   brew install qemu gcc i386-elf-gcc i386-elf-binutils gdb
   ```

3. **Clone the xv6 repository:**
   ```bash
   git clone https://github.com/sakshamrathi21/CS236-Spring-2025-Labs
   cd xv6-mac
   ```

4. **Compile xv6:**
   ```bash
   make clean
   make
   ```

5. **Start the QEMU emulator:**
   ```bash
   make qemu
   ```

---

It is recommended that you create separate copies of this xv6 folder for every problem you solve (so that you do not disturb the original files).


In case you face any issues in the above steps, then please contact: Saksham Rathi (Mail: 22b1003@iitb.ac.in ; WhatsApp: +91-6375-66-3539). In the worst case, you will have to use lab machines through ssh for using xv6 (which isn't really tough).