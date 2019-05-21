# Grub Password Protection

## INSTALLATION
```
git clone https://github.com/bkayranci/grub-password-protection.git
cd grub-password-protection
sudo ln grub-mkpasswd /bin/grub-mkpasswd
```

## USAGE
#### Create password protection configuration and configure it

```
grub-mkpasswd -u root
```

#### Clear password configuration and configure it

```
grub-mkpasswd -c
```
