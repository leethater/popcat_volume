# popcat_volume

Volume indicator inspired by  [volume-notification-dunst](https://github.com/dastorm/volume-notification-dunst).

## Demo

![demo](demo.gif)

## How to use

* ``./volume.sh up`` 
* ``./volume.sh down``
* ``./volume.sh mute``

For tiling window managers, you can add these lines to your config file :

```
bindsym XF86AudioRaiseVolume exec --no-startup-id **path_to_popcat**/volume.sh up
bindsym XF86AudioLowerVolume exec --no-startup-id **path_to_popcat**/volume.sh down
bindsym XF86AudioMute exec --no-startup-id **path_to_popcat**/volume.sh mute
```



