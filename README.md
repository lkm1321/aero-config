The default OS does not ship with libnss-mdns, which prevents avahi from helping us resolve .local hostnames. So, compile it, update /etc/nsswitch.conf
