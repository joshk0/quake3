# Install ioquake3

Install ioquake3, an open sourcing of the quake 3 arena engine, on the platform of your choice, then play with Josh.

## Installation on various platforms

### Mac

1. `curl -L https://git.io/ioq3mac | sh`. I promise it's not crapware. This will create /Applications/ioquake3/ioquake3-1.36.app
1. Launch the app. You may be denied because it's not a signed app. If so, go into Security preferences and 'Allow anyway'.

### Windows

1. Download installers: [1](http://ioquake3.org/files/1.36/installer/ioquake3-1.36-3.1.x86.exe), [2](http://ioquake3.org/files/1.36/data/ioquake3-q3a-1.32-1.x86.exe)
1. Find yourself a copy of pak0.pk3. It's out there on Google...
1. Run installer 1 and 2 with 'Install for everyone on this computer'
1. You should now have a directory `C:\Program Files (x86)\ioquake3\baseq3`. Place pak0.pk3 there.
1. Launch ioquake3 from the Start Menu.
1. When prompted for a cd-key, just press Accept.

## Customize the game

1. Setup > Player. Make sure to choose your name and hit the 'Model' button to choose an avatar. There is no benefit for any particular avatar.
1. Setup > Network, toggle the speed until you hit `LAN/Cable/xDSL`. Your ping will be horrible unless you do this.
1. Setup > Game Options, if you want to change your crosshair (i usually do.)

## HD / Wide screen on Windows

Go to this path (Start > Run): `%appdata%\Quake3\baseq3` then edit `q3config.cfg` in an editor.
Locate the lines which contain the variable names and replace values accordingly. Here are the keys and values to replace with for 1080p. Change as desired, save and exit and then you should be able to run the game with your new resolution.

```
seta r_mode "-1"
seta r_customwidth "1920"
seta r_customheight "1080"
seta cg_fov "105"
```

## Connect and play

1. Go back to main menu > Multiplayer
1. Hit Specify and type `quake3.triplehelix.org`. Then Connect
1. You're in!
