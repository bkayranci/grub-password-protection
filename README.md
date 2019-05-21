# Grub Password Protection

## INSTALLATION
```
git clone https://github.com/bkayranci/grub-password-protection.git -o /opt/grub-password-protection
chmod 500 /opt/grub-password-protection
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
