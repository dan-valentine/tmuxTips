# Tmux Tips

Based off of Ippsecs Tmux video https://youtu.be/Lqehvpe_djs

copy of Ippsecs .tmux.conf included in repo

# Tips Below
parentheses mean you push the buttons at the same time

# Prefix key
Prefix key = ctrl + b (locally ctrl+a for nested sessions)

# Copy and pasting
edit mode = prefix + [
copy in editmode = space + (arrow key to select) + enter
paste = prefix + ]
exit editmode = enter

# logging Extension
logging = prefix + (alt + shift + p)
located here https://github.com/tmux-plugins/tmux-logging

## Panelling
Send to pane = prefix + s
Join to pane = prefix + j

split vertically = prefix + %
split horizontal = prefix + "

switch pane = prefix + arrow key
move pane left = prefix + {
move pane right = prefix + }
toggle zoom on pane = prefix + z
resizes = (prefix + arrow key)
cycle pane layout = prefix + space

show evertything tmux can do = prefix + ?



