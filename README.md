# freebsd_commands
Some useful FreeBSD Commands


ToC
--------
+ [Update FreeNAS Jails](#updatejail)


**Update FreeNAS Jails<a name="#updatejail">**

https://forums.freenas.org/index.php?threads/keeping-the-jails-up-to-date.20062/


```
pkg –vv
```

Correct is


Repositories:
FreeBSD: {
url : "pkg+http://pkg.FreeBSD.org/freebsd:9:x86:64/latest",
enabled : yes,
mirror_type : "SRV"
}


If not pkg.freebsd.org


```
pkg audit
```

