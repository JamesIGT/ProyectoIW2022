### OBJETIVOS GENERALES
-  Hacer uso de los conocimientos adquiridos a los largo del semestre para la resolución y modelacion de un diseño de una red planteado en una problematica de la vida real.
- Implementar en la empresa FERREMUNDO una red para la transmisión de datos y voz, que interconecte la matriz de quito con sus sucursales de Latacunga y Ambato. 

------------


### CALCULO DE ANCHO DE BANDA
En promedio una base de datos por usuario ocupa aproximadamente una capacidad de
canal de 24Kbps obteniendo:

- **Edificio**: Matriz.
- **Cantidad de usuario**: 8.
- **Ancho de banda necesario**: 4.266664 MBps.
- **Transferencia 1 hora**: 15.3599904 GB.

------------
- **Edificio:** Sucursal.
- **Cantidad de usuario**: 4.
- **Ancho de banda necesario:** 2.133332 MBps.
- T**ransferencia 1 hora**: 7.6799952 GB

------------


El tamaño promedio de un mensaje de correo electrónico es de 500Kbytes y se estima
que un usuario revisa en promedio 4 correos por hora obteniendo:

- **Edificio: **Matriz
- **Cantidad de usuario:** 8
- **Ancho de banda necesario:** 0.035555552 MBps
- **Transferencia 1 hora:** 0.1279999872 GB
------------
- **Edificio**: Sucursal
- **Cantidad de usuario:** 4
- **Ancho de banda necesario:** 0.017777776 MBps
- **Transferencia 1 hora**: 0.0639999936 GB

------------


Para el acceso a internet se considera que el tamaño promedio de una página de internet
es de 312Kbytes y se estima que un usuario puede abrir un promedio 4 páginas en una
hora.

- **Edificio:** Matriz
- **Cantidad de usuario:** 8
- **Ancho de banda necesario: **0.022186664 MBps
- **Transferencia 1 hora:** 0.0798719904 GB

------------


- **Edificio:** Sucursal
- **Cantidad de usuario**: 4
- **Ancho de banda necesario**: 0.011093332 MBps
- **Transferencia 1 hora:** 0.0399359952 GB

------------


### DECISIONES DE DISEÑO
Para la creación de la red se tomo en cuenta la estructura de la matriz y sus sucursales. Se tomó la decisión de usar una estructura jerárquica de núcleo contraído donde usaremos un solo dispositivo para controlar la capa de núcleo y la capa de distribución.
Este diseño de red nos reducirá costos y queda perfecto para este caso por que la empresa no cuenta con demasiado personal, tampoco se ve que vaya a tener un crecimiento en los próximos años. Este diseño nos brinda las siguientes ventajas:
- Menor costo en la implementación
- Todas las ventajas de una estructura de 3 capas
- Fácil administración de los accesos que tienen los diferentes usuarios
- Este diseño serio implementado para cada sucursal y la matriz. Y cada red será conectada vía internet por un router.


------------
### DIAGRAMA DE TOPOLOGIA POR SECCIONES:
![](https://github.com/JamesIGT/ProyectoIW2022/blob/5a0322a8642a7d4ae1eb0434b882afe15d8d9819/Images/Imagen1.png)
![](https://github.com/JamesIGT/ProyectoIW2022/blob/main/Images/Imagen2.png)
![](https://github.com/JamesIGT/ProyectoIW2022/blob/5a0322a8642a7d4ae1eb0434b882afe15d8d9819/Images/Imagen3.png)

###  REFERENCIAS
Configuring VLAN Trunk Protocol (VTP). (s. f.).
Cisco. https://www.cisco.com/c/en/us/support/docs/lan-switching/vtp/98154-conf-vlan.html
Cómo configurar OSPF en cisco - CCNA desde cero. (s. f.). CCNA Desde
Cero. https://ccnadesdecero.com/curso/como-configurar-ospf/
Configuración VTP, OSPF multiárea, redistribución y respaldo de IOS (practica en CISCO
packet tracer). (s. f.). redesitesi. https://redesitsi.wordpress.com/2014/11/29/configuracionvtp-ospf-multi-area-redistribucion-y-respaldo-de-ios-practica-en-cisco-packet-tracer-2/
Configuración del encapsulado de retransmisión de tramas en las interfaces POS de la serie
Cisco 12000. (s. f.).
Cisco. https://www.cisco.com/c/es_mx/support/docs/optical/synchronous-optical-networksonet/19180-frame-19180.html
Ilustración 3. VLAN183 Voz Ambato
Cómo configurar HSRP (hot standby router protocol) - estudia redes. (s. f.). Estudia
Redes. https://estudiaredes.com/cisco/como-configurar-hsrp-hot-standby-router-protocol/
Casos prácticos de BGP. (s. f.).
Cisco. https://www.cisco.com/c/es_mx/support/docs/ip/border-gateway-protocolbgp/26634-bgp-toc.html

------------


**Table of Contents**

[TOCM]

[TOC]




