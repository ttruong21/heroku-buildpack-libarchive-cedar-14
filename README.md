```
$ curl -O http://www.libarchive.org/downloads/libarchive-3.1.2.tar.gz
$ tar xzvf libarchive-3.1.2.tar.gz
$ cd libarchive-3.1.2
$ ./configure --prefix=$HOME/vendor/libarchive
$ make
$ make install
$ cd $HOME/vendor
$ tar cJf heroku-libarchive-3.1.2.tar.xz libarchive
```

We can dowload the arhive by using srvdir.

```
$ curl https://raw.githubusercontent.com/scottmotte/srvdir-binary/master/srvdir.tar.gz -O -ssl3
$ tar -zxvf srvdir.tar.gz
$ ./srvdir
```
