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
git clone https://github.com/KingArmin/tabchi
cd tabchi
chmod +x bot
./bot install

```
* * *
## Create BOT
```
./bot create
./bot 1

```
## Create More BOT

```sh
cd tabchi
./bot create
./bot 2

```
* * *
## AutoLaunch
```sh
cd tabchi
sudo killall screen
sudo killall tmux
sudo killall tg
sudo killall nohup
sudo killall .telegram-cli
sudo rm -rf /root/open/.telegram-cli
sudo tmux new-session -s script "bash ./bot autolaunch -t"


```
***


