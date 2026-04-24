## comandos para usar no CLI do Router para config do SNMP

Clicar no Router > Aba CLI >

⚠️Rodar um comando por vez (uma linha por vez):

enable

configure terminal

interface fastEthernet 0/0

ip address 192.168.1.1 255.255.255.0

no shutdown

exit

snmp-server community public ro

copy running-config startup-config

## Como deve parecer ao configurar
![comandos rodados no packet tracer](prints/config-router.png)
