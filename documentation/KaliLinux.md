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

## SSH



```sh
root@kali:~# nmap 127.0.0.1

Starting Nmap 7.40 ( https://nmap.org ) at 2017-02-26 12:36 CST
Nmap scan report for localhost (127.0.0.1)
Host is up (0.0000020s latency).
Not shown: 999 closed ports
PORT   STATE SERVICE
22/tcp open  ssh

Nmap done: 1 IP address (1 host up) scanned in 0.10 seconds
root@kali:~# 
```