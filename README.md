python31.py
Collects user login credentials and initiates a Telnet session with a Cisco router using those credentials.
Once logged in, adds an IP address for Loopback interface 0.

python32.py
Collects user login credentials and initiates a Telnet session with a Cisco router using those credentials.
Once logged in, creates and names VLAN 2 through 5.

python33.py
Collects user login credentials and initiates a Telnet session with a Cisco router using those credentials.
Once logged in, creates and names VLAN 2 through 20.

python35.py
Collects user login credentials and initiates a Telnet session with switches based on IP addresses stored in
the myswitches.txt file. Once logged in to each switch, creates and names VLAN 2 through 8.

backupconfigs.py
Collects user login credentials and initiates a Telnet session with switches based on IP addresses stored in the myswitches.txt file. Once logged in to each switch, the running
configuration is read and saved to a file named by the switch IP.

WARNING: Telnet is not recognized as a secure connection. Use at own risk.