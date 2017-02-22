# level9-interpreter-snap
Code to «snapify» this interpreter made to work on gtk2.

##Build
Install snapcraft: https://snapcraft.io/create/

Clone and `cd` into the folder of the project
`snapcraft`

##Installation
###Local copy
`sudo snap install ./level9_X.X_amd64.snap --devmode`

###Remote copy
TBD

###Run
type `level9.glklevel9`

##Errors known
When running terminal shows:
```
(process:2165): Gtk-WARNING **: Locale not supported by C library.
	Using the fallback 'C' locale.
Gtk-Message: Failed to load module "unity-gtk-module"
Gtk-Message: Failed to load module "canberra-gtk-module"
Gtk-Message: Failed to load module "canberra-gtk-module"

(gtklevel9:2071): dconf-WARNING **: failed to commit changes to dconf: GDBus.Error:org.freedesktop.DBus.Error.AccessDenied: An AppArmor policy prevents this sender from sending this message to this recipient; type="method_call", sender=":1.207" (uid=1001 pid=2071 comm="/snap/level9/2/gtklevel9 ") interface="ca.desrt.dconf.Writer" member="Change" error name="(unset)" requested_reply="0" destination="ca.desrt.dconf" (uid=1001 pid=3018 comm="/usr/lib/dconf/dconf-service ")

```
Is it from snappy?
