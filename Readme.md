## Open file config alias
```
vi /etc/apache2/mods-available/alias.conf
```

## Comment out this
```
 #Alias /icons/ "/usr/share/apache2/icons/"

#<Directory "/usr/share/apache2/icons">
#       Options FollowSymlinks
#       AllowOverride None
#       Require all granted
#</Directory>
```

## restart apache2
```
systemctl restart apache2
```

