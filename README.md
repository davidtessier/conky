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

![Conky Screenshot](https://github.com/davidtessier/conky/blob/master/Screenshot%20from%202019-07-24%2016-14-53.png)

![image](https://github.com/user-attachments/assets/66ad9d98-ca32-40ce-8b66-b5f422dc2ad9)


# Set Conky To Start At Boot
Conky only becomes useful when it is set to start up at boot. Here's how in Ubuntu and the various respins.

## In Ubuntu/Unity:
Click the gear icon in the upper right hand corner of the top panel. Select Startup Applications. Click Add. In the resulting dialog box give the name as "Conky" and the command as conky. Click add and close.

## In Ubuntu/Gnome Shell
Press Alt+F2 to bring up the Run dialog. Type gnome-session-properties. Click the "Add" button. In the resulting dialog box give the name as "Conky" and the command as conky. Click add and close.
