# LinuxInsyde Pacman Repository

To add this to your Arch installation, add this to `/etc/pacman.conf`

```conf
[li-pacman]
SigLevel = Optional DatabaseOptional
Server = https://raw.githubusercontent.com/LinuxInsyde/$repo/main/$arch
```
