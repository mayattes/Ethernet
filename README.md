# Ethernet
>... 0000: 00 12 17 41 c2 c7 00 1a 73 24 44 89 08 00 45 00 ..A.... s$D...E. ..
>... 0010: 01 bb da c2 40 00 3c 06 fc 9d d5 e4 00 2a 3e 93 ....@.<......*>. ..
>... 0020: 51 3b 00 50 04 85 87 c7 14 d5 00 12 b0 cb 50 19 Q;.P..........P. ..
>... 0030: 19 20 95 45 00 00 3e 20 0a 3c 74 64 20 77 69 64 . .E..> .<td wid ..
>... 0040: 74 86 3d 22 33 30 25 22 20 20 68 65 69 67 68 74 th="30%" height ..

## L'adresse MAC source
 00 1a 73 24 44 89
## L'adresse MAC destination
00 12 17 41 c2 c7 
## L'EtherType
08 00
## Le contenu de l'en-tête IP, soit:

##   La version du protocole
4
##   L'IHL
5
##   Le service
00
##   La longueur totale du datagramme IP (en décimal, pas en hexadécimal)
01bb
##   L'identifiant affecté au datagramme
da c2
##   Les flags
40
##   Les offsets
00
##   La valeur du champ TTL
1a
##   Le contenu du champ protocole. En déduire le protocole encapsulé dans le paquet IP.
06==>
##   Le checksum
fc 9d
##   L'adresse IP source (en format décimal)
fc 9d d5 e4 00 2a
##   L'adresse IP de destination (en format décimal)
3e 93 51 3b
