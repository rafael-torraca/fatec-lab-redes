# CLASSES DE REDE

Classe A, B, C, D e E

Multicast - replicação, formatação de várias máquinas por exemplo.

A - 1.0.0.0



A - 128 redes com 16 milhões de máquinas
B - 16.384 redes com 64 mil hosts cada.
C - 2 milhoes de redes com 256 hosts cada.
D - é uma rede de multidifusão.
E - uso futuro

ICANN - Internet Corporation for Assigned Names and Number

C0290614 = 192.41.6.20

0.0.0.0 a 255.255.255.255

Camada 3
Endereço de origem e Endereço de Destino

Todo ip está associado a uma placa.

IP comprimento de 32bits (4 bytes)

2 ** 32 ipv4

2 ** 64 ipv6

127.0.0.1 loopback

192.168.0.0 indica uma rede

192.168.0.255 - broadcast
indica todos os hosts de uma determinada rede,
broadcast é o último endereço da rede
c

## SUB REDES - MASCARA DE REDE

End. IP: 192.168.0.1
Mask:    255.255.255.0

END. REDE = 192.168.0.0 - ENDEREÇO de REDE
END. BROADCAST = 192.168.0.255 - BROADCAST

11111111.11111111.11111111.00000000
[rede]                      [hosts]


2 ** 8 = 256 - 2 (broad cast e Rede)

CLASSE A (2 ** 24) - 2
CLASSE B (2 ** 16) - 2
CLASSE C (2 **  8) - 2


=======================
End.Rede: 172.16.0.0
Mask:     255.255.0.0

QTD: 65.534
End Rede: 172.16.0.0
Broadcast: 172.16.255.255
========================
End. Mq: 192.168.50.10
   Mask: 255.255.255.0

QTD: 254
End Rede: 192.168.50.0
Broadcast: 192.168.50.255
========================
End. Mq: 10.10.0.10
   Mask: 255.0.0.0

QTD: 16.777.214
REDE: 10.0.0.0
BDC: 10.255.255.255
=======================
Dúvida!
REDE: 192.168.50.50
Mask: 255.255.0.0

QTD: 42.434
BDC: 192.168.255.255
===========================================
MASCARA NÃO PADRÃO

192.168.0.0 (REDE)
255.255.254.0

HOSTS: 510
11111110.00000000

A quantidade de Zeros aplica na fórmula

(2 ** 9) - 2 = 510

512 / 256 = 2

SubRedes: 2

192.168.0.1 - 192.168.0.254 (HOSTS)
192.168.1.1 - 192.168.1.254 (HOSTS)

End.REDE: 192.168.0.0
     BDC: 192.168.1.255
===========================================
REDE: 192.168.0.0
MASK: 255.255.252.0

11111100.00000000

HOSTS: 1024 - 2 = 1022
Subredes: 4
192.168.0.0 - 192.168.3.255
BDC: 192.168.3.255
==========================================
REDE: 192.168.0.0
MASK: 255.255.255.128

HOSTS: 126
REDES: 1
BDC: 192.168.0.127

1000.0000

