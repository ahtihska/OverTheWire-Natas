# OverTheWire Natas
 Solution for Natas levels on Over the Wire
 ## Contents
* [Level 0](#level-0)
* [Level 0 - Level 1](#level-0---level-1)
* [Level 1 - Level 2](#level-1---level-2)
* [Level 2 - Level 3](#level-2---level-3)

## Level 0
Each level has access to the password of the next level. Your job is to somehow obtain that next password and level up. All passwords are also stored in /etc/natas_webpass/
```
Username: natas0
Password: natas0
URL:      http://natas0.natas.labs.overthewire.org
```
## Level 0 - Level 1
Inspect element and find the password under div id content
```
Username: natas1
Password: gtVrDuiDfck831PqWsLEZy5gyDz1clto
URL:      http://natas1.natas.labs.overthewire.org
```
## Level 1 - Level 2
Use keyboard shortcut Ctrl+Shift+I and find the password under div id content
```
Username: natas2
Password: ZluruAthQk7Q2MqmDeTiUij2ZvWy2mBi
URL:      http://natas2.natas.labs.overthewire.org
```
## Level 2 - Level 3
Inspect element and find the link for image under files/pixel.png
Open the image link to find that there is another file under files called user.txt
You can find this file on http://natas2.natas.labs.overthewire.org/files/users.txt
. You can find the password for user3 in this file
```
Username: natas3
Password: sJIJNW6ucpu6HPZ1ZAchaDtwd7oGrD14
URL: http://natas3.natas.labs.overthewire.org
```


