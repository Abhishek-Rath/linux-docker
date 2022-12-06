# Linux and Docker Notes

### Lecture link: [Linux & Docker Fundamentals - complete hands-on workshop](https://youtu.be/EUu1E_YKGTw)

```bash 
/
/home # home directory and files for users
/bin  # user command binaries(cat, nano, echo, etc)
/usr # user
/usr/bin # primary executables that system needs in order to run
/usr/local # programs installed for user
/lib # when executables in /bin need additional library files in order to run
/var # temporary variable data
/var/log # logs are stored for 30days
/var/log/syslog # system logs
/var/cache # cahed data 
/etc # system wide configurations
/etc/fstab # controls how different filesystems are treated each time they are introduced to a system
/etc/hosts # used to translate hostnames to IP address
/etc/hostname # name of machine
/etc/sudoers # users who can act as super user(s)
/tmp # temporary location for running process
/boot # essential files to boot the system  
/dev # device configuration files like keyboard, mouse
/media # device mounts like CD or USB drive
/mnt # temporary mount points for additional filesystems
/root # root users home directory

```