# Comandos de CiscoIOS

##  Comandos de acceso
![image](https://github.com/user-attachments/assets/9d5a41f7-0c24-47d6-854e-8d80cce5a0a2)

| Commando                                                         | Descripcion                                             |
|:----------------------------------------------------------------|:---------------------------------------------------------|
| enable                                                          | Cambia al nivel privilegiado                             |
| configure terminal *(configure t)*                              | Entra al modo de configuracion global en el nivel privilegiado|
| interface vlan 1                                                | Entra al modo de configuracion de Interfaz               |
| disable                                                         | cambia al nivel de usuario                               |
| exit                                                            | Sale del modo configuracion global y vuelve al modo privilegiado|
| line console 0                                                  | modo de subconfiguracion de linea, debe entrar dede modo de configuracion, (exit) para salir|
| end                                                             | Sale de cualquier modo y vuelve al modo privilegiado (ctr + Z)  |

## Comandos de ayuda

| Comando                                                         | Descripcion                                              |
|:----------------------------------------------------------------|:---------------------------------------------------------|
| ?                                                               | muestra la lista de comandos a los que tenemos acceso    |
| in?                                                             | te da una lista de los comandos parecidos a lo que pongas delante de la ?|
| interface ?                                                     | Te devuelve el siguiente parametro que puede ser         |
| (config-if)# mac address 1234.5678.90AB                         | Overwrite MAC address.                                   |
| (config-if)# no mac address                                     | Remove MAC overwrite.                                    |
| (config-if)# ipv6 address 2001:41d0:8:e115::ccc/64              | Add IPv6 address to interface.                           |
| (config-if)# ipv6 address 2001:41d0:8:e115::/64 eui-64          | Add IPv6 address based on MAC to interface.              |
| (config-if)# ip address dhcp                                    | Get IPv4 address via dhcp.                               |
| (config-if)# ipv6 address autoconfig [default]                  | Get IPv6 address [and default route] via autoconfig      |
| (config-if)# ip dhcp client client-id asccii SW2                | Set hostname transmitted as dhcp client to SW2           |
| (config)# interface g1/0 - 2                                    | Configure both interfaces at once.                       |
| (config-if)# [no] shutdown                                      | En- or Disable interface. Often shutdown is the default. |
| (config)# ip default-gateway 10.23.42.1                         | Set 10.23.42.1 as the default gateway                    |
| (config)# ip route 10.20.30.0 255.255.255.0 {1.2.3.4,e0/0} [ad] | Add static route via next hop or interface               |
| (config)# ipv6 route 2001:41d0:8:e115::/64 [g1/1] [next hop]    | Next hop is required for Ethernet interface in IPv6      |
| (config)# ip host the-space.agency 178.32.222.21                | Create a static host entry on this device.               |
| (config)# ipv6 unicast-routing                                  | Globally enable ipv6 routing.                            |
