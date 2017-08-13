Sets up an edge router, including:
 - dnsmasq owning:
   - caching resolver
   - dhcpd config
   - local dns zone
 - iptables firewall including port forwards
 - network interface configuration
 - openntpd

Host requirements:
 - Debian
 - ssh key set up
 - wifi firmware
 - local user with sudo privs
