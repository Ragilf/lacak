# Cara Lacak Lokasi Dengan Termux
$ pkg update && pkg upgrade
$ pkg install php
$ pkg install git
$ pkg install openssh
$ git clone https://github.com/thelinuxchoice/locator
$ cd locator
$ bash locator.sh

Buka New Sessions di Termux.....lalu ketik:
$ ssh -R 2323:localhost:2323 serveo.net
Lalu kembali lagi ke season awal
