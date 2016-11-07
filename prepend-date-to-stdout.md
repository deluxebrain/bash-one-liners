```sh
tail -f /var/log/my-log.log \
| awk '{ print strftime ("%Y-%m-%d %H:%M:%S "), $0, fflush();}'
```
