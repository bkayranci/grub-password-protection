# Grub Password Protection

## INSTALLATION
```
sudo git clone https://github.com/bkayranci/grub-password-protection.git /opt/grub-password-protection
sudo chmod 500 /opt/grub-password-protection
sudo ln /opt/grub-password-protection /bin/grub-mkpasswd
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
