GParted++
=========

Description
-----------
**GParted++** (*GPartedPlusPlus*) is the **original GParted Live image with several additions**

Additions
--------
* A friendlier `vi`: `vim` + a `.vimrc` file in the `/root` directory.  
  So perform a `sudo -s` from the Debian live `user` first to profit of this comfort.
  
* Common bash aliases in the `/root/.bashrc` file
  
* Some useful additional packages (additional packages installed list [here](https://github.com/maaaaz/GPartedPlusPlus/blob/main/_resources/packages_to_add.txt), full package list in the `filesystem.packages.txt` of each [Release](https://github.com/maaaaz/GPartedPlusPlus/releases)), mostly based on  [these ones](https://github.com/maaaaz/dotfiles/blob/master/debian_ubuntu.sh), notably these ones:
    * `pv`: to allow printing progress bars and rates during transfers etc.
    * `htop`, `bmon`, `nmon`: for system monitoring
    * `zutils`, `pigz`, `zip`, `unzip`: for processing zlib compressed data
    * `colordiff`, `xxd`, `vbindiff`: for pretty-printing data
    * `cifs-utils`, `smbclient`: for connecting to SMB shares
    * `nmap`, `ncat`, `socat`, `proxychains`, `wireshark`, `tshark`, `vlan`: for network transfers and debugging
    * `xrdp`: an RDP client
    * `usbutils`: to handle USB devices
    * `parallel`: to process parallel tasks
    * `open-vm-tools`: to have a builtin compatibility with VMWare hypervisors
    * `libbde-utils`, `dislocker`: to process BitLocked volumes
    * `ioping`, `nvme-cli`, `fio`: to troubleshoot disks


Usage
-----
* Download the latest iso file [in the `releases` section](https://github.com/maaaaz/GPartedPlusPlus/releases)

Changelog
---------
* 2023-12-23: from now, rolling frequent updated versions
* 2023-12-22: `gparted-live-1.5.0-6-amd64-maaaaz-edition-20231222.iso`, using the now automated Github action workflow
* 2022-10-31: `gparted-live-1.4.0-5-amd64-maaaaz-edition.iso`

Copyright and license
---------------------
* All trademarks, service marks, trade names and product names appearing on this repository are the property of their respective owners 
* I don't own anything on GParted brand, neither am I affiliated or working on the project
* Content provided in this repository is distributed with the same licence used by [`GParted`](https://gparted.org), which is to date, the [GPL licence](https://www.gnu.org/licenses/gpl-3.0.html)

Useful resources
----------------
* https://gparted.org/add-packages-in-gparted-live.php
* https://drbl.org/fine-print.php?path=./faq/2_System/81_add_prog_in_filesystem-squashfs.faq#81_add_prog_in_filesystem-squashfs.faq
* https://sethc23.github.io/wiki/1_POSTS/2016-03-10-modifying-linux-filesystem-and-live-cd-via-chroot/
* http://sirlagz.net/2013/06/20/how-to-customise-gparted-livecd/
* https://live-team.pages.debian.net/live-manual/html/live-manual/customizing-run-time-behaviours.en.html
* https://live-team.pages.debian.net/live-manual/html/live-manual/customizing-contents.en.html#live-chroot-local-includes
