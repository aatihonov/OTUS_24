Домашнее задание №1

Проектирование адресного пространства

Цель:
1. Собрать схему CLOS;
2. Распределить адресное пространство.

Выполнение:
![image_CLOS](https://github.com/aatihonov/OTUS_24/assets/169416214/d2f85142-88c7-4e41-8cd2-6e611be4bbe5)

Таблица адресов

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/7e11277c-76e9-46d0-8ae6-09041a4639b8)


Проверка доступности


spine1#ping 10.4.1.1

PING 10.4.1.1 (10.4.1.1) 72(100) bytes of data.

80 bytes from 10.4.1.1: icmp_seq=1 ttl=64 time=6.42 ms

80 bytes from 10.4.1.1: icmp_seq=2 ttl=64 time=2.97 ms

80 bytes from 10.4.1.1: icmp_seq=3 ttl=64 time=3.15 ms

80 bytes from 10.4.1.1: icmp_seq=4 ttl=64 time=2.80 ms

80 bytes from 10.4.1.1: icmp_seq=5 ttl=64 time=2.87 ms

--- 10.4.1.1 ping statistics ---

5 packets transmitted, 5 received, 0% packet loss, time 25ms

rtt min/avg/max/mdev = 2.808/3.648/6.428/1.395 ms, ipg/ewma 6.495/4.985 ms


spine1#ping 10.4.1.3

PING 10.4.1.3 (10.4.1.3) 72(100) bytes of data.

80 bytes from 10.4.1.3: icmp_seq=1 ttl=64 time=16.6 ms

80 bytes from 10.4.1.3: icmp_seq=2 ttl=64 time=4.56 ms

80 bytes from 10.4.1.3: icmp_seq=3 ttl=64 time=4.14 ms

80 bytes from 10.4.1.3: icmp_seq=4 ttl=64 time=4.96 ms

80 bytes from 10.4.1.3: icmp_seq=5 ttl=64 time=3.75 ms

--- 10.4.1.3 ping statistics ---

5 packets transmitted, 5 received, 0% packet loss, time 54ms

rtt min/avg/max/mdev = 3.759/6.815/16.637/4.927 ms, pipe 2, ipg/ewma 13.729/11.544 ms

spine1#ping 10.4.1.5

PING 10.4.1.5 (10.4.1.5) 72(100) bytes of data.

80 bytes from 10.4.1.5: icmp_seq=1 ttl=64 time=28.9 ms

80 bytes from 10.4.1.5: icmp_seq=2 ttl=64 time=18.9 ms

80 bytes from 10.4.1.5: icmp_seq=3 ttl=64 time=11.9 ms

80 bytes from 10.4.1.5: icmp_seq=4 ttl=64 time=4.54 ms

80 bytes from 10.4.1.5: icmp_seq=5 ttl=64 time=10.3 ms

--- 10.4.1.5 ping statistics ---

5 packets transmitted, 5 received, 0% packet loss, time 71ms

rtt min/avg/max/mdev = 4.542/14.955/28.946/8.373 ms, pipe 3, ipg/ewma 17.870/21.493 ms

spine2#ping 10.4.2.1

PING 10.4.2.1 (10.4.2.1) 72(100) bytes of data.

80 bytes from 10.4.2.1: icmp_seq=1 ttl=64 time=9.20 ms

80 bytes from 10.4.2.1: icmp_seq=2 ttl=64 time=6.18 ms

80 bytes from 10.4.2.1: icmp_seq=3 ttl=64 time=3.85 ms

80 bytes from 10.4.2.1: icmp_seq=4 ttl=64 time=4.17 ms

80 bytes from 10.4.2.1: icmp_seq=5 ttl=64 time=7.22 ms

--- 10.4.2.1 ping statistics ---

5 packets transmitted, 5 received, 0% packet loss, time 36ms

rtt min/avg/max/mdev = 3.853/6.127/9.202/1.984 ms, ipg/ewma 9.050/7.640 ms

spine2#ping 10.4.2.3

PING 10.4.2.3 (10.4.2.3) 72(100) bytes of data.

80 bytes from 10.4.2.3: icmp_seq=1 ttl=64 time=16.6 ms

80 bytes from 10.4.2.3: icmp_seq=2 ttl=64 time=8.42 ms

80 bytes from 10.4.2.3: icmp_seq=3 ttl=64 time=3.25 ms

80 bytes from 10.4.2.3: icmp_seq=4 ttl=64 time=4.33 ms

80 bytes from 10.4.2.3: icmp_seq=5 ttl=64 time=3.87 ms

--- 10.4.2.3 ping statistics ---

5 packets transmitted, 5 received, 0% packet loss, time 55ms

rtt min/avg/max/mdev = 3.251/7.300/16.620/5.001 ms, pipe 2, ipg/ewma 13.818/11.717 ms

spine2#ping 10.4.2.5

PING 10.4.2.5 (10.4.2.5) 72(100) bytes of data.

80 bytes from 10.4.2.5: icmp_seq=1 ttl=64 time=6.37 ms

80 bytes from 10.4.2.5: icmp_seq=2 ttl=64 time=2.20 ms

80 bytes from 10.4.2.5: icmp_seq=3 ttl=64 time=2.64 ms

80 bytes from 10.4.2.5: icmp_seq=4 ttl=64 time=2.87 ms

80 bytes from 10.4.2.5: icmp_seq=5 ttl=64 time=2.42 ms

--- 10.4.2.5 ping statistics ---

5 packets transmitted, 5 received, 0% packet loss, time 23ms

rtt min/avg/max/mdev = 2.209/3.306/6.370/1.548 ms, ipg/ewma 5.953/4.790 ms

