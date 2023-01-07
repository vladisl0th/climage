# climage
A colection of useful shell commands.

| Command  | Description |
| ------------- | ------------- |
|  ````find / -type f -a \( -perm -u+s -o -perm -g+s \) -exec ls -l {} \; 2> /dev/null```` | Find all the SUID/SGID executables  |
