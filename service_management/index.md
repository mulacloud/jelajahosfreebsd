# Beberapa command yang digunakan dalam video


## Persiapan
Silahkan download sebuah source code echo server. server ini akan membuka sebuah port yang bisa kita akses nanti dengan `telnet'

    `fetch -o /tmp/server.cpp https://github.com/mulacloud/jelajahosfreebsd/raw/main/service_management/echo-server.cpp`

Kompile source code yang sudah didownload sebelumnya

    c++ -o /tmp/server /tmp/server.cpp

Kemudian download rc script yang digunakan untuk melakukan manajemen service 


    fetch -o /usr/local/etc/rc.d/echo https://github.com/mulacloud/jelajahosfreebsd/raw/main/service_management/echo-rc-script

Rubah permission file rc 

    chmod +x /usr/local/etc/rc.d/echo

