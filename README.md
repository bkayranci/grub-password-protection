# Grub Password Protection

## INSTALLATION
```
sudo git clone https://github.com/bkayranci/grub-password-protection.git /opt/grub-password-protection
sudo chmod 500 /opt/grub-password-protection/grub-mkpasswd
sudo ln /opt/grub-password-protection/grub-mkpasswd /bin/grub-mkpasswd
```

## REQUIREMENTS
- tee
- grub-common

## USAGE
#### Create password protection configuration and configure it

```
grub-mkpasswd -u root
```

#### Clear password configuration and configure it

```
grub-mkpasswd -c
```


## SCREENSHOT

![Password Screen](/img/screenshot01.png "Password Screen")

![Configuration Screen](/img/screenshot02.png "Configuration Screen")

