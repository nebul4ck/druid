# Third Party Software

Druid
=====

Apache Druid is a high performance real-time analytics database.

This is a debian package version.

* **Maintainer:** nebul4ck
* **Version:** 0.11.0

web: https://druid.apache.org/


How install
-----------

1. Clone this repository

```
$ git clone https://github.com/nebul4ck/druid.git
```

2. Create a debian package

```
cd druid
$ dpkg -b druid/ druid-0.11.0.deb
```

3. Install 

```
$ sudo apt install ./druid-0.11.0.deb
```

4. Remove

```
$ sudo apt remove druid
```