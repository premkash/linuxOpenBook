# Users

### Create a new user*

`$useradd <userName>` 

### Then create a password for the user as

`$passwd <userName>`

### To add this user to multiple groups

`$useradd -G <group1, group2, group3> <userName>`

### To see a list of users on the system

`$cat /etc/passwd` 
this file has an line entry per user

### To see a list of all users that have a home directory:

`$cat /etc/passwd | grep '/home' | cut -d: -f1`

### To see all the groups on the system

`cut -d: -f1 /etc/group`

How to create linux user
- Create user command
- Create its home-directory
- Make it to relevant group/s
- setup its prompt, profile
- Create symlinks
- update permissions

