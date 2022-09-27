# FORKED FROM rag-hav/ContestCountdown
**Most of the code is borrowed from the following link**
https://github.com/rag-hav/ContestCountdown

Both gnome-extension can be used simultaneously
# Contest Countdown

Gnome extension that shows a countdown to the next codeforces contest in the top bar of gnome (panel). 

![alt text](https://github.com/friendship1/ContestCountdown-AIConf/blob/master/screenshot.png?raw=true)


## Installation

### Automatic

Run 
```curl https://github.com/friendship1/ContestCountdown-AIConf/install.sh | bash```

### Manual
* Remove old installation (if any)
    ```rm -rf ~/.local/share/gnome-shell/extensions/contestcountdown-aiconf@jwwoo```
    
* Download new code from github
    ```git clone https://github.com/friendship1/ContestCountdown-AIConf.git --branch master --single-branch ~/.local/share/gnome-shell/extensions/contestcountdown-aiconf@jwwoo/```

* If your Gnome version is < 40 (you can check using `gnome-shell --version`)
    * Goto extension folder
```cd ~/.local/share/gnome-shell/extensions/contestcountdown-aiconf@jwwoo/```
    * Checkout commit before gnome 42 updates 
```git checkout 32d1b1533a1ef24dae98c64389c2058f1a50c2f3```

* Restart gnome by pressing `alt + F2` and typing `r` in the dialog box.

    
* Enable extension using any extension manager, or with the command
    ```gnome-extensions enable contestcountdown-aiconf@jwwoo  ```

## Compatiblity

Extension tested on gnome shell version 42
