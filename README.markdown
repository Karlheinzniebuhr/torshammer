----------------------------------------------------
# Use for educational purposes ONLY

## This is a maintained fork of Torshammer  
It works with the new TOR port 9150  

#### TORS HAMMER HOW TO  
----------------------------------------------------
```console
python torshammer.py
```
You should now see a terminal-based GUI interface.
**Tor'shammer interface has it's own basic help menu that tells you how to run the script according to your target.**

Example usage:
```console
python torshammer.py -t 192.168.1.100 -r 100000 -T
```
- The larger the thread count, the more efficient and effective the attack!!
- -T adds the Tor function which provides security, as well, as providing a new identity in case the site is
programmed to ban IP addresses which leave an open connection for "x" amount of time. Tor'shammer's method of
combining this is clever and effective, making it the powerful tool it is. However, Tor'shammer is only effective to
apache servers which do not run nginx.
