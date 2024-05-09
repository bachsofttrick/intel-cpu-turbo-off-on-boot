# Disable Turbo Boost in Intel CPU
This is a script to disable Turbo Boost on boot of Linux system. 
Set chmod +x setcputurbooff.
Copy powersaves.rules to /etc/udev/rules.d/, setcputurbooff to anywhere and change RUN+ to location of your setcputurbooff script.
[Source](https://superuser.com/questions/1417292/udev-rule-to-start-a-command-on-ac-battery-plug-unplug-event)
