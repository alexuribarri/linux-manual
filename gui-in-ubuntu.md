##Step 1. Install tasksel
$ sudo apt update
$ sudo apt install tasksel

##Step2 Install the GUI

$ sudo tasksel install ubuntu-desktop

##Step3 Reboot

$ reboot

##Step 4 If GUI is not loading on reboor

$ sudo systemctl set-default graphical.target
