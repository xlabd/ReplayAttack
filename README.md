**How to run**

tip: get sha1 code from [here](http://www.sha1-online.com/)(make sure to use lenght of string 6 or less)
tip2: you can use getsha.py to get sha code of your input string.

1. from pc1 run master 
	- syntax : `python3 master.py [local ip addr] [port] [sha1 code]`
	- eg     : `python3 master.py 192.168.1.105 9987 e5acb1a96e34cd7f263aada0b69aa58bdd722a03`
2. from pc2..n run slave
	- syntax : `python3 slave.py [master ip addr] [master port]`
	- eg     : `python3 slave.py 192.168.1.105 9987`


