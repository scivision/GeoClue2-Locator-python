
## Prereqs

    apt install geoclue-2.0 python-gi gir1.2-gtkclutter-1.0 gir1.2-gtk-3.0 gir1.2-gtkchamplain-0.12

Then you can run

    /usr/bin/python where-am-i.py


It will print your location and exit after 10 seconds.



## Notes

### Code runs but the location doesn't get printed

Run `geoclue` executable as root in another terminal.
Location of the executable is in `org.freedesktop.GeoClue2.service` file
