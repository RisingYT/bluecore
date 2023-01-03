# bluecore
A repository that has the packages for Blue Wave. If they aren't present anywhere else or if they are modified.

Most of these are preinstalled by default. Some are not and can be optionally installed when wanted.

NOTE: Packages may not always be up-to-date because it's being managed by one person. 

Well... If you want to add the repo on your current Linux system (only supports any distro that uses 'pacman' as a default package manager.), then add this line at the end of /etc/pacman.conf.

```
[bluecore]
SigLevel = Optional TrustAll
Server = https://risingyt.github.io/bluecore/$arch
```
