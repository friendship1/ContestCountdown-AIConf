# Contest Countdown

Gnome extension that shows a countdown to the next codeforces contest in the top bar of gnome (panel). 

![alt text](https://github.com/rag-hav/ContestCountdown/blob/master/screenshot.png?raw=true)


## Installation

### Automatic

Run 
```curl https://raw.githubusercontent.com/rag-hav/ContestCountdown/master/install.sh | bash```

### Manual
* Remove old installation (if any)
    ```rm -rf ~/.local/share/gnome-shell/extensions/contestcountdown@raghav```
    
* Download new code from github
    ```git clone https://github.com/rag-hav/ContestCountdown.git --branch master --single-branch ~/.local/share/gnome-shell/extensions/contestcountdown@raghav/```

* Restart gnome by pressing `alt + F2` and typing `r` in the dialog box.

    
* Enable extension using any extension manager, or with the command
    ```gnome-extensions enable contestcountdown@raghav  ```

## Compatiblity

Extension tested on gnome shell version 3.36
