MAC下安装rar、unrar
一.首先操作，下载rar
在http://www.rarsoft.com/download.htm页面下载RAR X.XX for Mac OS X,
目前是rarosx-5.6.0.tar.gz
二.命令行操作,安装rar
    1.sudo install -c -o $USER rar /bin
    这一步有可能会报一个错误：install: /bin/rar: Operation not permitted，
    但是你不要慌，来一波命令完美解决：sudo install -c -o $USER rar /usr/local/bin
三.安装unrar
    1.sudo install -c -o $USER unrar /usr/local/bin