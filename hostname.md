### Change Hostname of Linux machine

```bash
#Change hostname in this file
sudo nano /etc/hostname
#set new value in hosts file
sudo nano /etc/hosts
#restart hostnamed
sudo systemctl restart systemd-hostnamed
#reboot system for update
sudo reboot
```
