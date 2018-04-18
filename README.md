# resources

Resource Files for various things

### terminatorconfig
This is the config profile for Terminator. (It has redteam visual profile)
* rename to "config"
* place in ~/.config/terminator/ directory

### nessus-weapon-inventory
This is a list of .nasl plugins which could be weaponized.

`grep -rnw /opt/nessus/lib/nessus/plugins/ -e ".*Nessus was able.*" | cut -d ":" -f 1 > nessus-weapon-inventory`
