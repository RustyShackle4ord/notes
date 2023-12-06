apt-get install ufw
ufw default deny incoming
ufw enable

For Connection from target to your port:

ufw allow from $target to any port $port

EXAMPLE: sudo ufw allow from 203.0.113.103 to any port 22


https://www.digitalocean.com/community/tutorials/ufw-essentials-common-firewall-rules-and-commands