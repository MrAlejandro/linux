### Shows the libraries that are used by a certain command when running
```ldd /bin/bash```
### Linux useful utilities scheme
[http://www.brendangregg.com/linuxperf.html](http://www.brendangregg.com/linuxperf.html)
### CPU info commands
  * ```uptime``` - shows uptime and average load
  * ```top```
  * ```vmstat``` - shows CPU memory usage, swap etc.
  * ```pidstat -p [process id]``` - shows CPU info for a certain process
  * ```sar -q``` - shows process queue
### Memory info
  * ```sar -B 1 4``` - shows memory pages statistics
  * ```sar -H``` - shows hugepages statistics
  * ```sar -r``` - shows memory usage
  * ```free -m``` - shows the memory info (total size, etc)
  * ```valgrind --leak-check=full ls``` - helps to detect memory leaks
  * ```watch -n0,2 cat /proc/[meminfo|memzone]``` - shows realtime memory|zone usage
### Harddrive info
  * ```iostat``` - shows general statistics
  * ```iotop``` - shows harddrive usage stats on process level
  * ```smartctl -a /dev/sda | head``` - shows harddrive conditions info
  * ```sqr -d``` - shows general statistics
  * ```pidstat -p [process id] -d``` - shows harddrive info for a certain process
### Network info
  * ```netstat -s``` - shows general info
  * ```netstat -i``` - shows errors on interfaces
  * ```iftop``` - traffic stats
  * ```sar -n [DEV|EDEV]
  * ```traceroute google.com```
