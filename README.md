# My conky configuration

On Ubuntu, install Conky with the following commands: 
```
sudo apt update
sudo apt install conky-all
```

Then, backup the default conky.conf file:
```
sudo cp /etc/conky/conky.conf /etc/conky/conky.conf.bak
```

Then, replace the contents of `/etc/conky/conky.conf` with the contents of the ![conky.conf](https://github.com/davidtessier/conky/blob/master/conky.conf) file from this repository. 
```
sudo gedit /etc/conky/conky.conf
```
# Screenshot

![image](https://github.com/user-attachments/assets/19f6266a-f7a4-48b1-bd0b-ff4db46fbdff)

# Set Conky To Start At Boot
Conky only becomes useful when it is set to start up at boot. Here's how in Ubuntu and the various respins.

## In Ubuntu/Unity:
Click the gear icon in the upper right hand corner of the top panel. Select Startup Applications. Click Add. In the resulting dialog box give the name as "Conky" and the command as conky. Click add and close.

## In Ubuntu/Gnome Shell
Press Alt+F2 to bring up the Run dialog. Type gnome-session-properties. Click the "Add" button. In the resulting dialog box give the name as "Conky" and the command as conky. Click add and close.
