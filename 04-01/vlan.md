# VLAN (REDES LOCAIS VIRTUAIS)

- segmentação da rede
- segurança
- facilidade de movimentação de redes IP
- controle de tráfego Broadcast
- Desempenho
- Gerenciamento

PORT ACCESS
- apenas 1 vlan

PORTA TRUNK (ENTRONCAMENTO)
- vlan 1
- vlan 2

------------------
ROUTER -> VLAN1 E VLAN2


### CRIAR SUB INTERFACE
Router(config)# interface GigabitEthernet 0/0/0.1

Router(config-subif)# encapsulation dot1Q ?
Router(config-subif)# encapsulation dot1Q 2

Router(config-subif)# ip address 192.168.0.254 255.255.255.0

show ip route

ip route 192.168.0.0 255.255.255.0 via GigabitEthernet 0/0/0.1