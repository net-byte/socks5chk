socks5chk - Socks5 Ability Checker
----------------------------------
Simple scripts used for checking SOCKS5 proxy's support of TCP or UDP.

Prerequisites
-------------
* Python 3.x
* [PySocks](https://github.com/Anorov/PySocks)
* [argparse](https://pypi.python.org/pypi/argparse) (required for Python 2.6)
* [win_inet_pton](https://pypi.python.org/pypi/win_inet_pton) (required for running Python 2.6-3.3 on Windows)

Usage
-----
Run command like this and check output.
```shell
python3 tcpchk.py -H 192.168.1.1 -P 1080
python3 tcpchk.py -H 192.168.1.1 -P 1080 -u user1 -p 123456
python3 udpchk.py -H 192.168.1.1 -P 1080
python3 udpchk.py -H 192.168.1.1 -P 1080 -u user1 -p 123456
```
