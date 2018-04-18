# resources

Resources / files for various things

### feeds
This is a list of subreddits, rss feeds and twitter accounts I think are interesting...

### nessus-weapon-inventory
This is a list of .nasl plugins which could be weaponized.

`grep -rnw /opt/nessus/lib/nessus/plugins/ -e ".*Nessus was able.*" | cut -d ":" -f 1 > nessus-weapon-inventory`

### terminatorconfig
This is a config profile for Terminator. It contains the 'redteam' color profile.
* install terminator (https://gnometerminator.blogspot.com/p/introduction.html) - `apt-get install terminator`
* download terminatorconfig - `wget  https://raw.githubusercontent.com/shellsharks/resources/master/terminatorconfig`
* rename to "config" - `mv terminatorconfig config`
* place in ~/.config/terminator/ directory - `mv config ~/.config/terminator/`
