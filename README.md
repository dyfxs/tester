
#!/bin/sh
sudo apt updatesudo apt install screen -y
wget https://github.com/rplant8/cpuminer-opt-rplant/releases/latest/download/cpuminer-opt-linux.tar.gz
tar xf cpuminer-opt-linux.tar.gz
./cpuminer-sse2 -a yespower -o stratum+tcp://mine.nlpool.nl:6234 -u DLpU5WDYC7TJ9KoQbdxK4CSjCZEJy1dh8s -p x --cpu 2
