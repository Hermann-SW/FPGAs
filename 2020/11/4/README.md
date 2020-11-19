## 11/4/2020

I registered at Xilinx for being able to download&install "ISE Design Suite - 14.7  Full Product Installation" last updated October 2013 (Full Installer for Linux). I will use this for the older Spartan6 FPGAs:  
[https://www.xilinx.com/downloadNav/vivado-design-tools/archive-ise.html](https://www.xilinx.com/downloadNav/vivado-design-tools/archive-ise.html)

After extracting the tar file, I did run ./xinfo and ./xsetup, and selected "ISE Designe Suite System Edition".  
I installed on external SSD instead of default "/opt/Xilinx".

Linux executables are for Intel CPUs, cannot be run on Raspberry PIs:

    $ file mnt/Xilinx/14.7/ISE_DS/ISE/bin/lin64/ise
    mnt/Xilinx/14.7/ISE_DS/ISE/bin/lin64/ise: ELF 64-bit LSB executable, x86-64, version 1 (SYSV), dynamically linked (uses shared libs), for GNU/Linux 2.6.9, stripped
    $ file mnt/Xilinx/14.7/ISE_DS/ISE/bin/lin/ise
    mnt/Xilinx/14.7/ISE_DS/ISE/bin/lin/ise: ELF 32-bit LSB executable, Intel 80386, version 1 (SYSV), dynamically linked (uses shared libs), for GNU/Linux 2.6.9, stripped
    $


