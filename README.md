# google-dork
This will grab a random dork and then save the output to a text file

This is what i use for finding all my XSS's.

Only note is the proxy is there as i use it with burp and then via tor browser socks.

You can remove this but remember google will give you the lovely capture!

I've made this using python 3 but it should work in python2.



Requires:
----
requests
google



```
pip install requests google
```

Note
------

I have not used inurl:"DORK" inurl:"&" as you end up getting results once and then you have to change the proxy each time.
