#!/bin/bash
su temporarily become the superuser
whoami display user, groups informations
groups prints the effective username of the current user
chown changes file owner and group
touch create an empty file
chmod 744 adds execute permission to the owner of the file
chmod 755 allow the file owner group owner and all user to execute a file
chmod 007 allow only to all user to read,write and execute a file
chmod --reference=ref_file file assign the permissions of ref_file to file
