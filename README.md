# C.H.I.P-DHCP-blink
simply add the file to /etc/dhcp/dhclient-exit-hooks.d/ 
on the next DHCP renew it will blink the numbers of the IP address

Example: 192.168.0.10

1 blink (1)
1 sec pause
9 blinks (9)
1 sec pause
2 blinks (2)
4 sec pause (.)
1 blink (1)
1 sec pause
6 blinks (6)
1 sec pause
8 blinks (8)
4 sec pause (.)
1 long blink (0)
4 sec pause (.)
1 blink (1)
1 sec pause
1 long blink (0)
