##systemctl
systemctl list-units|list-timers|list-sockets
systemctl start|stop|restart|reload UNIT...
systemctl is-active|is-enabled UNIT...
systemctl status UNIT...
systemctl enable|disable UNIT...

## journalctl
# multiple units at once
journalctl -u home.mount -u networking.service 

# live watch
journalctl -f -u apache 

#filter by date
journalctl --since "2016-07-01" --until "2 minutes ago" 

# filter by label error, warning, alert or emergency
journalctl -p err -b 

# add environment variable to path
export PATH=$PATH:~/opt/bin

# show path to linux command
which ls

# Create files of a certain size
truncate -s 5M ostechnix.txt

