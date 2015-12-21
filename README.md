#nscan
====
* (Forked from <a href="https://github.com/shibumi/nyan"> shibumi/nyan</a> )

a simple netcat wrapper

** Nscan Tweaks: **

* Tweaked for embedded devices
* Added functionality to scan a range of ips (function 'rscan')


**dependencies:**

* gnu-netcat
* pv
* sha512sum


**Version History**

* Version 1.0.0 Initial commit
* Version 1.0.1 fixed some bugs
* Version 1.1.0 fixed some bugs, 
                attached forward function  
                attached md5sum checksum  
                distinquish between local and remote port  
* Version 1.2.0 changed hash algorithm: md5sum -> sha256sum
