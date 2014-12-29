ifbw
====
...is a Python script for Linux that displays upload and download traffic on network interfaces.

ifbw in action:  
![ifbw in action](https://raw.githubusercontent.com/kvaidas/ifbw/master/images/screenshot1.png)


```
usage: ifbw.py [-h] [-n <iterations>] [-i <seconds>] [-d]
               [interface [interface ...]]

positional arguments:
  interface             list of interfaces, separated by spaces, defaults to
                        all interfaces

optional arguments:
  -h, --help            show this help message and exit
  -n <iterations>       how many iterations to perform before exiting
                        (defaults to infinite)
  -i <seconds>, --interval <seconds>
                        interval between measurements
  -d                    turn on debug mode (developers only)
```


Suggestions, fixes and other help welcome.
