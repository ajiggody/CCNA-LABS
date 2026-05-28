Lab Tasks:
1. Connect R1 and R2 via their GigabitEthernet0/0 interfaces
2. Set hostnames on each router according to the network diagram (R1 and R2)
3. Set the enable password to cisco on each router
4. View the running configuration — observe whether the password is encrypted
5. Enable password encryption on each router
6. View the running configuration again — observe the change
7. Disable password encryption on each router
8. View the running configuration again — observe the result

Key Commands:
enable - Enter privileged EXEC mode ( mode = > )
conf t - Enter global configuration mode ( mode = # )
hostname [name] - Set the router's hostname (config)#
enable password [password] - Set an unencrypted enable password (config)#
service password-encryption - Encrypt all plaintext passwords in the config (config)#
no service password-encryption - Disable password encryption (config)#
do show running-config - View the current running configuration from config mode (config)#

Tools Used:
- Cisco Packet Tracer
- Cisco IOS CLI
