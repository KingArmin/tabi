# [Tabchi | v.8]

</h4>
<pre>
<span>sudo apt-get update; sudo apt-get upgrade; sudo apt-get install tmux; sudo apt-get install luarocks; sudo apt-get install screen; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev; sudo apt-get update; sudo apt-get install; sudo apt-get install upstart-sysv;
</span>
</pre>
<hr>

* * *

# Install

```sh
git clone https://github.com/KingArmin/tabi
cd tabi
chmod +x tabi
./tabi install

```
* * *
## Create BOT
```
./tabi create
./tabi 1

```
## Create More BOT

```sh
cd tabi
./tabi create
./tabi 2

```
* * *
## AutoLaunch
```sh
cd tabi
sudo killall screen
sudo killall tmux
sudo killall tg
sudo killall nohup
sudo killall .telegram-cli
sudo rm -rf /root/open/.telegram-cli
sudo tmux new-session -s script "bash ./tabi autolaunch -t"


```
***


