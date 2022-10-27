# Useful commands

This folder contains a list of commands that I find useful and want to not forget (to be sorted later)

-   bash`ln -s [originalfile] [linkfile]` : to create a _soft_ symbolic link of `originalpath` as `linkfile`
-   bash`sudo update-initramfs -u`: updates the `initramfs`, a virtual file system that is part of the boot procedure. This is for when you have changed some of the boot configuration with `plymouth`.
-	`sudo usermod -a -G dialout <username>`: to add `username` to the `dialout` group to be able to flash data onto embedded system boards without needing permission everytime.
