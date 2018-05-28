# Debish #

This is an simple awesome wm theme derived from the
[default](https://github.com/awesomeWM/awesome/blob/v4.0/themes/default/theme.lua)
theme in awesome 4.0. The theme should be installed at
`$XDG_CONFIG_HOME/awesome/themes`, which usually is `~/.config/awesome/themes`
and it can be activated in awesome configuration with:

```
...
beautiful.init(awful.util.getdir("config") .. 'themes/debish/theme.lua')
...
```

Out of the box the theme uses [FiraCode](https://github.com/tonsky/FiraCode)
and [Fantasque Sans Mono](https://github.com/belluzj/fantasque-sans) fonts, so
these should be installed or the font settings modified in `theme.lua`.

### Changelog ###

```
2018-05-28
    - cleaned redish away
2018-04-11
    - added vertical bar (use boolean in theme.lua to change, defaults to vertical)
    - added more layout icons modified from default theme
```

## Screenshot ##

![Debish](screenshots/debish.png "Debish clean and busy.").

### Tag names on screenshots ###

The numbering and "icons" on the screenshot come from FiraCode -font are simply
tag names. If you want something similar they are these utf codes/characters:

```
➊ 
➋ 
➌ 
➍ 
➎ 
➏ 
➎ 
➑ 
➒ 
```

they should show up when using FiraCode as the font for tag names, adding them
is a simple matter of using copy paste to ones personal config files.

## Licensing ##

As a wallpaper this uses recoloured versions of the wallpaper from the beautiful
[Joy](https://wiki.debian.org/DebianArt/Themes/Joy) theme authored by Adrien
Aubourg and used in Debian Wheezy. The wallpapers there are licensed as GPLv2
and thus wallpapers in this theme being derivative works are also licensed
GPLv2. This theme is licensed GPLv2.

Author Niko Humalamäki (nikohuma at gmail.com).

