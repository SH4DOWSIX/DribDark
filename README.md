# DribDark
Modified Dribbblish theme.
Some code used from Comfy.



<img src="https://i.imgur.com/Xx8gLwQ.jpeg" alt="img" align="center" width="500px">

## Install
Install Dribbblish from here.
https://github.com/morpheusthewhite/spicetify-themes/tree/master/Dribbblish

Download color.ini and user.css from here and replace the original ones from Dribbblish.

Add these lines to the config-xpui.ini

```ini
[Patch]
; Playlist Height!
xpui.js_find_8008 = ,(\w+=)32,
xpui.js_repl_8008 = ,${1}14,
; TrackList Height!
xpui.js_find_8009 = ,B=56,
xpui.js_repl_8009 = ,B=32,
```

```spicetify apply in powershell```

You can change the red by editing the color.ini and replacing all references of e60000.
