# one-humans-wsl-journey

## access files outside of (WSL)ubuntu
https://superuser.com/questions/1083962/windows-linux-subsystem-accessing-files-outside-of-ubuntu
```
cd /mnt/c/Users
```

## access linux files from windows:
https://superuser.com/a/1266799/644627
```
C:\Users\%USERNAME%\AppData\Local\Packages\CanonicalGroupLimited.UbuntuonWindows_79rhkp1fndgsc\LocalState\rootfs\
```

## git bash terminal on wsl
https://www.reddit.com/r/bashonubuntuonwindows/comments/8b0qhl/can_i_use_gitbashs_terminal_for_wsl/
"C:\Program Files\Git\usr\bin\mintty.exe" --exec /usr/bin/winpty "C:\Windows\System32\bash.exe" -c "cd ~; $SHELL --login -i"

## troubleshoot a permission issue for bash
https://stackoverflow.com/a/48841189/5283424
```
sudo umount /mnt/c
sudo mount -t drvfs C: /mnt/c -o metadata
```

## an attempt to gain powerline fonts on windows subsystem linux.
https://medium.com/@jrcharney/bash-on-ubuntu-on-windows-the-almost-complete-set-up-1dd3cb89b794

now the only question is ... what are powerline fonts and which should I use?
