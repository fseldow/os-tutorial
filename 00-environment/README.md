*Concepts you may want to Google beforehand: linux, mac, terminal, compiler, emulator, nasm, qemu*

**Goal: Install the software required to run this tutorial**

I'm working on a Mac, though Linux is better because it will have all the standard tools already
available for you.

On Ubuntu, `sudo apt install nasm`, `sudo apt-get update`, and then `sudo apt-get install qemu` to install *nasm and qemu*.

Don't use the Xcode developer tools `nasm` if you have them installed, they won't work for the most cases. Always use `/usr/local/bin/nasm`

qemu is split into multiple binaries. Need 
to call `qemu-system-x86_64 binfile`  
Or run `sudo mv /usr/bin/qemu-system-x86_6
4 /usr/bin/qemu`. The following tutorial assumes you have renamed it.
