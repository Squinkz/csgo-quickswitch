# A more reliable quick switch for CSGO

This is a config for CSGO to make quickswitching more reliable. I made this back in 2017 but never uploaded it anywhere.

With this config, 'Q' (or whichever bind you choose) will always switch back to knife if you don't currently have a knife equipped, and if you do have a knife equipped it will switch to your primary. If you do not have a primary, it switches to your secondary.

It also implements a special large crosshair for smokes and molotovs, helping you to make those tricky lineups (this happens automatically when you switch to that grenade). Your crosshair will switch back to default automatically when you either throw the grenade, or switch to another weapon.

You can overwrite the crosshair configs with your own settings if you want.

## Installation

Copy the cfg files over to your
```
csgo/cfg
```
folder, and add the following to your autoexec.cfg:
```
exec quickswitch
host_writeconfig
```
