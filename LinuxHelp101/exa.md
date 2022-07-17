Change dir icons color to cyan and date modified to yellow
```fish
set -Ux EXA_COLORS "da=1;33:di=36"
```

Custom LS command
```fish
exa -laTH@ -L1 --time-style=iso --no-user --git --ignore-glob="*.git"

only dir : -lasTHD@
with tree : -L2
```



