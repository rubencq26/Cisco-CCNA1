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

![image](https://github.com/user-attachments/assets/8ea0c385-ab9d-49a3-bfcc-9977898723c7)

![image](https://github.com/user-attachments/assets/0605646e-c78c-44cf-9e2d-7a7a57ee8bc4)

![image](https://github.com/user-attachments/assets/94684deb-f5c0-470f-8ca2-8a60852f268a)

### Cambiar nombre del Switch

![image](https://github.com/user-attachments/assets/5097b614-0452-4cde-b322-40af790c4900)

Nota: Para devolver el switch al indicador predeterminado, use el comando de configuración global **no hostname**

### Contraseñas
![image](https://github.com/user-attachments/assets/cbb685c2-a8f0-47af-8b0a-360dafe3ddb6)
.
![image](https://github.com/user-attachments/assets/5da0f2a0-0215-40fb-bc35-77673d6993c4)

![image](https://github.com/user-attachments/assets/e9cae75b-3eea-4bbc-8dc6-87c9d876ca2d)

### Encriptar contraseñas

![image](https://github.com/user-attachments/assets/79aef309-98c9-4edf-9edb-4677d7897bed)

**show running-config** Use el comando para verificar que las contraseñas estén ahora encriptadas.

### Mensajes de aviso

