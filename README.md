# python-dhcp-leases

Python script to get DHCP leases

The original script can be found here:
https://askubuntu.com/a/553387/1360030

I've changed a few things so it's a bit prettier and works with CentOS
If you want to change this code so it works with Debian-based systems,
you just need to change line 236 back to this:
myfile = open('/var/lib/dhcp/dhcpd.leases', 'r')

Proper thanks and credit goes to Canadian Luke for sharing the original scrpt.
