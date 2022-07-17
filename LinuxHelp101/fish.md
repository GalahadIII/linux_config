sudo !! to sudo last command
```
in ~/.config/fish/config.fish add

function bind_bang switch (commandline -t)[-1] case "!" commandline -t $history[1]; commandline -f repaint case "*" commandline -i ! end end function fish_user_key_bindings bind ! bind_bang end
```