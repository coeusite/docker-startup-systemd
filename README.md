# docker-startup-systemd
Systemd service file, used to auto start docker container.

# Usage
- copy ```docker-startup@.service``` to /etc/systemd/system/ by root
- run ``` systemctl daemon-reload ```
- use ``` systemctl enable docker-startup@CONTAINERNAME.service``` to enable
- e.g. ``` systemctl enable docker-startup@ocserv.service```
- use ``` systemctl disable docker-startup@CONTAINERNAME.service``` to disable
