# level9-interpreter-snap
Code to «snapify» this interpreter made to work on gtk2.

##Build
Install snapcraft: [https://snapcraft.io/create/]https://snapcraft.io/create/
Clone and `cd` into the folder of the project
`snapcraft`

##Installation
###Local copy
`sudo snap install ./level9_X.X_amd64.snap --devmode`

###Remote copy
TBD

Run
type `level9.glklevel9`

##Errors known
When running terminal shows:
```
(process:2165): Gtk-WARNING **: Locale not supported by C library.
	Using the fallback 'C' locale.
Gtk-Message: Failed to load module "unity-gtk-module"
Gtk-Message: Failed to load module "canberra-gtk-module"
Gtk-Message: Failed to load module "canberra-gtk-module"
```
Is it from snappy?
