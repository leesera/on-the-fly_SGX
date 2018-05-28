make
 ./tcpproxy_server 127.0.0.1 12345 127.0.0.1 12344
 nc -l 12344 [other tap]
 echo 'hi' | nc 12345 [ other tap ]
