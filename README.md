# 🔭 NetRadar 🔭

[Español](https://github.com/XDeadHackerX/NetRadar/blob/main/README.md) | [English](https://github.com/XDeadHackerX/NetRadar/blob/main/README-English.md)

> Herramienta creada por XDeadHackerX

<p align="center"><img width="120px" alt="Version" src="https://img.shields.io/badge/version-1.0-white.svg?style=for-the-badge"/></p>

[![Net-Radar-1-0-es.png](https://i.postimg.cc/xTBFyHz3/Net-Radar-1-0-es.png)](https://postimg.cc/ZCFcJWjW)

---

*Buenas, soy* **XDeadHackerX** *y quiero presentaros mi nueva herramienta llamada* **NetRadar**. *Esta Tool está enfocada al* **Networking** *en concreto al* **Mapeo** *de* **Redes Locales y Redes Wifi.** *A Nivel de* **Red Local,** *es capaz de analizar todos los Dispositivos conectados (MAC, Vendedor MAC, Sistema Operativo, Nombre, Tipo de Dispositivo), todos los Puertos abiertos de cada IP (Puerto, Servicio, Versión del Servicio, Estado, Banner)*, encontrar Servidores (Nombre, Sistema Operativo, Versión del Servicio, Dominio, Puertos, etc.) *A Nivel de* **Red Wifi** *nos encontramos con 4 tipos de escaneos totalmente automatizados y muy potentes (Aircrack-ng, Bettercap, NmCli y Wash), al terminar el escaneo nos generará un* **Gráfico** *en el que te muestra un **esquema** de las **Redes Wifi detectadas** (MAC, Distancia desde nuestra Tarjeta de Red Wifi, Beacons, Canal, Velocidad del Router, Encriptación, AUTH y el Nombre de la Red Wifi) y los **Dispositivos conectados** a cada Red, mostrándote (Mac, Fabricante de la Mac, Tipo de dispositivo y tiempo conectados a la Red).*

*Como extra,* **NetRadar** *trae un **Kit** el cual es capaz de agrupar de una forma resumida y limpia información muy interesante acerca del Equipo, la Tarjeta de Red y la Tarjeta de Red Wifi [Opciones 1 y 2]*

<p align="center"><img src=https://i.postimg.cc/D0Vbpjfg/wifi1.gif width="350px"/></p>

---

## 💡 Funciones 💡

:ballot_box_with_check: **Información Tarjeta de Red + Equipo** --> [*IP Pública, IP Local, DNS, MAC, Sistema Operativo, Prueba de Velocidad Internet* ]

:ballot_box_with_check: **Información Tarjeta de Red Wifi + Utilidades** --> [**Info Tarjeta de Red** *(Datos Técnicos, Interfaz, Drivers, Chipset, MACs, Modos Compatibles con la Tarjeta de Red (Modo Monitor, AP, P2P-client, etc), En que Modo se encuentra la Tarjeta de Red (Monitor o Managed), Tasa de Transferencia de Datos, Frecuencias Soportadas*) **Activar Modo Monitor** *(Activa el Modo Monitor y Cambia la MAC, NO HACE FALTA PARA USAR LA HERRAMIENTA),* **Restablecer Tarjeta de Red** *(Desactiva el Modo Monitor, Pone la MAC por defecto y Reinicia el NetworkManager)*]

:ballot_box_with_check: **Escáner de Red Local (Un Dispositivo)** --> [**Escaneo Rápido Puertos** *(N° Puertos, Estado, Servicio de cada Puerto, Mac, Vendedor Mac), **Escaneo Avanzado Puertos** (N° Puertos, Estado, Servicio de cada Puerto, Versión de cada Servicio, Información del Contenido de cada Puerto, Mac, Vendedor Mac, Sistema Operativo, si tiene Host Información sobre él), **Escaneo Windows + Samba** (Escaneo Avanzado de los 65535 Puertos, Enumeración de Usuarios = En caso de Poder, Reconocimiento del Dominio = Nombre, Reconocimiento SMB = Permisos, Acceso, Clase, Nombre del Dispositivo Asignado por Windows), **Escaneo NetBios** (Escaneo Avanzado de los 65535 Puertos, Nombre de NetBios, Tipo/Nombre de Servidor, Usuarios = En caso de Poder)*]

:ballot_box_with_check: **Escáner de Red Local (Varios Dispositivos** --> [**Escaneo Rápido IPs** *(IPs, MAC, Vendedor Mac), **Escaneo Rápido IPs + Puertos** (IPs, N° Puertos, Servicio de cada Puerto, Mac, Vendedor Mac),**Escaneo Continuo IPs** (IPs, MAC, Vendedor Mac, Name, KB Enviados y Recibidos), **Escaneo Avanzado IPs Puertos** (N° Puertos, Estado, Servicio de cada Puerto, Versión de cada Servicio, Información del Contenido de cada Puerto, Mac, Vendedor Mac, Sistema Operativo, si tiene Host Información sobre él), **Escaneo en Busca de un Servicio en Específico** (HTTP/HTTPS, SMB, FTP, SSH, Telnet, Windows, NetBIOS)*]

:ballot_box_with_check: **Escáner Redes Wifi** --> [*Opción de hacer el escaneo con **Aircrack-ng, Bettercap, NmCli y Wash**. En el caso de usar Aircrack-ng cuando finaliza el escaneo te crea un **Gráfico** en el que te muestra un **esquema** de las **Redes Wifi Detectadas** (MAC, Distancia desde nuestra Tarjeta de Red Wifi, Beacons, Canal, Velocidad del Router, Encriptación, AUTH y el Nombre de la Red Wifi) y los **Dispositivos conectados** a cada Red, mostrándote (Mac, Fabricante de la Mac, Tipo de dispositivo y tiempo conectados a la Red).]

:ballot_box_with_check: **Escáner Dispositivos Conectados a una Red Wifi** --> [*Muestra los dispositivos Wifi conectados a una Red Wifi, cuando finaliza el escaneo te crea un Gráfico en el que te muestra un esquema de los dispositivos conectados mostrando la MAC de los dispositivos, la cantidad de Tráfico, la distancia entre cada dispositivo y nuestra Tarjeta de Red, los paquetes de perdida, Notas y Probes.*]

## 🛠 Instalar Herramienta 🛠

**0)** Instalar y usar la Herramienta con **Root**

**1)** sudo apt update && apt -y full-upgrade

**2)** sudo apt-get install git

**3)** git clone https://github.com/XDeadHackerX/NetRadar

