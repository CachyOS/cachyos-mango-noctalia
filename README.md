# cachyos-mango-settings

[**Mango**](https://mangowm.github.io/) is wayland compositor built on wlroots and (optional) scenefx. 

This repository contains `Mango` specific settings, like `config.conf` and `xdg-desktop-portal`.

Dependencies:

```Sh
mango xdg-desktop-portal-wlr
```

## Reposotiry tree

### Path [`.config/mango/`](./etc/skel/.config/mango/):

in [`config.conf`](./etc/skel/.config/mango/) you can find all `includes` from directory [`cfg/`](./etc/skel/.config/mango/cfg/)

### Path [`.config/mango/cfg/`](./etc/skel/.config/mango/cfg/)

| config | purpose |
| ------ | ------- |
| [`appearance.conf`](./etc/skel/.config/mango/cfg/appearance.conf) | look & feel; how `Mango` window managment looks |
| [`input.conf`](./etc/skel/.config/mango/cfg/input.conf) | libinput related settings; xbk layouts and etc |
| [`keybinds.conf`](./etc/skel/.config/mango/cfg/keybinds.conf) | keybinds; terminal spawn, workspaces, etc |
| [`layout.conf`](./etc/skel/.config/mango/cfg/layout.conf) | current layout; layout behaviour |
| [`misc.conf`](./etc/skel/.config/mango/cfg/misc.conf) | ungrouped settings; blur, cursors, etc |
| [`rules.conf`](./etc/skel/.config/mango/cfg/rules.conf) | window rules; like blur for noctalia |

### Path [`.config/xdg-desktop-portal/`](./etc/skel/.config/xdg-desktop-portal/)

In `mango-portals.conf` you can configure `xdg-desktop-portal` directives for `mango`; Default portal already set

<br/>

Thank you for choosing CachyOS!
