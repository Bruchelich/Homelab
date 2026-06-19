https://community-scripts.org/scripts/nextcloud-vm
  
  🆔  Virtual Machine ID: 303
  📦  Machine Type: q35 - for newer hardware
  💾  Disk Size: 50G
  💾  Disk Cache: Write Through
  🏠  Hostname: nextcloud-vm
  🖥️  CPU Model: Host
  🧠  CPU Cores: 2
  🛠️  RAM Size: 2048

once VM is set up we set up turnkey OS

Install to disk

<img width="1555" height="379" alt="image" src="https://github.com/user-attachments/assets/2f2dc173-3f45-425f-bfd1-881ddad40071" />

then select the big juicy drive

change 90% disk usage to max

DO NOT install grub automatically 

boot loader should be isntalled on /dev/sda not /dev/sda1

Reboot

now right click and stop the VM

then merc the installation media

<img width="792" height="393" alt="image" src="https://github.com/user-attachments/assets/558a2dcf-2542-48a7-b698-8d8ba0ffc2c0" />

a disk at the bottom will say unused and then just kill it

now by default it's using American keyboard so setting password is fun 

MY RECOMMENDATION: just ignore the fact that it's a different keyboard layout and stick to whatever works

then just go with the flow 

Enter domain: whatever IP u want it on

fuck API Key, fuck emails from turnkey

then install updates :D

REBOOT

log in with 
username: admin
password: *********

then go to /index.php/settings/admin/overview and updateeee
