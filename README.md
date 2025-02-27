Just put this in your systemd service and enable it and setup the service with correct location of your bash file and then it should work out of the box.
Note: You may need notification libraries if you are using it with something like tuf-fan-notification-git I was using inotify-tools, libnotify and dunst in my test case on Asus TUF FX506LH
