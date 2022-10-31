GParted++
=========

Description
-----------
**GParted++** (*GPartedPlusPlus*) is the **original GParted Live image with several additions**

Features
--------
* A friendlier `vi`: `vim` + a `.vimrc` file in the `/root` directory. So perform a `sudo -s` from the Debian live `user` first to profit.
* Common bash aliases in the `/root/.bashrc` file:
    ```
    alias ls='ls --color=auto'
    alias dir='dir --color=auto'
    alias vdir='vdir --color=auto'

    alias grep='grep --color=auto'
    alias fgrep='fgrep --color=auto'
    alias egrep='egrep --color=auto'

    alias ll='ls -l'
    alias la='ls -A'
    alias l='ls -CF'
    ```
* Some useful additional packages, mostly [these ones](https://github.com/maaaaz/dotfiles/blob/master/debian_ubuntu.sh), notably these ones:
    * `pv`: to allow printing progress bars and rates during transfers etc.
    * `htop`, `bmon`, `nmon`: for system monitoring
    * `zutils`, `pigz`, `zip`, `unzip`: for processing zlib compressed data
    * `colordiff`, `xxd`, `vbindiff`: for pretty-printing data
    * `cifs-utils`, `smbclient`: for connecting to SMB shares
    * `nmap`, `socat`, `proxychains`, `wireshark`, `tshark`, `vlan`: for network transfers and debugging
    * `xrdp`: an RDP client
    * `usbutils`: to handle USB devices
    * `parallel`: to process parallel tasks
    * `open-vm-tools`: to have a builtin compatibility with VMWare hypervisors

Changelog
---------
* 2022-10-31: `gparted-live-1.4.0-5-amd64-maaaaz-edition.iso`

Copyright and license
---------------------
* All trademarks, service marks, trade names and product names appearing on this repository are the property of their respective owners 
* I don't own anything on GParted brand, neither am I affiliated or working on the project
* Content provided in this repository is distributed with the same licence used by [`GParted`](https://gparted.org), which is to date, the [GPL licence](https://www.gnu.org/licenses/gpl-3.0.html)