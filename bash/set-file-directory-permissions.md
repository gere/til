# Set appropriate permissions for files and directory

In many case it's desirable to set different permissions for files and folders. Typically for a web site you want to 755 for folders and 644 for files. Recursively of course.

### Change all subdirectories to a given access level:

```bash
find /var/www/mysite -type d -exec chmod 755 {} \;
```


### Change all files to a given access level:

```bash
find /var/www/mysite -type f -exec chmod 644 {} \;
```

[Source](http://stackoverflow.com/questions/3740152/how-to-set-chmod-for-a-folder-and-all-of-its-subfolders-and-files-in-linux-ubunt)