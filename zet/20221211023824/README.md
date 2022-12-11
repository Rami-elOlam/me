# All about linux files

* How to find files ? -> `find` command 
* Differences between `locate`, `whereis` and `find` ?
* How do I find all the files in a directory and a subdirectory ?
* How do I find only the files recursively ? using the `find . -type f` (f for file, d for directory)
* Find only the "dot" files beginning with dot ? `find . -type f -name ".*"`
* How do I find only directories beginning with dot ? `find . -type d -name ".*"`
* Find all files that have been modified or created in last hour ? `find . -mtime -1`
* Find anything modified in last 5 min ? `find ~ -nmin -5`
* Find all files that are bigger that 10 Megabytes ?
* How do I find all files with setuid perms on computer ? `find / -perm =s`

## Command used

* `find . | more` sort of the same as `ls -l1`
* `find . -ls` same as the above but with the longer form