**4)** cd NetRadar

**5)** chmod 777 netradar.sh

**6)** bash netradar.sh

**7)** Elige un idioma

**8)** Ya podemos disfrutar de la herramienta

## 🎲 Tener en Cuenta 🎲

**[1]** En caso de usar la Herramienta para escanear direcciones IPs funcionará perfecto excepto de tener una VPN activada, con el uso de VPN la mayoría de servidores dan respuestas erróneas sobre sus puertos.

**[2]** En caso de que tengas descargada una versión más antigua, te aconsejo borrarla y volver a instalar la herramienta (+requisitos) para solucionar errores y obtener mejoras, que hacen que la herramienta sea mucho mejor que las versiones anteriores.

**[3]** Si dentro de la opción ([4] Escaneo de Todos los Dispositivos de la Red Local) en el apartado ([6] Buscar Servicios [HTTP, SMB, FTP, SSH,.]) se queda pillado, solo espere 3 minutos, esto ocurre por un error con una de las herramientas y está volcando la salida incorrecta al segundo plano y la Información correcta la está lanzando por terminal.

## 🔎 Versiones 🔎

**(v1.0)** ---> Versión Original.

## ⭐☕ Creado por XDeadHackerX ☕⭐

**Si consideras que este proyecto ha sido útil, te agradecería que me apoyaras dándole una estrella a este repositorio o invitándome a un café.**

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/XDeadHackerX)

Copyright © 2023, XDeadHackerX