1. Setup a socks5 server. Use `ssh -D 10801 127.0.0.1` for example
2. Run
$ python3 cat.py | nc -C -nvlp 8000

