# 20220120095211

rekõvigur le klavyé ã mod kõsol  
`dpkg-reconfigure console-setup`  
`dpkg-reconfigure keyboard-configuration`

obfuskasyõ pitõ  
`python -OO -m py_compile file.py`

# add gui app in boot
/etc/xdg/autostart/name.desktop  
[Desktop Entry]  
Exec=/home/user/run.sh  

## bash  
ctrl-z  
fg  
`jobs`

### screen  
ctrl-a ctrl-c  
ctrl-a ctrl-n  
screen -r 

### git
`git commit --amend` 
`git reset --hard`
`git stash push`
`git stash pop`

## vim
modifi le make pör pitõ
``` vim
:compiler pyunit
:set makeprg=python3\ %
:make
```
