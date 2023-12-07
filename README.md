# Qidi-X-Smart-3-Klipper-Config
My config files for my Qidi X-Smart 3

# Important
My changes are to improve the printer and control via Mainsail / Fluidd. 
My config will break things on the screen.
Example: I have re-done the fans so fan control on the screen is no longer needed.

I don't care about the screen except for Monitoring and being able to stop a print.

## Changes to base system

# Setup mkspi so datetime is updated
```
sudo apt install ntp
sudo dpkg-reconfigure tzdata
sudo systemctl start ntp
sudo systemctl enable ntp
```

# I have added these symbolic links
```
mks@mkspi:~/printer_data$ ls -la
total 8
drwxr-xr-x  2 mks mks 4096 Dec  6 20:29 .
drwxr-xr-x 35 mks mks 4096 Nov 20 20:34 ..
lrwxrwxrwx  1 mks mks   24 Nov 15 15:36 config -> /home/mks/klipper_config
lrwxrwxrwx  1 mks mks   29 Nov 15 15:37 database -> /home/mks/.moonraker_database
lrwxrwxrwx  1 mks mks   21 Nov 15 15:38 gcodes -> /home/mks/gcode_files
lrwxrwxrwx  1 mks mks   22 Nov 15 15:36 logs -> /home/mks/klipper_logs
```

# I have installed KAMP from the command line

# I have installed Mainsail using KIAUH (Not got webcam working in Mainsail yet)

# I have updated Fluidd using KIAUH (No issues found)

