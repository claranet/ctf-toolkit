# ctf-toolkit
A toolkit collection for CTF challenges

Each security domain has its own folder containing:
- a reference **README.MD**
- any files/scripts we deemed useful

## CTF environment setup

we strongly suggest using the kali distribution https://www.kali.org/

For **windows** follow these steps:
1. install [VMware Workstation Player](http://www.vmware.com/go/tryplayerpro-win-64-fr)
2. pick up an existing Kali image for VMWare, for example through [osboxes.org](http://www.osboxes.org/kali-linux/)
3. create a VM using the provided image
4. configure the correct os type (debian) for the VM through settings > advanced
5. connect with credentials, remember to watch for qwerty keyboards
    - kali: root/toor
    - osboxes.org: root/osboxes.org
6. install and configure the vmware tools on the running image (this enables fullscreen, copy/paste and other good stuff)
    - copy the cd media to any folder with read/write perms
    - unpack the vmwaretool archive
    - execute the perl script in the unpacked archive and leave most options to default **CAREFUL: you may want to think twice about sharing files & network with the host machine for malware CTF challenges**
7. stop the running VM and enable hardware acceleration through the VM settings' menu
8. enjoy and go fetch some flags!

For **linux** well ... you know what to do :) !
