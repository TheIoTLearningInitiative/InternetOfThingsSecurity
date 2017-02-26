# Kali Linux

- [Fixes](http://www.hitxp.com/articles/software/ubuntu-fix-slow-wireless-internet-connection-speed-upgrading-11-04-natty-narwhal/)

```sh
root@kali:~# nano /etc/nsswitch.conf
```

```
#hosts:          files mdns4_minimal [NOTFOUND=return] dns myhostname
hosts:          files dns
```

```sh
root@kali:~# nano  ~/.bashrc
```

```sh
pulseaudio -D
/sbin/iwconfig wlan0 power off
```