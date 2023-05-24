# 1 install
```
git clone https://github.com/HardySimpson/zlog
```

# 2 build
```
make 
make install

default directory
/usr/local/lib

$ make PREFIX=/usr/local/
$ sudo make PREFIX=/usr/local/ install
```


# 3 add so
```
sudo vim /etc/li.so.conf
add 
/usr/local/lib
$ sudo ldconfig

don't find so


other log easylogger
```


# 4 use 
```
zlog-chk-conf ./bin/zlog.conf
```
