# Setting-passwords-on-Switch.
![image](https://github.com/kulmiye73/Setting-passwords-on-Switch/assets/60412799/81b3e789-b2ce-459f-9bd5-831d23e40bb0)

 

#How to Set Console and VTY Passwords.

# conf terminal

line console 0

password cisco

login

# How to set password line vty.
conf terminal

line vty 0

password cisco

login

# How to prevent accessing through remaining vty line 1-4
conf t

line vty 1 4

login

exit

# Save your change to the starup-config file

Copy run start command
