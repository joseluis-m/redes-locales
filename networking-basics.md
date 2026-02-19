# Networking Basics — Documentación Técnica Completa

> **Curso completo de Fundamentos de Redes** — Basado en el currículo de Cisco Networking Academy  
> Nivel: Principiante absoluto | Idioma: Español de España  
> Autor: Instructor Certificado Cisco (CCNA/CCNP)

---

## Índice de Contenidos

- [Módulo 1: La Comunicación en un Mundo Conectado](#módulo-1-la-comunicación-en-un-mundo-conectado)
  - [1.1 Tipos de Redes](#11-tipos-de-redes)
  - [1.2 Transmisión de Datos](#12-transmisión-de-datos)
  - [1.3 Ancho de Banda y Rendimiento](#13-ancho-de-banda-y-rendimiento)
  - [1.4 Resumen del Módulo 1](#14-resumen-del-módulo-1)
- [Módulo 2: Componentes de Red, Tipos y Conexiones](#módulo-2-componentes-de-red-tipos-y-conexiones)
  - [2.1 Clientes y Servidores](#21-clientes-y-servidores)
  - [2.2 Componentes de Red](#22-componentes-de-red)
  - [2.3 Opciones de Conectividad con el ISP](#23-opciones-de-conectividad-con-el-isp)
  - [2.4 Resumen del Módulo 2](#24-resumen-del-módulo-2)
- [Módulo 3: Redes Inalámbricas y Móviles](#módulo-3-redes-inalámbricas-y-móviles)
  - [3.1 Redes Inalámbricas](#31-redes-inalámbricas)
  - [3.2 Conectividad de Dispositivos Móviles](#32-conectividad-de-dispositivos-móviles)
  - [3.3 Resumen del Módulo 3](#33-resumen-del-módulo-3)
- [Módulo 4: Construir una Red Doméstica](#módulo-4-construir-una-red-doméstica)
  - [4.1 Fundamentos de la Red Doméstica](#41-fundamentos-de-la-red-doméstica)
  - [4.2 Tecnologías de Red en el Hogar](#42-tecnologías-de-red-en-el-hogar)
  - [4.3 Estándares Inalámbricos](#43-estándares-inalámbricos)
  - [4.4 Configurar un Enrutador Doméstico](#44-configurar-un-enrutador-doméstico)
  - [4.5 Resumen del Módulo 4](#45-resumen-del-módulo-4)
- [Módulo 5: Principios de Comunicación](#módulo-5-principios-de-comunicación)
  - [5.1 Protocolos de Comunicación](#51-protocolos-de-comunicación)
  - [5.2 Estándares de Comunicación](#52-estándares-de-comunicación)
  - [5.3 Modelos de Comunicación en Red](#53-modelos-de-comunicación-en-red)
  - [5.4 Resumen del Módulo 5](#54-resumen-del-módulo-5)
- [Módulo 6: Medios de Red](#módulo-6-medios-de-red)
  - [6.1 Tipos de Medios de Red](#61-tipos-de-medios-de-red)
  - [6.2 Resumen del Módulo 6](#62-resumen-del-módulo-6)
- [Módulo 7: La Capa de Acceso](#módulo-7-la-capa-de-acceso)
  - [7.1 Encapsulación y la Trama Ethernet](#71-encapsulación-y-la-trama-ethernet)
  - [7.2 La Capa de Acceso](#72-la-capa-de-acceso)
  - [7.3 Resumen del Módulo 7](#73-resumen-del-módulo-7)
- [Módulo 8: El Protocolo de Internet](#módulo-8-el-protocolo-de-internet)
  - [8.1 Propósito de una Dirección IPv4](#81-propósito-de-una-dirección-ipv4)
  - [8.2 Estructura de la Dirección IPv4](#82-estructura-de-la-dirección-ipv4)
  - [8.3 Resumen del Módulo 8](#83-resumen-del-módulo-8)
- [Módulo 9: IPv4 y Segmentación de Redes](#módulo-9-ipv4-y-segmentación-de-redes)
  - [9.1 IPv4 Unidifusión, Difusión y Multidifusión](#91-ipv4-unidifusión-difusión-y-multidifusión)
  - [9.2 Tipos de Direcciones IPv4](#92-tipos-de-direcciones-ipv4)
  - [9.3 Segmentación de Redes](#93-segmentación-de-redes)
  - [9.4 Resumen del Módulo 9](#94-resumen-del-módulo-9)
- [Módulo 10: Formatos y Reglas de Direccionamiento IPv6](#módulo-10-formatos-y-reglas-de-direccionamiento-ipv6)
  - [10.1 Problemas de IPv4](#101-problemas-de-ipv4)
  - [10.2 Direccionamiento IPv6](#102-direccionamiento-ipv6)
  - [10.3 Resumen del Módulo 10](#103-resumen-del-módulo-10)
- [Módulo 11: Direccionamiento Dinámico con DHCP](#módulo-11-direccionamiento-dinámico-con-dhcp)
  - [11.1 Direccionamiento Estático y Dinámico](#111-direccionamiento-estático-y-dinámico)
  - [11.2 Configuración de DHCPv4](#112-configuración-de-dhcpv4)
  - [11.3 Resumen del Módulo 11](#113-resumen-del-módulo-11)
- [Módulo 12: Pasarelas a Otras Redes](#módulo-12-pasarelas-a-otras-redes)
  - [12.1 Límites de la Red](#121-límites-de-la-red)
  - [12.2 Traducción de Direcciones de Red (NAT)](#122-traducción-de-direcciones-de-red-nat)
  - [12.3 Resumen del Módulo 12](#123-resumen-del-módulo-12)
- [Módulo 13: El Proceso ARP](#módulo-13-el-proceso-arp)
  - [13.1 MAC e IP](#131-mac-e-ip)
  - [13.2 Contención de Difusiones](#132-contención-de-difusiones)
  - [13.3 Resumen del Módulo 13](#133-resumen-del-módulo-13)
- [Módulo 14: Enrutamiento entre Redes](#módulo-14-enrutamiento-entre-redes)
  - [14.1 La Necesidad del Enrutamiento](#141-la-necesidad-del-enrutamiento)
  - [14.2 La Tabla de Enrutamiento](#142-la-tabla-de-enrutamiento)
  - [14.3 Crear una LAN](#143-crear-una-lan)
  - [14.4 Resumen del Módulo 14](#144-resumen-del-módulo-14)
- [Módulo 15: TCP y UDP](#módulo-15-tcp-y-udp)
  - [15.1 TCP y UDP](#151-tcp-y-udp)
  - [15.2 Números de Puerto](#152-números-de-puerto)
  - [15.3 Resumen del Módulo 15](#153-resumen-del-módulo-15)
- [Módulo 16: Servicios de la Capa de Aplicación](#módulo-16-servicios-de-la-capa-de-aplicación)
  - [16.1 La Relación Cliente-Servidor](#161-la-relación-cliente-servidor)
  - [16.2 Servicios de Aplicación de Red](#162-servicios-de-aplicación-de-red)
  - [16.3 Sistema de Nombres de Dominio (DNS)](#163-sistema-de-nombres-de-dominio-dns)
  - [16.4 Clientes y Servidores Web](#164-clientes-y-servidores-web)
  - [16.5 Clientes y Servidores FTP](#165-clientes-y-servidores-ftp)
  - [16.6 Terminales Virtuales](#166-terminales-virtuales)
  - [16.7 Correo Electrónico y Mensajería](#167-correo-electrónico-y-mensajería)
  - [16.8 Resumen del Módulo 16](#168-resumen-del-módulo-16)
- [Módulo 17: Utilidades de Pruebas de Red](#módulo-17-utilidades-de-pruebas-de-red)
  - [17.1 Comandos de Resolución de Problemas](#171-comandos-de-resolución-de-problemas)
  - [17.2 Resumen del Módulo 17](#172-resumen-del-módulo-17)

---

## Módulo 1: La Comunicación en un Mundo Conectado

### 1.0 Introducción

> *Imagina que vives en una isla remota sin teléfono, sin correo, sin ningún medio de comunicación con el exterior. ¿Cómo te sentirías? Probablemente, bastante aislado. Pues bien, las redes de ordenadores nacieron precisamente para evitar ese aislamiento digital: para conectar personas, dispositivos e información sin importar la distancia.*

En este primer módulo descubriremos qué es una red, qué tipos de redes existen, cómo viajan los datos a través de ellas y qué significan conceptos tan importantes como el ancho de banda y el rendimiento. Todo explicado desde cero, como si fuera tu primera vez encendiendo un ordenador con cable de red.

---

### 1.1 Tipos de Redes

#### ¿Qué es una red?

Una **red** es simplemente un conjunto de dos o más dispositivos conectados entre sí para compartir información y recursos. Piénsalo como un grupo de amigos que se pasan notas en clase: cada amigo es un dispositivo, y las notas son los datos que viajan por la red.

En el mundo real, las redes nos permiten enviar correos electrónicos, ver vídeos en streaming, jugar en línea, hacer videollamadas y acceder a millones de páginas web. Sin redes, cada ordenador sería una isla aislada.

#### Redes de Área Personal (PAN)

Una **PAN** (Personal Area Network, o Red de Área Personal) es la red más pequeña que existe. Abarca pocos metros alrededor de una persona.

**Analogía:** Imagina tu escritorio. Tienes tu móvil, tus auriculares Bluetooth y tu reloj inteligente. Todos ellos se comunican entre sí a muy corta distancia; eso es una PAN.

Ejemplos típicos de PAN:
- Bluetooth entre tu móvil y unos auriculares inalámbricos.
- La conexión entre tu portátil y un ratón inalámbrico.
- La sincronización entre un reloj inteligente y un teléfono móvil.

#### Redes de Área Local (LAN)

Una **LAN** (Local Area Network, o Red de Área Local) es la red que encontramos en un edificio, una oficina, una casa o un aula. Cubre un área geográfica limitada, normalmente unos pocos cientos de metros como máximo.

**Analogía:** Piensa en una LAN como las habitaciones de una casa conectadas por pasillos. Cada habitación es un dispositivo (un ordenador, una impresora, un móvil), y los pasillos son los cables o la señal Wi-Fi que los une. Todos comparten los mismos recursos: la misma conexión a Internet, la misma impresora, etc.

Características principales de una LAN:
- Generalmente es propiedad y está gestionada por una persona u organización.
- Ofrece altas velocidades de transferencia (desde 100 Mbps hasta 10 Gbps o más).
- Cubre un área geográfica reducida.
- Usa tecnologías como **Ethernet** (cableado) y **Wi-Fi** (inalámbrico).

#### Redes de Área Amplia (WAN)

Una **WAN** (Wide Area Network, o Red de Área Amplia) conecta redes LAN que están separadas por grandes distancias geográficas: entre ciudades, países e incluso continentes.

**Analogía:** Si una LAN es una casa, una WAN es la red de carreteras y autopistas que conecta casas que están en ciudades diferentes. Internet, de hecho, es la WAN más grande del mundo.

Características principales de una WAN:
- Conecta múltiples LANs a través de grandes distancias.
- Generalmente es gestionada por **proveedores de servicios de Internet (ISP)**.
- La velocidad suele ser menor que la de una LAN debido a las grandes distancias.
- Usa tecnologías como fibra óptica submarina, enlaces satelitales o conexiones de operadoras.

#### Internet

**Internet** es una red global de redes interconectadas. No es propiedad de ninguna persona ni organización; es un sistema descentralizado donde millones de redes (LANs, WANs y otras) se conectan entre sí mediante un conjunto común de reglas llamadas **protocolos**.

**Analogía:** Internet es como el sistema postal mundial. No importa en qué país estés; si escribes correctamente la dirección (la dirección IP), tu carta (los datos) llegará al destinatario.

Puntos clave sobre Internet:
- No pertenece a nadie en particular.
- Se basa en estándares y protocolos abiertos (como TCP/IP).
- Permite el acceso a servicios como la **World Wide Web (WWW)**, el correo electrónico, la mensajería instantánea, el streaming de vídeo, etc.

#### Comparativa de Tipos de Redes

| Tipo | Alcance | Ejemplo | Velocidad típica |
|------|---------|---------|-------------------|
| **PAN** | Pocos metros | Bluetooth móvil-auriculares | 1-3 Mbps |
| **LAN** | Un edificio / campus | Red de una oficina | 100 Mbps - 10 Gbps |
| **WAN** | Ciudades / países | Conexión entre sedes de una empresa | 1 Mbps - 100 Gbps |
| **Internet** | Mundial | La red global | Variable |

---

### 1.2 Transmisión de Datos

#### ¿Cómo viajan los datos por una red?

Los datos no viajan por la red como una carta completa dentro de un sobre. En realidad, se dividen en trozos pequeños llamados **paquetes**, y cada paquete viaja de forma independiente hasta llegar al destino, donde se reensamblan.

**Analogía:** Imagina que quieres enviar un libro entero por correo postal, pero las normas de correos solo permiten sobres pequeños. ¿Qué harías? Arrancar las páginas del libro, numerar cada una, meter cada página en un sobre diferente y enviarlas todas. El destinatario recibe todos los sobres, ordena las páginas por número y reconstruye el libro completo. Así funcionan los paquetes de datos.

#### Tipos de datos que viajan por la red

En la actualidad, las redes transportan tres tipos principales de datos:

1. **Datos (texto, ficheros):** Correos electrónicos, documentos, páginas web, bases de datos.
2. **Voz:** Llamadas telefónicas por Internet (VoIP), notas de voz.
3. **Vídeo:** Streaming de películas, videollamadas, vigilancia por cámaras IP.

Estos tres tipos de datos se llaman colectivamente **tráfico convergente**, porque todos viajan por la misma infraestructura de red. Hace años, la voz viajaba por la red telefónica, el vídeo por la televisión por cable y los datos por la red informática. Hoy, todo converge en una única red IP.

#### El concepto de paquete

Un **paquete** (a veces llamado segmento, trama o datagrama dependiendo de la capa del modelo de red, como veremos más adelante) contiene:

```
+-----------------------------------------------+
|  CABECERA          |  DATOS (Carga útil)       |
|  (Dirección origen)|                           |
|  (Dirección destino)|                          |
|  (Información de   |                           |
|   control)         |                           |
+-----------------------------------------------+
```

- **Cabecera (Header):** Información de control como las direcciones de origen y destino, el número de secuencia del paquete, etc. Es como la información que escribes en el exterior de un sobre postal.
- **Datos (Payload o carga útil):** La información real que se quiere transmitir. Es como la carta que va dentro del sobre.

#### Conmutación de paquetes frente a conmutación de circuitos

Existen dos formas fundamentales de transmitir datos:

**Conmutación de circuitos:** Se establece un camino dedicado entre el emisor y el receptor durante toda la comunicación. Es como cuando llamas por teléfono fijo: se reserva una línea exclusiva para tu llamada.

**Conmutación de paquetes:** Los paquetes viajan de forma independiente por diferentes rutas y se reensamblan en el destino. Internet funciona así. Es más eficiente porque la red se comparte entre muchos usuarios simultáneamente.

**Analogía:** Imagina una autopista. En la conmutación de circuitos, se cerraría un carril entero solo para tu coche hasta que llegases a tu destino. En la conmutación de paquetes, todos los coches (paquetes) comparten todos los carriles y cada uno puede tomar una ruta diferente para llegar al mismo sitio.

---

### 1.3 Ancho de Banda y Rendimiento

#### ¿Qué es el ancho de banda?

El **ancho de banda** (bandwidth) es la capacidad máxima teórica de un enlace de red para transportar datos. Se mide en **bits por segundo (bps)** y sus múltiplos.

**Analogía:** Piensa en una tubería de agua. El ancho de banda es el diámetro de la tubería. Una tubería más ancha (mayor ancho de banda) puede transportar más agua (datos) al mismo tiempo, pero eso no significa que siempre esté llena.

Unidades comunes de ancho de banda:

| Unidad | Abreviatura | Equivalencia |
|--------|-------------|--------------|
| Bits por segundo | bps | 1 bps |
| Kilobits por segundo | Kbps | 1.000 bps |
| Megabits por segundo | Mbps | 1.000.000 bps |
| Gigabits por segundo | Gbps | 1.000.000.000 bps |
| Terabits por segundo | Tbps | 1.000.000.000.000 bps |

> **¡Cuidado!** No confundas bits (b minúscula) con bytes (B mayúscula). 1 Byte = 8 bits. Cuando tu operador te dice que tienes "100 Mbps de fibra", se refiere a Mega**bits**. Si descargas un fichero y el navegador te dice "12,5 MB/s", se refiere a Mega**bytes**. 100 Mbps ÷ 8 = 12,5 MBps. ¡Es la misma velocidad expresada de dos formas distintas!

#### ¿Qué es el rendimiento (throughput)?

El **rendimiento** (throughput) es la cantidad real de datos que se transfieren con éxito a través de la red en un período de tiempo determinado. Siempre es igual o menor que el ancho de banda.

**Analogía:** Volviendo a la tubería de agua: el ancho de banda es el diámetro de la tubería (capacidad máxima), pero el rendimiento es la cantidad de agua que realmente fluye por ella en un momento dado. Si la tubería tiene piedras, barro o estrechamientos (congestión de red, errores, interferencias), el agua que fluye será menos que la capacidad máxima.

Factores que reducen el rendimiento respecto al ancho de banda:
- **Congestión de la red:** Demasiados usuarios usando la red al mismo tiempo.
- **Latencia:** El tiempo que tarda un paquete en viajar de origen a destino.
- **Errores en la transmisión:** Paquetes que se pierden y deben reenviarse.
- **Limitaciones del hardware:** Un dispositivo antiguo puede no alcanzar la velocidad máxima del enlace.

#### Latencia

La **latencia** es el tiempo que tarda un paquete en viajar desde el origen hasta el destino. Se mide en milisegundos (ms).

**Analogía:** Si el ancho de banda es el diámetro de la tubería y el rendimiento es cuánta agua fluye, la latencia es cuánto tiempo tarda una gota de agua en recorrer la tubería de un extremo a otro.

Una latencia baja es crítica para aplicaciones en tiempo real como:
- Videollamadas (si la latencia es alta, hay retrasos y la conversación se entrecorta).
- Juegos en línea (una latencia alta produce el temido "lag").
- Voz sobre IP (VoIP).

---

### 1.4 Resumen del Módulo 1

En este primer módulo hemos aprendido que:

- Una **red** conecta dispositivos para compartir información y recursos.
- Las redes se clasifican por su tamaño geográfico: **PAN** (personal), **LAN** (local), **WAN** (amplia) e **Internet** (global).
- Los datos se dividen en **paquetes** para viajar por la red, y se reensamblan en el destino.
- Las redes modernas son **convergentes**: transportan datos, voz y vídeo por la misma infraestructura.
- El **ancho de banda** es la capacidad máxima teórica del enlace, medido en bps.
- El **rendimiento** es la velocidad real de transferencia, siempre ≤ ancho de banda.
- La **latencia** es el tiempo que tarda un paquete en llegar de origen a destino.

> *Con estos conceptos fundamentales, ya tienes la base para entender cómo funcionan las redes. En el siguiente módulo, veremos los componentes físicos que hacen posible todo esto.*

---

## Módulo 2: Componentes de Red, Tipos y Conexiones

### 2.0 Introducción

> *Ahora que ya sabes qué es una red y cómo viajan los datos, es hora de "abrir el capó" y ver las piezas que componen una red. Al igual que un coche necesita motor, ruedas y volante para funcionar, una red necesita dispositivos, medios de transmisión y servicios para operar.*

En este módulo exploraremos los roles de clientes y servidores, los dispositivos de red fundamentales, y las diferentes formas de conectarnos a Internet a través de un proveedor de servicios.

---

### 2.1 Clientes y Servidores

#### El modelo Cliente-Servidor

En una red, los dispositivos pueden desempeñar dos roles fundamentales:

- **Cliente:** Es el dispositivo que **solicita** información o servicios. Tu navegador web, por ejemplo, actúa como cliente cuando pides una página web.
- **Servidor:** Es el dispositivo que **proporciona** la información o el servicio solicitado. El ordenador que aloja la página web y te la envía es el servidor.

**Analogía:** Piensa en un restaurante. Tú eres el cliente: pides la comida (solicitas datos). El cocinero y la cocina son el servidor: preparan la comida (procesan la solicitud) y te la sirven (envían los datos de vuelta).

Características del modelo cliente-servidor:
- Los servidores suelen ser ordenadores potentes que funcionan 24 horas al día, 7 días a la semana.
- Un único servidor puede atender a múltiples clientes simultáneamente.
- Los clientes inician la comunicación; los servidores responden.

#### El modelo Peer-to-Peer (P2P)

En una red **Peer-to-Peer (P2P)** o **red entre iguales**, cada dispositivo puede actuar simultáneamente como cliente y como servidor. No hay un servidor central dedicado.

**Analogía:** Es como un grupo de amigos que comparten apuntes. Cualquiera puede dar apuntes a otro (actuar como servidor) y al mismo tiempo pedirlos (actuar como cliente). No hay un "bibliotecario central".

| Característica | Cliente-Servidor | Peer-to-Peer |
|---------------|-----------------|--------------|
| Servidor dedicado | Sí | No |
| Escalabilidad | Alta | Limitada |
| Seguridad | Centralizada, más fácil de gestionar | Distribuida, más difícil |
| Coste | Mayor (requiere servidores) | Menor |
| Ejemplo | Página web de una empresa | Compartir archivos entre compañeros |

---

### 2.2 Componentes de Red

Para que una red funcione, necesitamos tres categorías de componentes:

#### 1. Dispositivos finales (End Devices)

Los **dispositivos finales** son los que los usuarios utilizan directamente. Son el origen o el destino de los datos en la red.

Ejemplos:
- **Ordenadores** de escritorio y portátiles.
- **Teléfonos móviles** y tabletas.
- **Impresoras** de red.
- **Cámaras IP** de seguridad.
- **Televisores inteligentes** (Smart TVs).
- **Servidores** (aunque sean potentes, técnicamente son dispositivos finales porque son el destino final de las peticiones).

**Analogía:** Los dispositivos finales son como las casas y los edificios de una ciudad. Son los puntos donde las personas viven y trabajan, es decir, donde se genera y se consume la información.

#### 2. Dispositivos intermedios (Intermediary Devices)

Los **dispositivos intermedios** son los que se encargan de dirigir y gestionar el tráfico de datos dentro de la red. No son el origen ni el destino de la comunicación del usuario, sino los "carteros" y "oficinas de correos" que aseguran que los datos lleguen a su destino.

Los más importantes son:

**Switch (conmutador):** Conecta múltiples dispositivos dentro de una misma LAN. Aprende las direcciones de los dispositivos conectados a cada uno de sus puertos y envía los datos solo al puerto correcto.

**Analogía del switch:** Es como un cartero inteligente dentro de un edificio de oficinas. Sabe exactamente en qué despacho está cada persona y entrega las cartas directamente, sin molestar a los demás.

**Enrutador (router):** Conecta diferentes redes entre sí y determina el mejor camino para que los paquetes lleguen de una red a otra. Es el dispositivo clave que conecta tu LAN doméstica con Internet.

**Analogía del enrutador:** Es como una rotonda en una carretera. Los coches (paquetes) llegan por diferentes direcciones y la rotonda (enrutador) les indica por qué salida deben continuar para llegar a su destino.

**Punto de acceso inalámbrico (Wireless Access Point - WAP):** Permite que los dispositivos inalámbricos se conecten a la red cableada.

**Cortafuegos (Firewall):** Dispositivo de seguridad que filtra el tráfico de red, permitiendo o bloqueando las comunicaciones según unas reglas predefinidas.

**Analogía del cortafuegos:** Es como el portero de una discoteca. Decide quién puede entrar (tráfico permitido) y quién no (tráfico bloqueado), según unas normas establecidas.

#### 3. Medios de red (Network Media)

Los **medios de red** son los canales por los que viajan los datos. Pueden ser físicos (cables) o inalámbricos (ondas):

- **Cable de cobre (par trenzado):** El cable más común en LANs, como el cable Ethernet (RJ-45) que conectas a tu ordenador.
- **Cable de fibra óptica:** Transmite datos mediante pulsos de luz. Más rápido y de mayor alcance que el cobre.
- **Inalámbrico (wireless):** Usa ondas de radio (Wi-Fi, Bluetooth) o infrarrojos.

> *Profundizaremos mucho más en los medios de red en el Módulo 6.*

#### Esquema de componentes de red

```
  [Dispositivos Finales]          [Dispositivos Intermedios]
  +-------------------+          +-------------------------+
  | - Ordenadores     |          | - Switches              |
  | - Móviles/Tablets |<-------->| - Enrutadores (Routers) |
  | - Impresoras      |  Medios  | - Puntos de Acceso (AP) |
  | - Servidores      |  de Red  | - Cortafuegos (Firewall)|
  | - Cámaras IP      |          +-------------------------+
  +-------------------+
         (Cables de cobre, fibra óptica, señal inalámbrica)
```

---

### 2.3 Opciones de Conectividad con el ISP

Un **ISP** (Internet Service Provider, o **Proveedor de Servicios de Internet**) es la empresa que te conecta a Internet. En España, ejemplos de ISP son Movistar, Vodafone, Orange, MásMóvil, etc.

#### Tipos de conexión al ISP

| Tipo de conexión | Medio | Velocidad típica | Notas |
|-----------------|-------|-------------------|-------|
| **Fibra óptica (FTTH)** | Fibra óptica hasta el hogar | 100 Mbps - 10 Gbps | La mejor opción disponible hoy. Muy extendida en España. |
| **DSL** (Digital Subscriber Line) | Línea telefónica de cobre | 1 - 100 Mbps | Usa el mismo cable que el teléfono fijo. Velocidad depende de la distancia a la centralita. |
| **Cable** | Cable coaxial de TV | 10 - 1000 Mbps | Compartido con el servicio de televisión por cable. |
| **Satélite** | Señal vía satélite | 1 - 100 Mbps | Útil en zonas rurales sin otra opción. Latencia alta. |
| **Inalámbrico celular (4G/5G)** | Ondas de radio móvil | 10 Mbps - 1 Gbps+ | Muy extendido para dispositivos móviles. |
| **Dial-up (telefónica)** | Línea telefónica | Hasta 56 Kbps | Tecnología obsoleta. Se menciona solo por completitud histórica. |

**Analogía:** Elegir un ISP y tipo de conexión es como elegir cómo ir al trabajo. Puedes ir en bicicleta (dial-up: lento pero funciona), en autobús (DSL: razonable pero compartido), en coche propio (cable: más rápido) o en AVE (fibra óptica: rapidísimo).

#### Conexión dentro del hogar

El ISP proporciona normalmente un **módem** o un **enrutador con módem integrado** (en España, lo que comúnmente llamamos "el router de la operadora"). Este dispositivo convierte la señal del ISP en una señal que tu red doméstica puede utilizar.

```
  Internet (ISP)
       |
  [Módem/Router de la operadora]
       |
  +----+----+----+
  |    |    |    |
  PC  Móvil TV  Tablet
```

---

### 2.4 Resumen del Módulo 2

En este módulo hemos aprendido que:

- Los dispositivos en red actúan como **clientes** (solicitan servicios) o **servidores** (proporcionan servicios). En redes **P2P**, un dispositivo puede ser ambas cosas.
- Las redes se componen de tres tipos de elementos: **dispositivos finales** (ordenadores, móviles), **dispositivos intermedios** (switches, enrutadores, cortafuegos) y **medios de red** (cables, señales inalámbricas).
- Un **switch** conecta dispositivos dentro de una misma LAN; un **enrutador** conecta redes diferentes entre sí.
- Un **ISP** nos conecta a Internet usando diferentes tecnologías: fibra óptica, DSL, cable, satélite o redes móviles.

> *Ya conoces los "ladrillos" con los que se construye una red. En el siguiente módulo, nos adentraremos en el mundo de las redes inalámbricas y los dispositivos móviles.*

---

## Módulo 3: Redes Inalámbricas y Móviles

### 3.0 Introducción

> *Hace no tantos años, conectarse a Internet significaba sentarse delante de un ordenador de sobremesa enchufado a la pared con un cable. Hoy, lo hacemos desde el sofá, desde la calle, desde un avión. Las redes inalámbricas han revolucionado nuestra forma de estar conectados.*

En este módulo descubriremos cómo funcionan las redes inalámbricas, los diferentes tipos de conectividad móvil y cómo nuestros smartphones y tabletas acceden a la red.

---

### 3.1 Redes Inalámbricas

#### ¿Qué es una red inalámbrica?

Una **red inalámbrica** (wireless network) permite la conexión de dispositivos sin necesidad de cables físicos, utilizando **ondas de radio** como medio de transmisión.

**Analogía:** Si una red cableada es como una autopista con carriles asfaltados, una red inalámbrica es como el tráfico aéreo: los aviones (datos) vuelan por el aire sin necesidad de carreteras físicas, pero necesitan reglas claras (protocolos) para no chocar entre sí.

#### Tipos principales de redes inalámbricas

**Wi-Fi (Wireless Fidelity):** Es el tipo de red inalámbrica más utilizado en hogares y empresas. Se basa en los estándares **IEEE 802.11** (que veremos en detalle en el Módulo 4). Un **punto de acceso inalámbrico (AP)** o un enrutador inalámbrico emite la señal Wi-Fi a la que se conectan los dispositivos.

**Bluetooth:** Tecnología de corto alcance (hasta unos 10 metros) para crear redes PAN. Se utiliza para auriculares, altavoces, ratones, teclados y transferencias rápidas de archivos entre dispositivos cercanos.

**NFC (Near Field Communication):** Comunicación de campo cercano, con un alcance de solo unos centímetros. Se usa para pagos contactless con el móvil, emparejamiento rápido de dispositivos y lectura de etiquetas inteligentes.

#### Componentes de una red Wi-Fi

- **Punto de acceso inalámbrico (AP):** El dispositivo que crea la red Wi-Fi. En los hogares suele estar integrado en el enrutador.
- **Adaptador inalámbrico:** La tarjeta de red Wi-Fi del dispositivo cliente (hoy en día integrada en prácticamente todos los ordenadores portátiles, móviles y tabletas).
- **SSID (Service Set Identifier):** El **nombre de la red Wi-Fi**. Es lo que ves cuando buscas redes disponibles en tu móvil (p.ej., "MiRedDeCasa", "Vodafone-A1B2").
- **Contraseña / Clave de seguridad:** La contraseña que protege el acceso a la red.

#### Ventajas e inconvenientes de las redes inalámbricas

| Ventajas | Inconvenientes |
|----------|---------------|
| Movilidad: te conectas desde cualquier punto dentro del alcance. | Velocidad generalmente menor que una conexión cableada equivalente. |
| Facilidad de instalación: no hace falta tirar cables. | Más susceptible a interferencias (paredes, otros dispositivos, microondas). |
| Flexibilidad: se pueden añadir dispositivos fácilmente. | Seguridad: la señal puede ser interceptada si no se cifra correctamente. |
| Coste de instalación reducido en muchos casos. | Alcance limitado que depende del entorno. |

---

### 3.2 Conectividad de Dispositivos Móviles

#### Redes de datos móviles

Los teléfonos móviles y tabletas con tarjeta SIM se conectan a Internet a través de las redes de datos móviles proporcionadas por los operadores de telecomunicaciones (Movistar, Orange, Vodafone, etc.).

Las generaciones de redes móviles han evolucionado enormemente:

| Generación | Nombre | Velocidad típica | Características |
|-----------|--------|-------------------|-----------------|
| **2G** | GSM | Hasta 50 Kbps | Llamadas de voz y SMS. Datos muy lentos. |
| **3G** | UMTS / HSPA | 1-10 Mbps | Navegación web básica, correo electrónico. |
| **4G** | LTE / LTE-Advanced | 10-100 Mbps | Streaming de vídeo HD, aplicaciones en tiempo real. |
| **5G** | NR (New Radio) | 100 Mbps - 10+ Gbps | Latencia ultra-baja, IoT masivo, realidad virtual. |

**Analogía:** Las generaciones de redes móviles son como las generaciones de coches. El 2G era un coche de los años 60: te llevaba del punto A al punto B, pero despacio. El 4G es un coche deportivo moderno. Y el 5G es un coche de competición con tecnología punta.

#### Conectividad Wi-Fi en dispositivos móviles

Los dispositivos móviles modernos pueden conectarse tanto a redes móviles (3G/4G/5G) como a redes Wi-Fi. Normalmente, los dispositivos priorizan la conexión Wi-Fi cuando está disponible porque:
- No consume datos del plan de la operadora.
- Suele ofrecer mayor velocidad en interiores.
- Menor consumo de batería en muchos casos.

#### Punto de acceso móvil (Hotspot / Tethering)

Un **hotspot móvil** o **anclaje de red (tethering)** permite que un teléfono móvil comparta su conexión de datos con otros dispositivos, convirtiéndose en un pequeño enrutador inalámbrico portátil.

**Analogía:** Es como si tu móvil se convirtiera en una fuente de agua portátil que permite beber a otros dispositivos cercanos, usando el agua (datos) que recibe de la red de la operadora.

Formas de hacer tethering:
- **Wi-Fi:** El móvil crea una red Wi-Fi a la que se conectan otros dispositivos (la forma más habitual).
- **Bluetooth:** Conexión más lenta pero menor consumo de batería.
- **USB:** Conexión por cable, la más rápida y estable.

#### GPS y servicios de localización

Los dispositivos móviles incorporan receptores **GPS** (Global Positioning System) que les permiten determinar su ubicación geográfica con precisión. Esto, combinado con la conectividad de red, habilita servicios como:
- Navegación (Google Maps, Waze).
- Aplicaciones de transporte (Uber, Cabify, Bolt).
- Redes sociales con geolocalización.
- Localización de dispositivos perdidos.

---

### 3.3 Resumen del Módulo 3

En este módulo hemos aprendido que:

- Las **redes inalámbricas** permiten la conexión sin cables, usando ondas de radio. Las principales tecnologías son **Wi-Fi**, **Bluetooth** y **NFC**.
- Una red Wi-Fi se identifica por su **SSID** (nombre de la red) y se protege con una contraseña.
- Las redes de datos **móviles** (2G, 3G, 4G, 5G) permiten la conectividad en cualquier lugar con cobertura de la operadora.
- El **tethering/hotspot** permite compartir la conexión de datos del móvil con otros dispositivos.
- Los dispositivos móviles combinan múltiples formas de conectividad (Wi-Fi, datos móviles, Bluetooth, NFC, GPS) para ofrecer una experiencia de conexión permanente.

> *Ya entiendes cómo los dispositivos inalámbricos se conectan a la red. En el siguiente módulo, pondremos todo esto en práctica y aprenderemos a configurar una red doméstica completa.*

---

## Módulo 4: Construir una Red Doméstica

### 4.0 Introducción

> *Todos tenemos una red en casa, aunque muchas veces ni nos damos cuenta. Ese "router" que nos instaló la operadora y al que se conecta toda la familia es el centro de nuestra red doméstica. En este módulo aprenderemos a entenderla y configurarla.*

Este módulo te convertirá en el "técnico de redes" de tu propia casa. Veremos qué componentes forman tu red doméstica, las tecnologías disponibles, los estándares Wi-Fi y cómo configurar correctamente un enrutador.

---

### 4.1 Fundamentos de la Red Doméstica

#### ¿Qué es una red doméstica?

Una **red doméstica** es una LAN (Red de Área Local) dentro de tu hogar que conecta todos tus dispositivos entre sí y con Internet.

Componentes típicos de una red doméstica:

1. **Enrutador inalámbrico** (normalmente proporcionado por el ISP): Es el corazón de la red. Realiza varias funciones en un solo dispositivo:
   - **Enrutador:** Dirige el tráfico entre tu red doméstica e Internet.
   - **Switch:** Tiene puertos Ethernet para conectar dispositivos por cable.
   - **Punto de acceso inalámbrico:** Emite la señal Wi-Fi.
   - **Módem:** Convierte la señal del ISP (fibra, ADSL) en señal Ethernet.

2. **Dispositivos conectados por cable:** Ordenadores de sobremesa, consolas de videojuegos, televisores inteligentes (Smart TVs), descodificadores.

3. **Dispositivos conectados por Wi-Fi:** Portátiles, móviles, tabletas, altavoces inteligentes, bombillas inteligentes, etc.

```
                        Internet
                           |
                    [Router del ISP]
                    /    |    |    \
                  /      |    |      \
    [PC sobremesa] [Smart TV] [Móvil] [Portátil]
     (Cable ETH)   (Cable ETH) (Wi-Fi)  (Wi-Fi)
```

**Analogía:** Tu red doméstica es como la instalación eléctrica de tu casa. El cuadro eléctrico principal (el router) recibe la electricidad de la calle (Internet) y la distribuye a todas las tomas de corriente (puertos y Wi-Fi) para que cada electrodoméstico (dispositivo) pueda funcionar.

#### Ventajas de tener una red doméstica bien configurada

- **Compartir la conexión a Internet** entre todos los dispositivos.
- **Compartir recursos**: impresoras, discos duros en red (NAS), archivos multimedia.
- **Domótica y hogar inteligente**: controlar luces, termostatos, cámaras, asistentes de voz.
- **Entretenimiento en red**: streaming a diferentes televisores, juegos en línea.

---

### 4.2 Tecnologías de Red en el Hogar

Dentro del hogar existen varias tecnologías para interconectar dispositivos:

#### Ethernet (red cableada)

La tecnología **Ethernet** (que veremos en profundidad en el Módulo 7) usa cables de par trenzado con conectores **RJ-45** para conectar dispositivos al enrutador o switch.

Ventajas del cable Ethernet en casa:
- Conexión estable y fiable.
- Velocidades altas (1 Gbps es lo estándar hoy en día).
- Sin interferencias.
- Ideal para dispositivos fijos: sobremesa, Smart TV, consola.

#### Wi-Fi (red inalámbrica)

Ya visto en el Módulo 3, es la forma más habitual de conectar dispositivos en el hogar. La mayoría de enrutadores domésticos emiten señal Wi-Fi en dos bandas de frecuencia:

- **2,4 GHz:** Mayor alcance, pero menor velocidad y más susceptible a interferencias (muchos dispositivos usan esta banda).
- **5 GHz:** Menor alcance, pero mayor velocidad y menos interferencias.
- **6 GHz (Wi-Fi 6E/7):** La banda más nueva, aún más rápida y con menor congestión.

**Analogía:** Las bandas de frecuencia son como las carreteras. La banda de 2,4 GHz es una carretera nacional: llega a más sitios pero tiene mucho tráfico. La banda de 5 GHz es una autopista: más rápida pero con menos salidas (menor alcance). La de 6 GHz es una autopista nueva con pocos coches todavía.

#### Powerline (PLC - Power Line Communication)

La tecnología **PLC** (Power Line Communication) o **Powerline** transmite datos a través del **cableado eléctrico** de la casa. Se usan adaptadores PLC que se enchufan a las tomas de corriente.

**Analogía:** Es como usar las tuberías de agua de la casa para enviar mensajes en miniatura dentro de cápsulas. La infraestructura ya existe (el cableado eléctrico), solo necesitas unos adaptadores especiales.

Es útil cuando:
- El Wi-Fi no llega bien a ciertas zonas de la casa.
- No se pueden tender cables Ethernet por la vivienda.

---

### 4.3 Estándares Inalámbricos

Los estándares Wi-Fi están definidos por el organismo **IEEE** (Institute of Electrical and Electronics Engineers) bajo la familia de estándares **802.11**. Cada nuevo estándar mejora la velocidad, el alcance y la eficiencia.

| Estándar IEEE | Nombre comercial | Banda de frecuencia | Velocidad máxima teórica | Año |
|--------------|-----------------|---------------------|--------------------------|-----|
| 802.11b | — | 2,4 GHz | 11 Mbps | 1999 |
| 802.11a | — | 5 GHz | 54 Mbps | 1999 |
| 802.11g | — | 2,4 GHz | 54 Mbps | 2003 |
| 802.11n | **Wi-Fi 4** | 2,4 y 5 GHz | 600 Mbps | 2009 |
| 802.11ac | **Wi-Fi 5** | 5 GHz | 6,9 Gbps | 2013 |
| 802.11ax | **Wi-Fi 6 / 6E** | 2,4, 5 y 6 GHz | 9,6 Gbps | 2019/2021 |
| 802.11be | **Wi-Fi 7** | 2,4, 5 y 6 GHz | 46 Gbps | 2024 |

> **Nota:** Las velocidades máximas teóricas nunca se alcanzan en la práctica, tal como aprendimos en el Módulo 1 sobre la diferencia entre ancho de banda y rendimiento.

#### Seguridad inalámbrica

Proteger la red Wi-Fi es fundamental. Los principales protocolos de seguridad son:

- **WEP** (Wired Equivalent Privacy): Antiguo e **inseguro**. No debe usarse nunca.
- **WPA** (Wi-Fi Protected Access): Mejora sobre WEP, pero también considerado obsoleto.
- **WPA2** (Wi-Fi Protected Access 2): Estándar actual ampliamente utilizado. Usa cifrado **AES**, muy robusto.
- **WPA3** (Wi-Fi Protected Access 3): El más reciente y seguro. Mejora la protección contra ataques de fuerza bruta y facilita la conexión de dispositivos IoT.

> **Consejo práctico:** Asegúrate siempre de que tu red Wi-Fi doméstica use como mínimo **WPA2**. Si tu enrutador soporta WPA3, úsalo.

---

### 4.4 Configurar un Enrutador Doméstico

#### Acceso a la interfaz de configuración

La mayoría de los enrutadores domésticos se configuran a través de una interfaz web accesible desde un navegador.

Pasos básicos:
1. Conectar tu ordenador al enrutador (por cable o Wi-Fi).
2. Abrir un navegador web.
3. Escribir la **dirección IP del enrutador** en la barra de direcciones. Las más comunes son:
   - `192.168.1.1`
   - `192.168.0.1`
   - `192.168.1.254` (común en enrutadores de Movistar)
4. Introducir el **usuario y contraseña** de administración (vienen en una pegatina en el propio enrutador o en la documentación del ISP).

#### Configuraciones básicas importantes

**Cambiar el nombre de la red (SSID):** Personalizar el nombre de tu red Wi-Fi. Es recomendable no usar datos personales (como tu nombre o número de piso).

**Cambiar la contraseña Wi-Fi:** Usar una contraseña robusta: al menos 12 caracteres, combinando mayúsculas, minúsculas, números y símbolos.

**Cambiar la contraseña de administración del enrutador:** Esto es diferente de la contraseña Wi-Fi. Es la clave para acceder a la configuración del enrutador. Si alguien accede con ella, puede controlar toda tu red.

**Seleccionar el modo de seguridad:** Elegir **WPA2** o **WPA3** como mínimo.

**Configurar DHCP:** El servicio **DHCP** (Dynamic Host Configuration Protocol) asigna automáticamente direcciones IP a cada dispositivo que se conecta a la red. Normalmente viene activado por defecto en los enrutadores domésticos. Lo veremos en profundidad en el Módulo 11.

**Actualizar el firmware:** El **firmware** es el software interno del enrutador. Mantenerlo actualizado es crucial para la seguridad y el rendimiento.

#### Esquema de configuración de un enrutador doméstico

```
  CONFIGURACIÓN DEL ENRUTADOR
  ============================
  
  RED INALÁMBRICA (Wi-Fi):
  ├── SSID: MiRedDeCasa
  ├── Seguridad: WPA2-Personal (AES)
  ├── Contraseña Wi-Fi: M1Cl@v3_S3gur@!
  ├── Banda: 2,4 GHz + 5 GHz (Dual Band)
  
  RED LOCAL (LAN):
  ├── Dirección IP del router: 192.168.1.1
  ├── Máscara de subred: 255.255.255.0
  ├── DHCP: Activado
  │   ├── Rango: 192.168.1.100 - 192.168.1.254
  │   ├── Puerta de enlace: 192.168.1.1
  │   └── DNS: 8.8.8.8 / 8.8.4.4
  
  ADMINISTRACIÓN:
  ├── Usuario admin: admin
  ├── Contraseña admin: [CAMBIAR POR DEFECTO]
  └── Firmware: Actualizado
```

---

### 4.5 Resumen del Módulo 4

En este módulo hemos aprendido que:

- Una **red doméstica** está compuesta por un enrutador (normalmente de la operadora) y los dispositivos que se conectan a él.
- Existen diferentes tecnologías para conectar dispositivos en casa: **Ethernet** (cable), **Wi-Fi** (inalámbrico) y **Powerline/PLC** (red eléctrica).
- Los estándares **Wi-Fi (802.11)** han evolucionado desde los 11 Mbps del 802.11b hasta los teóricos 46 Gbps del Wi-Fi 7.
- Las bandas de frecuencia principales son **2,4 GHz** (más alcance) y **5 GHz** (más velocidad).
- La seguridad Wi-Fi debe usar como mínimo **WPA2**, preferiblemente **WPA3**.
- Es fundamental **cambiar las contraseñas por defecto** del enrutador (tanto la del Wi-Fi como la de administración) y mantener el **firmware actualizado**.

> *¡Enhorabuena! Ya puedes configurar tu propia red doméstica de forma segura. En el siguiente módulo daremos un salto conceptual importante: entenderemos los principios y protocolos que hacen posible que los dispositivos se comuniquen entre sí.*

---

## Módulo 5: Principios de Comunicación

### 5.0 Introducción

> *¿Te has preguntado alguna vez cómo es posible que un ordenador fabricado por Apple en California pueda comunicarse sin problemas con un servidor Samsung en Corea del Sur? La respuesta está en los protocolos y estándares de comunicación: las "reglas del juego" que todos los dispositivos del mundo acuerdan seguir.*

En este módulo descubriremos qué son los protocolos, quién los crea, y los modelos de referencia (OSI y TCP/IP) que organizan la comunicación en red en capas bien definidas. Este es uno de los módulos más importantes del curso, porque sienta las bases teóricas que utilizaremos en todos los módulos siguientes.

---

### 5.1 Protocolos de Comunicación

#### ¿Qué es un protocolo?

Un **protocolo** es un conjunto de reglas que definen cómo se comunican los dispositivos en una red. Especifica el formato, el orden y las acciones que se deben tomar al enviar y recibir mensajes.

**Analogía:** Piensa en una conversación telefónica. Hay unas reglas implícitas que todos seguimos: descuelgas, dices "¿Dígame?", la otra persona se identifica, habláis por turnos, y al final os despedís y colgáis. Si cada uno siguiera reglas diferentes (uno habla en morse y el otro con señales de humo), la comunicación sería imposible. Los protocolos de red son exactamente eso: reglas comunes que permiten que todos los dispositivos se entiendan.

#### Elementos clave de un protocolo

Todos los protocolos de comunicación definen al menos estos tres aspectos:

1. **Formato del mensaje (codificación):** Cómo se estructura el mensaje. ¿Qué va primero? ¿Cuántos bits ocupa cada campo?
2. **Tamaño del mensaje:** El tamaño máximo de cada mensaje o fragmento.
3. **Temporización:** Cuándo enviar, cuánto esperar por una respuesta, y qué hacer si la respuesta no llega.
4. **Encapsulación:** Cómo se "empaquetan" los datos con la información de control necesaria (ya lo vimos brevemente en el Módulo 1 con los paquetes).
5. **Patrón del mensaje:** ¿Es una comunicación uno a uno (unicast)? ¿Uno a todos (broadcast)? ¿Uno a un grupo (multicast)?

#### Protocolos de red más comunes

| Protocolo | Función | Capa (referencia rápida) |
|-----------|---------|--------------------------|
| **HTTP / HTTPS** | Navegación web | Aplicación |
| **DNS** | Resolución de nombres de dominio a direcciones IP | Aplicación |
| **DHCP** | Asignación automática de direcciones IP | Aplicación |
| **FTP** | Transferencia de archivos | Aplicación |
| **SMTP / POP3 / IMAP** | Correo electrónico | Aplicación |
| **TCP** | Transporte fiable de datos | Transporte |
| **UDP** | Transporte rápido (sin garantía de entrega) | Transporte |
| **IP** (IPv4/IPv6) | Direccionamiento y enrutamiento | Red / Internet |
| **ICMP** | Diagnóstico de red (ping) | Red / Internet |
| **Ethernet (802.3)** | Comunicación en LAN cableada | Acceso a la red |
| **Wi-Fi (802.11)** | Comunicación en LAN inalámbrica | Acceso a la red |

> No te preocupes si no conoces todos estos protocolos aún. Los iremos descubriendo uno a uno en los módulos siguientes.

---

### 5.2 Estándares de Comunicación

#### ¿Por qué necesitamos estándares?

Los **estándares** son especificaciones técnicas publicadas por organismos reconocidos internacionalmente que garantizan la interoperabilidad entre fabricantes y tecnologías diferentes. Gracias a los estándares, un portátil Lenovo puede conectarse sin problemas a un enrutador Cisco mediante un cable fabricado por cualquier empresa.

**Analogía:** Los estándares de red son como las normas de circulación. No importa qué marca de coche conduzcas ni en qué país estés (dentro de Europa); si todos seguimos las mismas señales de tráfico y conducimos por el mismo lado de la carretera, el sistema funciona.

#### Organismos de estandarización principales

| Organismo | Nombre completo | Ámbito |
|-----------|----------------|--------|
| **IEEE** | Institute of Electrical and Electronics Engineers | Estándares de LAN y WLAN (Ethernet 802.3, Wi-Fi 802.11) |
| **IETF** | Internet Engineering Task Force | Protocolos de Internet (TCP/IP, HTTP, DNS). Publica los **RFC** (Request for Comments). |
| **IANA** | Internet Assigned Numbers Authority | Gestión de direcciones IP, nombres de dominio y números de puerto. |
| **ICANN** | Internet Corporation for Assigned Names and Numbers | Coordinación del sistema de nombres de dominio (DNS) global. |
| **ITU** | International Telecommunication Union | Telecomunicaciones internacionales (estándares de telefonía, fibra, etc.). |
| **ISO** | International Organization for Standardization | Modelo OSI, entre otros muchos estándares. |
| **Wi-Fi Alliance** | — | Certificación de compatibilidad Wi-Fi entre dispositivos. |

#### Estándares abiertos frente a estándares propietarios

- **Estándares abiertos:** Disponibles para cualquier fabricante o desarrollador. Fomentan la interoperabilidad. Ejemplos: TCP/IP, Ethernet, Wi-Fi.
- **Estándares propietarios:** Controlados por una empresa específica. Pueden limitar la interoperabilidad. Ejemplos: FaceTime de Apple (aunque se está abriendo), ciertos protocolos industriales.

---

### 5.3 Modelos de Comunicación en Red

Para organizar la complejidad de la comunicación en red, se utilizan **modelos en capas**. Cada capa realiza una función específica y se comunica con la capa inmediatamente superior e inferior. Los dos modelos fundamentales son el **modelo OSI** y el **modelo TCP/IP**.

#### ¿Por qué usar capas?

**Analogía:** Piensa en el sistema postal. Tú escribes una carta (capa de aplicación), la metes en un sobre y escribes la dirección (capa de transporte/red), el cartero la lleva a la oficina de correos (capa de enlace de datos), y la oficina de correos la envía en un camión o avión (capa física). Cada "capa" del sistema postal hace su trabajo sin necesidad de saber exactamente qué hacen las demás.

Ventajas de los modelos en capas:
- **Modularidad:** Se puede cambiar una capa sin afectar a las demás.
- **Facilidad de diseño:** Cada capa tiene una función clara.
- **Interoperabilidad:** Los fabricantes pueden crear productos para una capa específica.
- **Facilidad de diagnóstico:** Si algo falla, puedes identificar en qué capa está el problema.

#### El Modelo OSI (Open Systems Interconnection)

El **modelo OSI** fue creado por la **ISO** y tiene **7 capas**. Es un modelo de referencia teórico que ayuda a comprender cómo funcionan las comunicaciones, aunque en la práctica se utiliza más el modelo TCP/IP.

```
  +-----+----------------------------+------------------------------------+
  | Nº  | Capa                       | Función                            |
  +-----+----------------------------+------------------------------------+
  |  7  | Aplicación (Application)   | Interfaz con el usuario/software   |
  |  6  | Presentación (Presentation)| Formato de datos, cifrado          |
  |  5  | Sesión (Session)           | Control de diálogos/sesiones       |
  |  4  | Transporte (Transport)     | Entrega fiable extremo a extremo   |
  |  3  | Red (Network)              | Direccionamiento lógico y enrutam. |
  |  2  | Enlace de datos (Data Link)| Direccionamiento físico (MAC)      |
  |  1  | Física (Physical)          | Señales eléctricas/ópticas/radio   |
  +-----+----------------------------+------------------------------------+
```

**Regla mnemotécnica para recordar las capas (de arriba a abajo):**  
"**A** **P**edro **S**e **T**odo **R**esultó **E**n **F**iesta"  
(Aplicación, Presentación, Sesión, Transporte, Red, Enlace de datos, Física)

**Descripción de cada capa:**

- **Capa 7 - Aplicación:** Es la capa más cercana al usuario. Aquí operan los protocolos que interactúan directamente con las aplicaciones: HTTP (web), SMTP (correo), FTP (ficheros), DNS (resolución de nombres).

- **Capa 6 - Presentación:** Se encarga de la traducción y el formato de los datos. Por ejemplo, convierte datos entre diferentes formatos de codificación (ASCII, JPEG, MP4), cifra y descifra la información (SSL/TLS) y comprime datos.

- **Capa 5 - Sesión:** Gestiona, establece y termina las sesiones de comunicación entre dos dispositivos. Controla quién habla y cuándo (como un moderador en un debate).

- **Capa 4 - Transporte:** Se encarga de la entrega fiable de los datos de extremo a extremo. Aquí operan **TCP** (fiable, orientado a conexión) y **UDP** (rápido, sin conexión). Segmenta los datos y los reagrupa.

- **Capa 3 - Red:** Se encarga del **direccionamiento lógico** (direcciones IP) y del **enrutamiento** (decidir el mejor camino para que los paquetes lleguen a su destino). Los enrutadores operan en esta capa.

- **Capa 2 - Enlace de Datos:** Se encarga del **direccionamiento físico** (direcciones **MAC**) y del acceso al medio. Los switches operan en esta capa. Aquí se crean las **tramas (frames)**.

- **Capa 1 - Física:** Se ocupa de la transmisión de bits puros (0s y 1s) a través del medio físico: señales eléctricas en cables de cobre, pulsos de luz en fibra óptica u ondas de radio en Wi-Fi.

#### El Modelo TCP/IP

El **modelo TCP/IP** es el modelo práctico utilizado en Internet y en la mayoría de las redes actuales. Tiene **4 capas** y es más sencillo que el OSI porque agrupa algunas capas.

```
  +-----+-----------------------+------------------------------+
  | Nº  | Capa TCP/IP           | Equivalencia OSI             |
  +-----+-----------------------+------------------------------+
  |  4  | Aplicación            | Aplicación + Presentación    |
  |     |                       | + Sesión (capas 7, 6, 5)     |
  |  3  | Transporte            | Transporte (capa 4)          |
  |  2  | Internet              | Red (capa 3)                 |
  |  1  | Acceso a la Red       | Enlace de Datos + Física     |
  |     |                       | (capas 2 y 1)                |
  +-----+-----------------------+------------------------------+
```

#### Comparativa visual OSI vs TCP/IP

```
       MODELO OSI                    MODELO TCP/IP
  +-------------------+         +-------------------+
  | 7. Aplicación     |         |                   |
  +-------------------+         |                   |
  | 6. Presentación   |  <--->  |  4. Aplicación    |
  +-------------------+         |                   |
  | 5. Sesión         |         |                   |
  +-------------------+         +-------------------+
  | 4. Transporte     |  <--->  |  3. Transporte    |
  +-------------------+         +-------------------+
  | 3. Red            |  <--->  |  2. Internet      |
  +-------------------+         +-------------------+
  | 2. Enlace de Datos|         |                   |
  +-------------------+  <--->  | 1. Acceso a la Red|
  | 1. Física         |         |                   |
  +-------------------+         +-------------------+
```

#### Encapsulación de datos

Cuando los datos viajan desde la capa de Aplicación hasta la capa Física, cada capa añade su propia **cabecera** (y a veces un **trailer**) a los datos. Este proceso se llama **encapsulación**.

**Analogía:** Es como meter una carta dentro de sobres cada vez más grandes. Escribes la carta (datos de aplicación), la metes en un sobre con la dirección del destinatario (capa de transporte), ese sobre se mete en otro sobre más grande con las direcciones de red (capa de Internet/Red), y ese sobre se mete en un paquete postal con las etiquetas de la oficina de correos (capa de Acceso a la Red).

```
  Capa de Aplicación:    [          DATOS          ]
                              ↓ Encapsulación
  Capa de Transporte:    [Cab.TCP][     DATOS       ]  → Segmento
                              ↓ Encapsulación
  Capa de Internet:   [Cab.IP][Cab.TCP][  DATOS     ]  → Paquete
                              ↓ Encapsulación
  Capa de Acceso:  [Cab.ETH][Cab.IP][Cab.TCP][DATOS][Trl.ETH] → Trama
                              ↓
  Medio Físico:     01101001011010010110100101...     → Bits
```

**Nombre de los datos en cada capa (PDU - Protocol Data Unit):**

| Capa TCP/IP | Nombre de la PDU | Ejemplo |
|-------------|-------------------|---------|
| Aplicación | **Datos** | Página web HTML |
| Transporte | **Segmento** (TCP) / **Datagrama** (UDP) | Segmento TCP con puerto 80 |
| Internet | **Paquete** | Paquete IP con dir. origen y destino |
| Acceso a la Red | **Trama (Frame)** | Trama Ethernet con dir. MAC |
| Medio Físico | **Bits** | 01101001... |

---

### 5.4 Resumen del Módulo 5

En este módulo hemos aprendido que:

- Un **protocolo** es un conjunto de reglas que definen cómo se comunican los dispositivos en una red.
- Los **estándares** garantizan la interoperabilidad entre fabricantes. Organismos como **IEEE**, **IETF** e **ISO** los desarrollan y publican.
- El **modelo OSI** tiene 7 capas y es un modelo teórico de referencia.
- El **modelo TCP/IP** tiene 4 capas y es el modelo práctico utilizado en Internet.
- La **encapsulación** es el proceso por el que cada capa añade su cabecera a los datos, creando una PDU específica: Datos → Segmento → Paquete → Trama → Bits.

> *Este módulo es fundamental. Los conceptos de capas, protocolos y encapsulación aparecerán una y otra vez en el resto del curso. Tómate tu tiempo para asimilarlo bien antes de continuar.*

---

## Módulo 6: Medios de Red

### 6.0 Introducción

> *Si los protocolos son las "reglas del idioma" que hablan los dispositivos, los medios de red son las "carreteras" por las que viajan los datos. Sin un medio físico (o inalámbrico), los datos no tendrían forma de ir de un sitio a otro. En este módulo exploraremos los tres tipos principales de medios de red.*

---

### 6.1 Tipos de Medios de Red

Los medios de red se dividen en tres grandes categorías:

#### 1. Cable de cobre

El **cable de cobre** transmite datos mediante **señales eléctricas**. Es el medio más antiguo y más extendido en redes LAN.

**Tipos principales de cable de cobre:**

**a) Par trenzado (Twisted Pair):**  
Es el tipo de cable más utilizado en redes locales. Consiste en pares de hilos de cobre trenzados entre sí para reducir las interferencias electromagnéticas.

```
  Cable de Par Trenzado (vista en sección):
  
  +----------------------------------+
  |  Cubierta exterior               |
  |  +---+  +---+  +---+  +---+     |
  |  | ⟳ |  | ⟳ |  | ⟳ |  | ⟳ |    |  ← 4 pares trenzados
  |  +---+  +---+  +---+  +---+     |     (8 hilos en total)
  |                                  |
  +----------------------------------+
          Conector: RJ-45
```

Existen dos variantes:
- **UTP (Unshielded Twisted Pair):** Par trenzado **sin blindaje**. Es el más común en instalaciones domésticas y de oficina. Más económico pero más susceptible a interferencias.
- **STP (Shielded Twisted Pair):** Par trenzado **con blindaje** (una capa protectora metálica). Más resistente a interferencias, usado en entornos industriales.

**Categorías de cable UTP:**

| Categoría | Velocidad máxima | Frecuencia | Uso típico |
|-----------|-----------------|------------|------------|
| **Cat 5** | 100 Mbps | 100 MHz | Redes antiguas (Fast Ethernet) |
| **Cat 5e** | 1 Gbps | 100 MHz | Redes domésticas y de oficina |
| **Cat 6** | 1 Gbps (10 Gbps hasta 55m) | 250 MHz | Redes empresariales |
| **Cat 6a** | 10 Gbps | 500 MHz | Centros de datos, redes de alto rendimiento |
| **Cat 7** | 10 Gbps | 600 MHz | Entornos con altas interferencias |
| **Cat 8** | 25-40 Gbps | 2000 MHz | Centros de datos de alta velocidad |

> **Consejo práctico:** Para una instalación doméstica o de oficina actual, el cable **Cat 6** o **Cat 6a** es la mejor relación calidad/precio.

**b) Cable coaxial:**  
Tiene un conductor central rodeado de un aislante y una malla metálica. Se usó ampliamente para televisión por cable y para las primeras redes Ethernet. Hoy en día su uso en redes de datos es muy limitado, pero sigue presente en instalaciones de televisión por cable e Internet por cable (tecnología DOCSIS).

```
  Cable Coaxial (vista en sección):
  
       Cubierta exterior
      +--------------------+
      |   Malla metálica   |
      |  +==============+  |
      |  |  Aislante    |  |
      |  |  +--------+  |  |
      |  |  |Conductor|  |  |
      |  |  | central |  |  |
      |  |  +--------+  |  |
      |  +==============+  |
      +--------------------+
```

#### 2. Cable de fibra óptica

El **cable de fibra óptica** transmite datos mediante **pulsos de luz** a través de hilos de vidrio o plástico extremadamente finos. Es el medio más rápido y de mayor alcance disponible.

**Analogía:** Si el cable de cobre es como enviar mensajes con señales eléctricas por un cable, la fibra óptica es como enviar mensajes con una linterna a través de un tubo transparente. La luz viaja mucho más rápido y puede recorrer distancias enormes sin degradarse.

```
  Cable de Fibra Óptica (vista en sección):
  
      +-----------------------------+
      |  Cubierta exterior          |
      |  +=======================+  |
      |  | Revestimiento (125µm) |  |
      |  |  +==================+ |  |
      |  |  | Núcleo (9-62,5µm)| |  |  ← Aquí viaja la luz
      |  |  +==================+ |  |
      |  +=======================+  |
      +-----------------------------+
```

**Tipos de fibra óptica:**

| Tipo | Diámetro del núcleo | Distancia máxima | Velocidad | Uso |
|------|--------------------|--------------------|-----------|-----|
| **Monomodo (SMF)** | 9 µm | Hasta 100+ km | Hasta 100+ Gbps | WANs, conexiones de larga distancia |
| **Multimodo (MMF)** | 50-62,5 µm | Hasta 2 km | Hasta 100 Gbps | LANs, dentro de edificios |

**Ventajas de la fibra óptica:**
- Velocidades muy altas (desde Gbps hasta Tbps).
- Gran alcance sin degradación de la señal.
- Inmune a interferencias electromagnéticas.
- Más segura: es muy difícil interceptar la señal.
- Ligera y delgada.

**Inconvenientes:**
- Coste más elevado que el cobre (especialmente los conectores y equipos).
- Más frágil que el cobre; requiere cuidado en la instalación.
- Necesita herramientas especializadas para su instalación y reparación.

#### 3. Medios inalámbricos

Los **medios inalámbricos** transmiten datos mediante **ondas electromagnéticas** (ondas de radio, microondas, infrarrojos).

Como vimos en los Módulos 3 y 4, las principales tecnologías inalámbricas son:
- **Wi-Fi (802.11):** Para redes LAN inalámbricas.
- **Bluetooth:** Para redes PAN de corto alcance.
- **Redes celulares (4G/5G):** Para conectividad móvil de área amplia.
- **Satélite:** Para zonas remotas sin otra infraestructura.

**Factores que afectan a la señal inalámbrica:**
- **Distancia:** A mayor distancia, menor intensidad de la señal.
- **Obstáculos:** Paredes, suelos y objetos metálicos atenúan la señal.
- **Interferencias:** Otros dispositivos que emiten en la misma frecuencia (microondas, teléfonos inalámbricos, redes Wi-Fi vecinas).
- **Cantidad de usuarios:** A más dispositivos conectados, menor ancho de banda disponible para cada uno.

#### Tabla comparativa de medios de red

| Característica | Cobre (UTP) | Fibra Óptica | Inalámbrico |
|---------------|-------------|--------------|-------------|
| Señal | Eléctrica | Luz | Ondas de radio |
| Velocidad máxima | 10 Gbps (Cat 6a) | 100+ Gbps | Hasta 46 Gbps (Wi-Fi 7, teórico) |
| Distancia máxima | 100 m (par trenzado) | 100+ km (monomodo) | Variable (metros a km) |
| Interferencias | Susceptible a EMI | Inmune | Muy susceptible |
| Coste | Bajo | Medio-alto | Bajo-medio |
| Instalación | Sencilla | Especializada | Muy sencilla |
| Seguridad física | Media | Alta | Baja (señal accesible por el aire) |

---

### 6.2 Resumen del Módulo 6

En este módulo hemos aprendido que:

- Existen tres tipos de medios de red: **cobre**, **fibra óptica** e **inalámbricos**.
- El **cable de cobre** (especialmente el par trenzado UTP con conector RJ-45) es el más común en redes LAN. Las categorías van de Cat 5 a Cat 8.
- La **fibra óptica** usa pulsos de luz, ofrece las mayores velocidades y distancias, y es inmune a interferencias. Existe en variantes **monomodo** (larga distancia) y **multimodo** (corta distancia).
- Los **medios inalámbricos** ofrecen flexibilidad y movilidad, pero son más susceptibles a interferencias y problemas de seguridad.
- La elección del medio depende de factores como la velocidad necesaria, la distancia, el coste y el entorno.

> *Ahora que conoces los "caminos" por los que viajan los datos, en el siguiente módulo veremos qué ocurre cuando los datos llegan a un switch en la capa de acceso de la red.*

---

## Módulo 7: La Capa de Acceso

### 7.0 Introducción

> *Imagina que los datos que envías desde tu ordenador son como un paquete que envías por mensajería. Antes de salir de tu edificio, el paquete necesita una etiqueta con la dirección del siguiente punto de entrega. Eso es exactamente lo que hace la capa de acceso: prepara los datos para viajar por el medio físico local.*

En este módulo aprenderemos sobre la encapsulación en la capa de enlace de datos, la estructura de una trama Ethernet y el papel fundamental del switch en la capa de acceso.

---

### 7.1 Encapsulación y la Trama Ethernet

#### ¿Qué ocurre en la Capa de Acceso a la Red?

Recordando lo que aprendimos en el Módulo 5, la capa de Acceso a la Red del modelo TCP/IP (equivalente a las capas 1 y 2 del modelo OSI) es responsable de:
- Colocar los datos en el medio físico (cable, fibra, ondas de radio).
- Direccionar los datos al dispositivo correcto dentro de la red local (LAN).

Para ello, la capa de enlace de datos encapsula el paquete IP dentro de una **trama (frame)**, añadiendo las direcciones físicas de origen y destino.

#### La dirección MAC

Cada tarjeta de red (NIC - Network Interface Card) de cada dispositivo tiene una **dirección MAC** (Media Access Control) única a nivel mundial. Es un identificador de 48 bits (6 bytes) que se escribe habitualmente en formato hexadecimal.

**Formato de una dirección MAC:**

```
  AA:BB:CC:DD:EE:FF
  |------| |------|
  OUI       Identificador del dispositivo
  (fabricante)

  Ejemplo real: 00:1A:2B:3C:4D:5E
```

- Los primeros 3 bytes (OUI - Organizationally Unique Identifier) identifican al **fabricante** (por ejemplo, Intel, Cisco, Samsung).
- Los últimos 3 bytes son asignados por el fabricante y son únicos para cada dispositivo.

**Analogía:** Si la dirección IP es como tu dirección postal (puede cambiar si te mudas), la dirección MAC es como tu DNI o número de pasaporte: es única, viene "de fábrica" y normalmente no cambia.

| Característica | Dirección IP | Dirección MAC |
|---------------|-------------|---------------|
| Capa | Red (Capa 3) | Enlace de Datos (Capa 2) |
| Longitud | 32 bits (IPv4) / 128 bits (IPv6) | 48 bits |
| Formato | Decimal con puntos (192.168.1.1) | Hexadecimal con dos puntos o guiones |
| Asignación | Configurada manual o automáticamente (DHCP) | Grabada de fábrica en la tarjeta de red |
| Alcance | Global (puede cruzar redes) | Local (solo válida dentro de la LAN) |

#### Estructura de la Trama Ethernet

La **trama Ethernet** es la PDU de la capa 2 (enlace de datos). Su estructura es:

```
+----------+---------+---------+------+-----------+-----+
| Preámbulo| Dir.MAC | Dir.MAC | Tipo |   DATOS   | FCS |
|  (8B)    | Destino | Origen  | (2B) | (46-1500B)|     |
|          |  (6B)   |  (6B)   |      |           |(4B) |
+----------+---------+---------+------+-----------+-----+
                 CABECERA                           COLA
```

- **Preámbulo (8 bytes):** Secuencia de sincronización que avisa al receptor de que viene una trama.
- **Dirección MAC de destino (6 bytes):** ¿A quién va dirigida la trama?
- **Dirección MAC de origen (6 bytes):** ¿Quién envía la trama?
- **Tipo / Longitud (2 bytes):** Indica qué protocolo de capa superior está encapsulado (por ejemplo, 0x0800 = IPv4, 0x86DD = IPv6).
- **Datos (46-1500 bytes):** El paquete IP (u otros datos de capa superior). Si son menos de 46 bytes, se rellena con datos de relleno (padding).
- **FCS - Frame Check Sequence (4 bytes):** Código de detección de errores (CRC) que permite al receptor verificar si la trama llegó sin corrupciones.

**Analogía de la trama Ethernet:** Piensa en un sobre postal. La dirección del destinatario es la MAC de destino. La dirección del remitente es la MAC de origen. El sello indica el tipo de servicio (Tipo/Longitud). La carta dentro del sobre son los Datos. Y el código de barras del servicio de rastreo es el FCS.

---

### 7.2 La Capa de Acceso

#### El papel del Switch en la capa de acceso

El **switch Ethernet** (conmutador) es el dispositivo estrella de la capa de acceso. Su función principal es **reenviar tramas Ethernet al puerto correcto**, basándose en la dirección MAC de destino.

#### ¿Cómo funciona un switch?

El switch mantiene una tabla interna llamada **tabla de direcciones MAC** (MAC Address Table o tabla CAM). Esta tabla asocia cada dirección MAC conocida con el puerto físico del switch donde está conectado ese dispositivo.

**Proceso paso a paso:**

1. **Aprendizaje:** Cuando el switch recibe una trama, examina la dirección MAC de **origen** y la asocia con el puerto por el que llegó. Así "aprende" qué dispositivos están conectados a qué puertos.

2. **Reenvío:** El switch examina la dirección MAC de **destino**:
   - Si la MAC de destino está en su tabla → envía la trama **solo por ese puerto** (reenvío unicast).
   - Si la MAC de destino NO está en su tabla → envía la trama por **todos los puertos excepto el de origen** (inundación/flooding). Esto asegura que la trama llegue al destino aunque el switch aún no lo conozca.

3. **Filtrado:** El switch nunca reenvía una trama por el mismo puerto por el que la recibió.

**Ejemplo ilustrado:**

```
  Tabla MAC del Switch (tras el aprendizaje):
  +-------------------+--------+
  | Dirección MAC     | Puerto |
  +-------------------+--------+
  | AA:AA:AA:AA:AA:AA | F0/1   |
  | BB:BB:BB:BB:BB:BB | F0/2   |
  | CC:CC:CC:CC:CC:CC | F0/3   |
  +-------------------+--------+

  Escenario: PC-A (AA:AA) envía una trama a PC-C (CC:CC)

  [PC-A] ---F0/1--- [SWITCH] ---F0/3--- [PC-C]  ← La trama va SOLO al F0/3
                       |
                      F0/2
                       |
                     [PC-B]  ← PC-B NO recibe la trama (filtrado)
```

**Analogía:** Un switch es como un cartero inteligente dentro de un bloque de pisos. Conoce en qué piso vive cada vecino (tabla MAC) y entrega cada carta directamente al buzón correcto, sin dejarla en los buzones de los demás.

#### Switch frente a Hub

Antes de los switches, se usaban **hubs** (concentradores). Un hub reenviaba cada trama recibida por TODOS los puertos, sin inteligencia alguna. Era como un cartero que mete una copia de cada carta en TODOS los buzones del bloque.

| Característica | Hub | Switch |
|---------------|-----|--------|
| Reenvío | A todos los puertos | Solo al puerto correcto |
| Inteligencia | Ninguna (Capa 1) | Tabla MAC (Capa 2) |
| Colisiones | Un único dominio de colisión | Un dominio de colisión por puerto |
| Rendimiento | Bajo | Alto |
| Uso actual | Obsoleto | Estándar |

---

### 7.3 Resumen del Módulo 7

En este módulo hemos aprendido que:

- La capa de acceso se encarga de preparar los datos para viajar por la red local, encapsulándolos en **tramas Ethernet**.
- Cada dispositivo tiene una **dirección MAC** única de 48 bits, grabada de fábrica en su tarjeta de red.
- La **trama Ethernet** contiene: preámbulo, MAC de destino, MAC de origen, tipo, datos y FCS.
- El **switch** opera en la capa 2 y usa una **tabla de direcciones MAC** para reenviar las tramas solo al puerto correcto, mejorando drásticamente el rendimiento respecto a los antiguos hubs.
- El switch aprende las direcciones MAC de forma automática examinando las tramas que recibe.

> *Ahora entiendes cómo viajan los datos dentro de una red local. Pero, ¿cómo saben los datos a qué red deben ir? Eso es tarea de la dirección IP, que veremos en el siguiente módulo.*

---

## Módulo 8: El Protocolo de Internet

### 8.0 Introducción

> *La dirección MAC, como acabamos de ver, sirve para identificar dispositivos dentro de una red local. Pero, ¿qué pasa cuando quieres enviar datos a un dispositivo que está en otra red, quizá en otro país? Para eso necesitamos un sistema de direccionamiento universal: el Protocolo de Internet (IP).*

En este módulo nos adentraremos en el mundo del **IPv4**: su propósito, su estructura y cómo funciona para identificar cada dispositivo en cualquier red del mundo.

---

### 8.1 Propósito de una Dirección IPv4

#### ¿Qué es una dirección IPv4?

Una **dirección IPv4** es un identificador lógico de 32 bits que se asigna a cada dispositivo (interfaz) conectado a una red que utiliza el protocolo IP. Es el equivalente a una dirección postal en el mundo digital.

**Analogía:** Si la dirección MAC es como tu DNI (identifica quién eres físicamente), la dirección IPv4 es como tu dirección postal (identifica dónde estás ubicado en la "ciudad de Internet"). Puedes mudarte (cambiar de IP), pero tu DNI (MAC) sigue siendo el mismo.

#### Características fundamentales

- **Longitud:** 32 bits (4 bytes).
- **Formato:** Se escribe en **notación decimal con puntos** (dotted decimal), separando los 4 bytes con puntos.
- **Ejemplo:** `192.168.1.10`
- **Rango:** Cada octeto (byte) va de 0 a 255.

Cada dirección IPv4 tiene dos partes:
- **Parte de red (Network ID):** Identifica a qué red pertenece el dispositivo. Es como el nombre de la calle.
- **Parte de host:** Identifica al dispositivo concreto dentro de esa red. Es como el número del portal.

```
  Dirección IP: 192.168.1.10
  
  |  Parte de Red  | Parte de Host |
  |  192.168.1     |      .10      |
  
  Analogía postal:
  |  Calle Mayor   |   Nº 10      |
```

> Cómo se determina qué parte es la de red y cuál la de host depende de la **máscara de subred**, que veremos en la siguiente sección.

#### ¿Quién necesita una dirección IP?

Todos los dispositivos que quieran comunicarse en una red IP necesitan al menos una dirección IP:
- Ordenadores, portátiles, móviles y tabletas.
- Servidores web, de correo, de ficheros, etc.
- Enrutadores (una dirección IP en cada interfaz/puerto).
- Impresoras de red, cámaras IP, dispositivos IoT.

---

### 8.2 Estructura de la Dirección IPv4

#### Representación binaria

Aunque nosotros escribimos las direcciones IPv4 en decimal (p.ej., `192.168.1.10`), los ordenadores las procesan en **binario** (0s y 1s).

Cada octeto es un número de 8 bits:

```
  Decimal:    192    .   168    .     1    .    10
  Binario: 11000000 . 10101000 . 00000001 . 00001010
           |  8 bits | 8 bits  |  8 bits  |  8 bits |
           |      Total: 32 bits (4 bytes)           |
```

**Tabla de conversión rápida de posiciones binarias:**

| Posición | 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
|----------|----|----|----|----|---|---|---|---|
| Bit | 2⁷ | 2⁶ | 2⁵ | 2⁴ | 2³ | 2² | 2¹ | 2⁰ |

**Ejemplo:** Convertir 192 a binario:
- 192 = 128 + 64 = 2⁷ + 2⁶
- Binario: **11000000**

**Ejemplo:** Convertir 168 a binario:
- 168 = 128 + 32 + 8 = 2⁷ + 2⁵ + 2³
- Binario: **10101000**

#### La Máscara de Subred

La **máscara de subred** (Subnet Mask) es un número de 32 bits que determina qué parte de la dirección IP es la porción de red y cuál es la porción de host.

Funciona así: donde la máscara tiene **1s en binario**, esa parte de la IP corresponde a la **red**. Donde tiene **0s**, corresponde al **host**.

```
  Dir. IP:      192.168.1    .10
  Binario IP:   11000000.10101000.00000001 . 00001010
  Máscara:      11111111.11111111.11111111 . 00000000
  Máscara Dec:  255  .  255  .  255  .  0
                |------ RED --------------|--- HOST --|
```

**Notación CIDR (Classless Inter-Domain Routing):** En lugar de escribir la máscara completa, se usa una barra seguida del número de bits de red. Por ejemplo, la máscara 255.255.255.0 tiene 24 bits de red, por lo que se escribe: `192.168.1.10 /24`.

**Máscaras de subred más comunes:**

| Máscara en decimal | Notación CIDR | Bits de red | Bits de host | Hosts posibles |
|-------------------|---------------|-------------|--------------|----------------|
| 255.0.0.0 | /8 | 8 | 24 | 16.777.214 |
| 255.255.0.0 | /16 | 16 | 16 | 65.534 |
| 255.255.255.0 | /24 | 24 | 8 | 254 |
| 255.255.255.128 | /25 | 25 | 7 | 126 |
| 255.255.255.192 | /26 | 26 | 6 | 62 |
| 255.255.255.224 | /27 | 27 | 5 | 30 |
| 255.255.255.240 | /28 | 28 | 4 | 14 |
| 255.255.255.248 | /29 | 29 | 3 | 6 |
| 255.255.255.252 | /30 | 30 | 2 | 2 |

> **Nota:** El número de hosts posibles es 2^n - 2 (siendo n el número de bits de host). Se restan 2 porque la primera dirección se reserva como **dirección de red** y la última como **dirección de difusión (broadcast)**.

#### Dirección de Red, Dirección de Host y Dirección de Difusión

En cualquier red IPv4 hay tres tipos de direcciones especiales:

1. **Dirección de red:** Todos los bits de host a 0. Identifica a la red en sí (no se asigna a ningún dispositivo).
2. **Dirección de difusión (broadcast):** Todos los bits de host a 1. Los mensajes enviados a esta dirección llegan a TODOS los dispositivos de esa red.
3. **Direcciones de host:** Todas las direcciones entre la de red y la de broadcast. Son las que se asignan a dispositivos.

**Ejemplo con la red 192.168.1.0/24:**

```
  Dir. de Red:       192.168.1.0       (todos los bits de host = 0)
  Primera IP útil:   192.168.1.1       (primera asignable a un dispositivo)
  Última IP útil:    192.168.1.254     (última asignable a un dispositivo)
  Dir. de Broadcast: 192.168.1.255     (todos los bits de host = 1)
  
  Total de IPs:      256 (de .0 a .255)
  IPs asignables:    254 (de .1 a .254)
```

#### La puerta de enlace predeterminada (Default Gateway)

La **puerta de enlace predeterminada** (default gateway) es la dirección IP del enrutador de tu red local. Es la "puerta de salida" para los datos que necesitan ir a otra red (por ejemplo, a Internet).

**Analogía:** Si tu red local es tu barrio, la puerta de enlace es la salida del barrio a la carretera principal. Si quieres ir a cualquier sitio fuera de tu barrio, tienes que pasar por esa salida.

Normalmente, la puerta de enlace es la primera o la última dirección IP útil de la red:
- `192.168.1.1` (muy común en redes domésticas en España).
- `192.168.1.254`

---

### 8.3 Resumen del Módulo 8

En este módulo hemos aprendido que:

- Una **dirección IPv4** es un identificador lógico de 32 bits escrito en notación decimal con puntos (p.ej., 192.168.1.10).
- Cada dirección tiene una **parte de red** y una **parte de host**, determinadas por la **máscara de subred**.
- La notación **CIDR** (/24, /16, etc.) indica cuántos bits corresponden a la parte de red.
- En cada red hay tres direcciones especiales: la **dirección de red** (bits de host = 0), la **dirección de broadcast** (bits de host = 1) y las **direcciones de host** asignables (todas las demás).
- La **puerta de enlace predeterminada** es la IP del enrutador local, necesaria para comunicarse con otras redes.

> *¡Ya dominas los fundamentos de IPv4! En el siguiente módulo profundizaremos en los tipos de comunicación (unicast, broadcast, multicast), las clases de direcciones IP y la segmentación de redes.*

---

## Módulo 9: IPv4 y Segmentación de Redes

### 9.0 Introducción

> *Ahora que ya sabes qué es una dirección IPv4 y cómo está formada, vamos a profundizar. ¿Qué ocurre cuando un dispositivo envía datos a un solo destinatario? ¿Y a todos los dispositivos de la red? ¿Y a un grupo selecto? Además, veremos por qué es importante dividir las redes grandes en subredes más pequeñas.*

---

### 9.1 IPv4 Unidifusión, Difusión y Multidifusión

Existen tres tipos de comunicación en redes IPv4:

#### Unidifusión (Unicast)

La comunicación **unicast** envía datos de **un emisor a un único receptor**. Es el tipo más común de comunicación en redes.

**Analogía:** Es como enviar una carta postal a una persona concreta. Solo esa persona la recibe.

- Se usa una dirección IP de destino que identifica a un único dispositivo.
- Ejemplo: Navegar por una página web (tu ordenador se comunica con el servidor web).

#### Difusión (Broadcast)

La comunicación **broadcast** envía datos de **un emisor a TODOS los dispositivos** de la misma red local.

**Analogía:** Es como poner un anuncio por la megafonía de un edificio: todos los que están en el edificio lo escuchan.

- Se usa la **dirección de broadcast** de la red como destino (p.ej., 192.168.1.255 en una red /24).
- Existe también la dirección de **broadcast limitado**: `255.255.255.255`, que se dirige a todos los dispositivos de la red local.
- Ejemplo: El protocolo DHCP usa broadcast para que un dispositivo nuevo descubra el servidor DHCP en la red.

> **Importante:** Los broadcasts no cruzan los enrutadores. Quedan confinados dentro de la red local. Esta propiedad es fundamental y la veremos con más detalle en el Módulo 13.

#### Multidifusión (Multicast)

La comunicación **multicast** envía datos de **un emisor a un grupo selecto de receptores** que se han "suscrito" a una dirección multicast específica.

**Analogía:** Es como una lista de correo electrónico o un grupo de WhatsApp: solo reciben el mensaje los miembros del grupo, no todos los del edificio.

- Usa direcciones del rango **224.0.0.0 a 239.255.255.255**.
- Ejemplo: Streaming de vídeo en directo donde solo los espectadores interesados reciben la transmisión.

```
  UNICAST:     [PC-A] ---------> [PC-B]
                (uno a uno)

  BROADCAST:   [PC-A] ---------> [TODOS]
                (uno a todos en la LAN)

  MULTICAST:   [PC-A] ---------> [PC-B, PC-D, PC-F]
                (uno a un grupo)
```

---

### 9.2 Tipos de Direcciones IPv4

#### Direcciones públicas y privadas

**Direcciones públicas:** Son únicas a nivel mundial y enrutables en Internet. Las asigna tu ISP. Cualquier dispositivo con una IP pública puede ser alcanzado directamente desde Internet.

**Direcciones privadas:** Están reservadas para uso interno en redes locales (LANs) y NO son enrutables en Internet. Pueden repetirse en diferentes redes privadas sin conflicto.

**Analogía:** Las direcciones públicas son como los números de teléfono fijo (únicos en el mundo). Las direcciones privadas son como las extensiones internas de una empresa: la extensión 101 puede existir en mil empresas diferentes sin problema, pero solo funciona dentro de cada empresa.

**Rangos de direcciones IP privadas (RFC 1918):**

| Clase | Rango de direcciones privadas | Máscara por defecto | Rango CIDR |
|-------|------------------------------|--------------------:|------------|
| A | 10.0.0.0 — 10.255.255.255 | 255.0.0.0 | 10.0.0.0/8 |
| B | 172.16.0.0 — 172.31.255.255 | 255.255.0.0 | 172.16.0.0/12 |
| C | 192.168.0.0 — 192.168.255.255 | 255.255.255.0 | 192.168.0.0/16 |

> **Dato práctico:** La mayoría de las redes domésticas en España usan el rango 192.168.1.0/24 o 192.168.0.0/24.

#### Direcciones especiales

| Dirección | Propósito |
|-----------|-----------|
| **127.0.0.0/8** (Loopback) | Dirección de prueba local. `127.0.0.1` = "yo mismo". Se usa para comprobar que la pila TCP/IP funciona correctamente. |
| **169.254.0.0/16** (Link-Local / APIPA) | Dirección que se asigna automáticamente cuando un dispositivo no puede obtener IP por DHCP. Indica un problema de red. |
| **0.0.0.0** | Ruta por defecto o "cualquier red". |
| **255.255.255.255** | Broadcast limitado (todos en la red local). |

#### Clases de direcciones IPv4 (clasificación histórica)

Históricamente, las direcciones IPv4 se dividieron en clases. Aunque hoy se usa el sistema CIDR (sin clases), es importante conocerlas:

| Clase | Primer octeto | Rango | Máscara por defecto | Uso |
|-------|--------------|-------|--------------------:|-----|
| **A** | 1-126 | 1.0.0.0 — 126.255.255.255 | /8 (255.0.0.0) | Grandes organizaciones |
| **B** | 128-191 | 128.0.0.0 — 191.255.255.255 | /16 (255.255.0.0) | Organizaciones medianas |
| **C** | 192-223 | 192.0.0.0 — 223.255.255.255 | /24 (255.255.255.0) | Redes pequeñas |
| **D** | 224-239 | 224.0.0.0 — 239.255.255.255 | — | Multicast |
| **E** | 240-255 | 240.0.0.0 — 255.255.255.255 | — | Experimental/Reservado |

> **Nota:** La dirección 127.x.x.x queda excluida de la Clase A porque está reservada para loopback.

---

### 9.3 Segmentación de Redes

#### ¿Por qué segmentar una red?

**Segmentar** una red significa dividir una red grande en subredes más pequeñas. Las razones principales son:

1. **Reducir el tráfico de broadcast:** En una red grande, los broadcasts llegan a TODOS los dispositivos. Si hay 1.000 dispositivos en una sola red, cada broadcast lo recibirán los 1.000. Al segmentar, cada subred tiene sus propios broadcasts, reduciendo el tráfico innecesario.

2. **Mejorar la seguridad:** Se pueden aplicar políticas de seguridad diferentes a cada subred (por ejemplo, separar la red de empleados de la red de invitados).

3. **Mejorar el rendimiento:** Menos dispositivos por subred = menos tráfico = mejor rendimiento.

4. **Facilitar la gestión:** Es más fácil administrar redes pequeñas y bien organizadas.

**Analogía:** Una red sin segmentar es como un edificio enorme con una sola sala abierta donde trabajan 1.000 personas. Cada vez que alguien grita (broadcast), lo oyen todos. Si divides el edificio en departamentos separados (subredes), cada grito solo se oye en su departamento.

#### Subnetting (Creación de subredes)

El **subnetting** es la técnica de dividir una red IP en subredes más pequeñas "tomando prestados" bits de la porción de host para crear más redes, pero con menos hosts por red.

**Ejemplo simplificado:**

Red original: `192.168.1.0/24` → 1 red con 254 hosts.

Si cambiamos la máscara a `/25` (tomamos 1 bit de host para red):
- Subred 1: `192.168.1.0/25` → Hosts de .1 a .126 (126 hosts)
- Subred 2: `192.168.1.128/25` → Hosts de .129 a .254 (126 hosts)

Si cambiamos la máscara a `/26` (tomamos 2 bits de host para red):
- Subred 1: `192.168.1.0/26` → Hosts de .1 a .62 (62 hosts)
- Subred 2: `192.168.1.64/26` → Hosts de .65 a .126 (62 hosts)
- Subred 3: `192.168.1.128/26` → Hosts de .129 a .190 (62 hosts)
- Subred 4: `192.168.1.192/26` → Hosts de .193 a .254 (62 hosts)

```
  Red original /24 (254 hosts):
  |=============================================|

  Dividida en 2 subredes /25 (126 hosts cada una):
  |======================|======================|
       192.168.1.0/25        192.168.1.128/25

  Dividida en 4 subredes /26 (62 hosts cada una):
  |===========|===========|===========|===========|
   .0/26       .64/26      .128/26     .192/26
```

> **Nota:** El subnetting es un tema que se profundiza mucho más en cursos como CCNA. Aquí lo presentamos como concepto introductorio.

---

### 9.4 Resumen del Módulo 9

En este módulo hemos aprendido que:

- Existen tres tipos de comunicación IP: **unicast** (uno a uno), **broadcast** (uno a todos) y **multicast** (uno a un grupo).
- Las direcciones IPv4 pueden ser **públicas** (enrutables en Internet) o **privadas** (solo para uso local, definidas por el RFC 1918).
- Existen direcciones especiales como la **loopback** (127.0.0.1), la **link-local/APIPA** (169.254.x.x) y la de **broadcast limitado** (255.255.255.255).
- La **segmentación de redes** (subnetting) divide redes grandes en subredes más pequeñas para mejorar el rendimiento, la seguridad y la gestión.
- Al hacer subnetting, se "toman prestados" bits de la porción de host para crear más subredes con menos hosts cada una.

> *IPv4 ha sido el pilar de Internet durante décadas, pero tiene un problema grave: se están agotando las direcciones. En el siguiente módulo veremos cómo IPv6 viene al rescate.*

---

## Módulo 10: Formatos y Reglas de Direccionamiento IPv6

### 10.0 Introducción

> *IPv4, con sus 32 bits, permite aproximadamente 4.300 millones de direcciones. Puede parecer mucho, pero con más de 8.000 millones de personas en el planeta y miles de millones de dispositivos conectados (móviles, ordenadores, cámaras, termostatos, coches, relojes...), las direcciones IPv4 se han agotado. IPv6 llega con una solución contundente: ¡340 sextillones de direcciones!*

---

### 10.1 Problemas de IPv4

#### El agotamiento de direcciones

El problema más grave de IPv4 es el **agotamiento de direcciones**. Con solo 2³² = 4.294.967.296 direcciones posibles, y con la explosión de dispositivos conectados (el **Internet de las Cosas - IoT** ha multiplicado exponencialmente la demanda), simplemente no hay suficientes direcciones IPv4 para todos.

**Analogía:** Imagina una ciudad donde los números de teléfono solo tienen 4 dígitos (0000-9999). Con una población pequeña, basta. Pero si la ciudad crece hasta tener 100.000 habitantes, muchos se quedarían sin número. Eso es lo que le ha pasado a IPv4.

#### Soluciones temporales que se aplicaron a IPv4

Para alargar la vida de IPv4 se implementaron varias soluciones parciales:

- **NAT (Network Address Translation):** Permite que múltiples dispositivos de una red privada compartan una única dirección IP pública. Lo veremos en detalle en el Módulo 12.
- **Direcciones privadas (RFC 1918):** Permiten reutilizar los mismos rangos de IPs en redes internas (ya visto en el Módulo 9).
- **CIDR (Classless Inter-Domain Routing):** Permite asignar bloques de direcciones de tamaño flexible, evitando el desperdicio del sistema de clases.

Estas soluciones han sido efectivas, pero son parches. La solución definitiva es **IPv6**.

#### Otras limitaciones de IPv4

Además del agotamiento de direcciones, IPv4 tiene otras carencias que IPv6 aborda:
- Seguridad opcional (IPsec es opcional en IPv4, obligatorio en IPv6).
- Configuración automática limitada (DHCP es necesario).
- Cabeceras complejas que ralentizan el procesamiento en los enrutadores.

---

### 10.2 Direccionamiento IPv6

#### Características principales de IPv6

- **Longitud:** **128 bits** (frente a los 32 de IPv4).
- **Número de direcciones:** 2¹²⁸ ≈ 3,4 × 10³⁸ (340 sextillones). Suficiente para asignar miles de millones de direcciones a cada grano de arena de la Tierra.
- **Formato:** Se escribe en **hexadecimal**, dividido en 8 grupos de 4 dígitos hexadecimales, separados por dos puntos `:`.

**Ejemplo de dirección IPv6 completa:**

```
  2001:0DB8:0000:0000:0000:0000:0000:0001
  |    |    |    |    |    |    |    |
  Grupo1 Grupo2 ...                  Grupo8
  (16 bits cada grupo = 8 × 16 = 128 bits)
```

#### Reglas de simplificación de IPv6

Dado que las direcciones IPv6 son muy largas, existen dos reglas para abreviarlas:

**Regla 1 - Omitir los ceros iniciales de cada grupo:**

```
  Completa:    2001:0DB8:0000:0000:0000:0000:0000:0001
  Simplificada: 2001:DB8:0:0:0:0:0:1
```

Se elimina el "0" inicial en cada grupo: `0DB8` → `DB8`, `0000` → `0`, `0001` → `1`.

**Regla 2 - Sustituir grupos consecutivos de ceros por `::`**

```
  Simplificada: 2001:DB8:0:0:0:0:0:1
  Aún más corta: 2001:DB8::1
```

> **¡Importante!** La doble dos puntos `::` solo se puede usar UNA VEZ en una dirección. Si se usara dos veces, sería imposible saber cuántos grupos de ceros representa cada una.

**Más ejemplos de simplificación:**

| Dirección completa | Simplificada |
|--------------------|-------------|
| `2001:0DB8:0000:0000:0000:0000:0000:0001` | `2001:DB8::1` |
| `FE80:0000:0000:0000:020C:29FF:FE9B:1234` | `FE80::20C:29FF:FE9B:1234` |
| `FF02:0000:0000:0000:0000:0000:0000:0001` | `FF02::1` |
| `0000:0000:0000:0000:0000:0000:0000:0001` | `::1` (loopback IPv6) |
| `0000:0000:0000:0000:0000:0000:0000:0000` | `::` (dirección sin especificar) |

#### Tipos de direcciones IPv6

| Tipo | Descripción | Equivalente IPv4 | Prefijo |
|------|-------------|-------------------|---------|
| **Unicast Global (GUA)** | Equivalente a una IP pública. Enrutable en Internet. | IP pública | `2000::/3` (empieza por 2 o 3) |
| **Link-Local** | Se asigna automáticamente a cada interfaz. Solo válida en el enlace local (LAN). | 169.254.x.x (APIPA) | `FE80::/10` |
| **Unique Local** | Equivalente a las IPs privadas. No enrutable en Internet. | 10.x.x.x, 172.16.x.x, 192.168.x.x | `FC00::/7` |
| **Multicast** | Envío a un grupo de dispositivos. | 224.0.0.0/4 | `FF00::/8` |
| **Loopback** | "Yo mismo" para pruebas. | 127.0.0.1 | `::1` |
| **Sin especificar** | Ausencia de dirección. | 0.0.0.0 | `::` |

> **Nota importante:** En IPv6 **no existe el broadcast**. Se usa multicast y una dirección especial llamada "all-nodes multicast" (`FF02::1`) para el mismo efecto.

#### Estructura de una dirección IPv6 Global Unicast

```
  |<--- 48 bits --->|<- 16 bits ->|<-------- 64 bits -------->|
  | Prefijo de      | ID de       | ID de Interfaz            |
  | enrutamiento    | subred      | (generado a partir de MAC |
  | global          |             |  o aleatoriamente)        |
  
  Ejemplo: 2001:0DB8:ACAD : 0001 : 020C:29FF:FE9B:1234
           |-- Pref. enrut.--|  Sub  |-- ID de Interfaz --|
```

- **Prefijo de enrutamiento global (48 bits):** Asignado por el ISP. Identifica la organización.
- **ID de subred (16 bits):** Permite crear hasta 65.536 subredes dentro de la organización.
- **ID de interfaz (64 bits):** Identifica la interfaz de red del dispositivo. Puede generarse a partir de la dirección MAC (método **EUI-64**) o de forma aleatoria.

---

### 10.3 Resumen del Módulo 10

En este módulo hemos aprendido que:

- IPv4 tiene un grave problema de **agotamiento de direcciones** debido a su limitación de 32 bits (4.300 millones de IPs).
- **IPv6** usa 128 bits, proporcionando un espacio de direccionamiento prácticamente infinito (340 sextillones).
- Las direcciones IPv6 se escriben en **hexadecimal** con 8 grupos de 4 dígitos separados por dos puntos.
- Existen dos **reglas de simplificación**: omitir ceros iniciales y usar `::` para grupos consecutivos de ceros (solo una vez por dirección).
- Los tipos principales de direcciones IPv6 son: **Global Unicast** (públicas), **Link-Local** (enlace local), **Unique Local** (privadas), **Multicast** y **Loopback (::1)**.
- IPv6 **no tiene broadcast**; usa multicast en su lugar.

> *Con IPv6 resuelto el problema de direccionamiento, necesitamos una forma eficiente de asignar esas direcciones a los dispositivos. Eso es exactamente lo que hace DHCP, tema del siguiente módulo.*

---

## Módulo 11: Direccionamiento Dinámico con DHCP

### 11.0 Introducción

> *Imagina que cada vez que conectas un nuevo dispositivo a la red (tu móvil, el portátil de un invitado, una bombilla inteligente), tuvieras que configurar manualmente la dirección IP, la máscara de subred, la puerta de enlace y el servidor DNS. Sería un trabajo tedioso y propenso a errores. Por suerte, existe DHCP, un protocolo que automatiza todo este proceso.*

---

### 11.1 Direccionamiento Estático y Dinámico

#### Direccionamiento estático

El **direccionamiento estático** consiste en configurar manualmente la dirección IP y los parámetros de red en cada dispositivo.

**Ventajas:**
- Control total sobre qué IP tiene cada dispositivo.
- Necesario para ciertos dispositivos como servidores, enrutadores e impresoras de red (que necesitan siempre la misma IP).

**Inconvenientes:**
- Consume mucho tiempo en redes grandes.
- Propenso a errores humanos (direcciones duplicadas, errores de escritura).
- Difícil de gestionar si los dispositivos cambian frecuentemente (portátiles, móviles, invitados).

#### Direccionamiento dinámico

El **direccionamiento dinámico** utiliza un protocolo para asignar automáticamente las direcciones IP y la configuración de red a los dispositivos. El protocolo más utilizado para esto es **DHCP** (Dynamic Host Configuration Protocol).

**Analogía:** El direccionamiento estático es como reservar un asiento numerado en un cine: tú eliges exactamente dónde sentarte. El direccionamiento dinámico es como el acomodador del cine (el servidor DHCP) que te asigna un asiento libre cuando llegas, sin que tú tengas que preocuparte.

---

### 11.2 Configuración de DHCPv4

#### ¿Cómo funciona DHCP?

El proceso de asignación de una dirección IP mediante **DHCPv4** sigue cuatro pasos, conocidos como **DORA**:

```
  Cliente                                     Servidor DHCP
     |                                             |
     |  1. DHCP DISCOVER (Broadcast)               |
     |  "¡Hola! ¿Hay algún servidor DHCP por ahí?" |
     |-------------------------------------------->|
     |                                             |
     |  2. DHCP OFFER                              |
     |  "Sí, te puedo ofrecer la IP 192.168.1.50" |
     |<--------------------------------------------|
     |                                             |
     |  3. DHCP REQUEST (Broadcast)                |
     |  "¡Acepto esa IP, por favor!"               |
     |-------------------------------------------->|
     |                                             |
     |  4. DHCP ACK                                |
     |  "Perfecto, la IP 192.168.1.50 es tuya     |
     |   durante las próximas 24 horas."           |
     |<--------------------------------------------|
     |                                             |
```

Detalle de cada paso:

1. **DHCP Discover (Descubrimiento):** El cliente envía un mensaje de broadcast (255.255.255.255) buscando un servidor DHCP en la red. El cliente aún no tiene IP, así que usa la dirección 0.0.0.0 como origen.

2. **DHCP Offer (Oferta):** El servidor DHCP responde ofreciendo una dirección IP disponible, junto con la máscara de subred, la puerta de enlace y el servidor DNS.

3. **DHCP Request (Solicitud):** El cliente envía un broadcast aceptando la oferta. Se envía por broadcast porque puede haber más de un servidor DHCP en la red y así todos los servidores saben qué oferta se aceptó.

4. **DHCP ACK (Confirmación):** El servidor confirma la asignación. A partir de este momento, el cliente tiene una dirección IP válida y puede comunicarse en la red.

#### Información que proporciona DHCP

DHCP no solo asigna una dirección IP; proporciona toda la configuración necesaria:

| Parámetro | Descripción | Ejemplo |
|-----------|-------------|---------|
| **Dirección IP** | La IP asignada al dispositivo | 192.168.1.50 |
| **Máscara de subred** | Define la red | 255.255.255.0 |
| **Puerta de enlace predeterminada** | IP del enrutador | 192.168.1.1 |
| **Servidor DNS** | Para resolver nombres de dominio | 8.8.8.8 |
| **Tiempo de concesión (lease time)** | Cuánto tiempo es válida la IP | 24 horas |

#### Tiempo de concesión (Lease Time)

La dirección IP asignada por DHCP no es permanente: tiene un **tiempo de concesión** (lease time). Cuando el tiempo expira, el dispositivo debe renovar la concesión o perderá la dirección IP.

**Analogía:** Es como un aparcamiento con parquímetro. El servidor DHCP te "alquila" una plaza de aparcamiento (IP) por un tiempo determinado. Cuando se acerca la hora de expiración, puedes renovar el ticket. Si no renuevas, la plaza queda libre para otro coche.

Normalmente, el dispositivo intenta renovar la concesión cuando ha transcurrido el 50% del tiempo de lease.

#### DHCPv6

Para redes IPv6, existe **DHCPv6**, que funciona de manera similar pero con algunas diferencias:
- IPv6 también soporta la **autoconfiguración sin estado (SLAAC - Stateless Address Autoconfiguration)**, donde los dispositivos pueden generar su propia dirección IPv6 sin necesidad de un servidor DHCP, usando la información del enrutador.
- DHCPv6 se usa cuando se necesitan parámetros adicionales (como la dirección del servidor DNS) que SLAAC no proporciona.

---

### 11.3 Resumen del Módulo 11

En este módulo hemos aprendido que:

- El **direccionamiento estático** requiere configurar manualmente cada dispositivo. Es útil para servidores y enrutadores pero poco práctico para redes grandes.
- El **direccionamiento dinámico con DHCP** automatiza la asignación de IP y parámetros de red.
- El proceso DHCP sigue cuatro pasos: **DORA** (Discover, Offer, Request, ACK).
- DHCP proporciona: dirección IP, máscara, puerta de enlace, DNS y tiempo de concesión.
- Las concesiones DHCP tienen un **tiempo limitado** (lease time) y deben renovarse periódicamente.
- En IPv6, **SLAAC** permite la autoconfiguración de direcciones sin servidor DHCP; **DHCPv6** se usa para información adicional.

> *Ya sabes cómo los dispositivos obtienen su dirección IP automáticamente. Pero, ¿cómo salen los datos de tu red local hacia Internet? En el siguiente módulo veremos las pasarelas y NAT.*

---

## Módulo 12: Pasarelas a Otras Redes

### 12.0 Introducción

> *Tu red doméstica es como una isla. Los dispositivos de tu red pueden comunicarse entre sí, pero para llegar a Internet necesitan un "puente" que los conecte con el resto del mundo. Ese puente es la puerta de enlace (gateway), y el truco de magia que permite que todos tus dispositivos con IPs privadas se comuniquen con Internet usando una sola IP pública se llama NAT.*

---

### 12.1 Límites de la Red

#### ¿Qué es una puerta de enlace?

La **puerta de enlace predeterminada** (default gateway) es el enrutador que un dispositivo utiliza para enviar tráfico a redes que no son la suya. Como vimos en el Módulo 8, es la "salida" de tu red local.

**Analogía:** Si tu red local es tu barrio, la puerta de enlace es la rotonda que conecta tu barrio con la carretera principal. Todo el tráfico que salga del barrio debe pasar por esa rotonda.

#### ¿Cómo decide un dispositivo si el destino está en su red o en otra?

Cuando un dispositivo quiere enviar datos, realiza una operación lógica **AND** entre su propia dirección IP y su máscara de subred, y entre la dirección IP de destino y su propia máscara. Si los resultados coinciden, el destino está en la misma red. Si no coinciden, el destino está en otra red y los datos se envían a la puerta de enlace.

```
  Ejemplo: Mi IP = 192.168.1.10/24, Destino = 192.168.1.50
  
  Mi IP AND Máscara:     192.168.1.10 AND 255.255.255.0 = 192.168.1.0
  Destino AND Máscara:   192.168.1.50 AND 255.255.255.0 = 192.168.1.0
  
  192.168.1.0 = 192.168.1.0 → ¡MISMA RED! → Envío directo.
  
  ---
  
  Ejemplo: Mi IP = 192.168.1.10/24, Destino = 8.8.8.8
  
  Mi IP AND Máscara:     192.168.1.10 AND 255.255.255.0 = 192.168.1.0
  Destino AND Máscara:   8.8.8.8      AND 255.255.255.0 = 8.8.8.0
  
  192.168.1.0 ≠ 8.8.8.0 → ¡RED DIFERENTE! → Envío al gateway (192.168.1.1).
```

#### El enrutador como frontera de red

El enrutador tiene al menos dos interfaces de red:
- Una interfaz conectada a tu **red local (LAN)** con una dirección IP privada (p.ej., 192.168.1.1).
- Una interfaz conectada a la **red del ISP (WAN)** con una dirección IP pública asignada por el ISP.

```
  RED LOCAL (LAN)                         INTERNET (WAN)
  192.168.1.0/24                          IP Pública del ISP
                                          
  [PC: 192.168.1.10]                      [Servidor web: 93.184.216.34]
  [Móvil: 192.168.1.20]  ---[ROUTER]---   
  [Tablet: 192.168.1.30]    LAN | WAN    
                          .1.1  | IP Pública
```

---

### 12.2 Traducción de Direcciones de Red (NAT)

#### ¿Qué es NAT?

**NAT** (Network Address Translation, o Traducción de Direcciones de Red) es una técnica implementada en los enrutadores que traduce las direcciones IP privadas de los dispositivos de tu red local a una dirección IP pública para comunicarse con Internet, y viceversa.

**Analogía:** NAT funciona como la recepción de un hotel. Dentro del hotel, las habitaciones tienen números internos (101, 102, 103 = IPs privadas). Pero cuando un huésped quiere enviar una carta, la recepción pone la dirección del hotel (IP pública) como remitente. Cuando llega la respuesta al hotel, la recepción mira a qué habitación va y la redirige.

#### ¿Por qué es necesario NAT?

- Las direcciones IP privadas (192.168.x.x, 10.x.x.x, 172.16.x.x) **no son enrutables en Internet**. Los routers de Internet descartan paquetes con direcciones privadas como origen.
- NAT permite que decenas o cientos de dispositivos con IPs privadas compartan **una sola dirección IP pública**.
- Esto ha sido clave para **retrasar el agotamiento de IPv4** (como mencionamos en el Módulo 10).

#### Tipos de NAT

**NAT Estático:** Asocia una IP privada con una IP pública de forma fija y permanente. Se usa para servidores que necesitan ser accesibles desde Internet.

**NAT Dinámico:** Asigna una IP pública de un pool (grupo) de IPs disponibles cuando un dispositivo interno inicia una comunicación.

**PAT (Port Address Translation) / NAT con sobrecarga:** Es el tipo más común, especialmente en redes domésticas. **Múltiples dispositivos internos comparten una sola IP pública**, diferenciándose por los **números de puerto**.

```
  PAT en acción:
  
  Dispositivo interno          Traducción PAT          Internet
  192.168.1.10:50001  →  85.23.44.100:60001  →  [Servidor web]
  192.168.1.20:50002  →  85.23.44.100:60002  →  [Servidor web]
  192.168.1.30:50003  →  85.23.44.100:60003  →  [Servidor web]
  
  Todos salen con la MISMA IP pública (85.23.44.100)
  pero con DIFERENTES puertos (60001, 60002, 60003)
```

**Analogía de PAT:** Es como si todos los empleados de una empresa enviaran sus cartas con la misma dirección postal de la empresa, pero cada uno añadiera un número de referencia diferente. Cuando llegan las respuestas a la empresa, se mira el número de referencia para saber a qué empleado va cada carta.

---

### 12.3 Resumen del Módulo 12

En este módulo hemos aprendido que:

- La **puerta de enlace predeterminada** es el enrutador que conecta tu red local con otras redes (incluido Internet).
- Un dispositivo compara la dirección de red del destino con la suya propia. Si son iguales, envía directamente. Si son diferentes, envía al **gateway**.
- **NAT** traduce direcciones IP privadas a públicas para permitir la comunicación con Internet.
- **PAT** (NAT con sobrecarga) es el tipo más común y permite que múltiples dispositivos compartan una sola IP pública usando diferentes números de puerto.
- NAT ha sido fundamental para **mitigar el agotamiento de direcciones IPv4**.

> *Ya sabes cómo los datos salen de tu red hacia Internet. Pero hay un detalle que hemos dejado pendiente: ¿cómo sabe tu ordenador la dirección MAC del enrutador para poder enviarle la trama Ethernet? Para eso existe ARP, el tema del siguiente módulo.*

---

## Módulo 13: El Proceso ARP

### 13.0 Introducción

> *Recuerda lo que aprendimos en el Módulo 7: para enviar datos dentro de una red local, se necesita la dirección MAC del destino. Y en el Módulo 8, que para comunicarse entre redes diferentes se necesita la dirección IP. Pero, ¿cómo se conectan estos dos mundos? ¿Cómo averigua tu ordenador la dirección MAC de otro dispositivo si solo conoce su dirección IP? La respuesta es ARP.*

---

### 13.1 MAC e IP

#### La necesidad de dos tipos de direcciones

En una comunicación de red, se necesitan **ambas direcciones** simultáneamente:

- **Dirección IP (Capa 3):** Para identificar el dispositivo y la red de destino a nivel global. Es lo que permite al enrutador decidir por dónde enviar el paquete.
- **Dirección MAC (Capa 2):** Para entregar la trama al dispositivo correcto dentro de la red local. Es lo que usa el switch para enviar los datos al puerto correcto.

**Analogía:** Imagina que envías un paquete de Madrid a una oficina en Barcelona. La dirección postal completa (calle, número, ciudad) es como la dirección IP: indica el destino final. Pero dentro del edificio de oficinas de Barcelona, el conserje necesita saber en qué despacho dejarlo; el nombre de la persona en el buzón es como la dirección MAC.

#### ¿Qué es ARP?

**ARP** (Address Resolution Protocol, o Protocolo de Resolución de Direcciones) es el protocolo que permite a un dispositivo averiguar la **dirección MAC** de otro dispositivo **conociendo solo su dirección IP**, dentro de la misma red local.

#### ¿Cómo funciona ARP?

El proceso ARP es simple pero fundamental:

1. **ARP Request (Solicitud ARP):** El dispositivo emisor envía un mensaje de **broadcast** a toda la red local preguntando: "¿Quién tiene la dirección IP 192.168.1.1? Por favor, respóndeme con tu dirección MAC."

2. **ARP Reply (Respuesta ARP):** El dispositivo que tiene esa IP responde con un mensaje **unicast** directamente al emisor: "Yo tengo la IP 192.168.1.1, y mi dirección MAC es AA:BB:CC:DD:EE:FF."

```
  1. ARP REQUEST (Broadcast - llega a TODOS):
  
  [PC-A: 192.168.1.10]                [Router: 192.168.1.1]
  MAC: 11:11:11:11:11:11              MAC: AA:BB:CC:DD:EE:FF
         |                                    |
         |  "¿Quién tiene 192.168.1.1?        |
         |   Soy 192.168.1.10 (11:11:...)     |
         |---------BROADCAST----------------->|
         |                  (también llega a todos los demás)
  
  
  2. ARP REPLY (Unicast - solo al emisor):
  
  [PC-A: 192.168.1.10]                [Router: 192.168.1.1]
         |                                    |
         |  "Yo soy 192.168.1.1 y             |
         |   mi MAC es AA:BB:CC:DD:EE:FF"     |
         |<-----------UNICAST-----------------|
```

#### La caché ARP

Para no tener que enviar solicitudes ARP continuamente, cada dispositivo mantiene una **caché ARP** (o tabla ARP): una tabla temporal que almacena las asociaciones IP → MAC ya aprendidas.

```
  Tabla ARP de PC-A:
  +------------------+-------------------+--------+
  | Dirección IP     | Dirección MAC     | Tipo   |
  +------------------+-------------------+--------+
  | 192.168.1.1      | AA:BB:CC:DD:EE:FF | Dinám. |
  | 192.168.1.20     | 22:22:22:22:22:22 | Dinám. |
  +------------------+-------------------+--------+
```

En Windows, puedes ver la tabla ARP con el comando: `arp -a`  
En Linux/macOS: `arp -n` o `ip neigh`

Las entradas de la caché ARP tienen un **tiempo de expiración** (normalmente unos minutos). Si no se usan, se eliminan automáticamente.

---

### 13.2 Contención de Difusiones

#### Dominios de broadcast

Un **dominio de broadcast** es el conjunto de dispositivos que reciben una trama de broadcast enviada por cualquiera de ellos. En una red plana (sin enrutadores), todos los dispositivos pertenecen al mismo dominio de broadcast.

**El problema:** Cada solicitud ARP es un broadcast. A medida que la red crece, el número de broadcasts aumenta, consumiendo ancho de banda y recursos de procesamiento de todos los dispositivos.

**Analogía:** Es como una clase donde cada vez que un alumno tiene una pregunta, la grita en voz alta para que todos la oigan. Con 5 alumnos no es problema, pero con 500, el ruido se vuelve insoportable.

#### ¿Cómo se contienen los broadcasts?

**Los enrutadores NO reenvían broadcasts.** Cada interfaz de un enrutador define un **dominio de broadcast diferente**. Esto significa que los broadcasts de una red local NO afectan a las demás.

```
  Dominio de           Dominio de
  Broadcast 1          Broadcast 2
  +------------+       +------------+
  | [PC-A]     |       | [PC-C]     |
  | [PC-B]     |       | [PC-D]     |
  | [Switch 1] |       | [Switch 2] |
  +------+-----+       +-----+------+
         |                    |
    -----+-------[ROUTER]----+-----
         Interfaz 1    Interfaz 2
         192.168.1.1   192.168.2.1
```

En este esquema, un broadcast de PC-A llega a PC-B y Switch 1, pero **NO cruza el enrutador** y por tanto NO llega a PC-C ni PC-D.

#### VLANs como herramienta de segmentación

Aunque se profundiza en cursos más avanzados, merece la pena mencionar que los switches gestionados pueden crear **VLANs** (Virtual LANs) para segmentar el tráfico y crear dominios de broadcast separados sin necesitar múltiples enrutadores físicos. Es como crear "redes virtuales" dentro de un mismo switch.

---

### 13.3 Resumen del Módulo 13

En este módulo hemos aprendido que:

- Para enviar datos en una red local se necesitan tanto la **dirección IP** (capa 3) como la **dirección MAC** (capa 2).
- **ARP** permite averiguar la dirección MAC de un dispositivo conociendo su dirección IP, mediante un proceso de solicitud (broadcast) y respuesta (unicast).
- Los dispositivos mantienen una **caché ARP** con las asociaciones IP→MAC aprendidas para evitar solicitudes repetitivas.
- Un **dominio de broadcast** abarca todos los dispositivos que reciben los mismos broadcasts.
- Los **enrutadores** definen los límites de los dominios de broadcast: los broadcasts NO cruzan los enrutadores.
- Las **VLANs** permiten segmentar dominios de broadcast dentro de un mismo switch.

> *Ahora comprendes cómo los datos encuentran su camino tanto dentro de una red local (MAC + ARP) como hacia otras redes (IP + Gateway). En el siguiente módulo veremos en profundidad cómo los enrutadores deciden el mejor camino para enviar los paquetes.*

---

## Módulo 14: Enrutamiento entre Redes

### 14.0 Introducción

> *Hasta ahora hemos visto cómo los datos viajan dentro de una red local (gracias a los switches y las direcciones MAC) y cómo salen hacia otras redes (gracias a la puerta de enlace). Pero, ¿qué pasa con los datos una vez que llegan al enrutador? ¿Cómo decide el enrutador por dónde enviarlos? Bienvenido al fascinante mundo del enrutamiento.*

---

### 14.1 La Necesidad del Enrutamiento

#### ¿Qué es el enrutamiento?

El **enrutamiento** (routing) es el proceso por el cual un enrutador (router) determina el **mejor camino** para enviar un paquete desde la red de origen hasta la red de destino.

**Analogía:** El enrutador es como el GPS de tu coche. Cuando introduces un destino (dirección IP de destino), el GPS (enrutador) consulta su mapa (tabla de enrutamiento) y te indica por qué salida de la rotonda debes ir para llegar al destino de la forma más eficiente.

#### ¿Por qué es necesario?

- Los paquetes de datos deben viajar a través de múltiples redes intermedias para llegar a su destino final.
- Cada enrutador en el camino toma una decisión independiente sobre el siguiente "salto" (next hop) del paquete.
- Un paquete puede atravesar decenas de enrutadores antes de llegar a su destino.

```
  [PC en Madrid] → [Router ISP Madrid] → [Router troncal España]
       → [Router troncal Europeo] → [Router ISP EEUU]
       → [Router ISP California] → [Servidor Google]
```

Cada flecha (→) representa un "salto" (hop). En cada salto, un enrutador consulta su tabla de enrutamiento y decide por qué interfaz reenviar el paquete.

---

### 14.2 La Tabla de Enrutamiento

#### ¿Qué es una tabla de enrutamiento?

La **tabla de enrutamiento** es una base de datos almacenada en la memoria del enrutador que contiene información sobre las redes conocidas y cómo alcanzarlas.

Cada entrada de la tabla contiene al menos:
- **Red de destino:** La dirección de red y su máscara (p.ej., 192.168.2.0/24).
- **Siguiente salto (Next Hop):** La dirección IP del siguiente enrutador al que enviar el paquete.
- **Interfaz de salida:** El puerto del enrutador por el que debe salir el paquete.
- **Métrica / Coste:** Un valor que indica la "distancia" o "coste" de esa ruta (si hay varias rutas al mismo destino, se elige la de menor coste).

**Ejemplo simplificado de tabla de enrutamiento:**

```
  +-------------------+------------------+-------------+---------+
  | Red de Destino    | Siguiente Salto  | Interfaz    | Métrica |
  +-------------------+------------------+-------------+---------+
  | 192.168.1.0/24    | Conectada direct.| G0/0        | 0       |
  | 192.168.2.0/24    | Conectada direct.| G0/1        | 0       |
  | 10.0.0.0/8        | 192.168.2.254    | G0/1        | 1       |
  | 0.0.0.0/0         | 192.168.1.1      | G0/0        | 1       |
  +-------------------+------------------+-------------+---------+
```

- **Redes directamente conectadas:** Aparecen automáticamente cuando se configuran las interfaces del enrutador.
- **Ruta por defecto (0.0.0.0/0):** Es la "ruta comodín". Si el enrutador no encuentra una ruta más específica para el destino, usa esta ruta. Es como decir: "si no sé cómo llegar, envío el paquete por aquí".

#### ¿Cómo se llena la tabla de enrutamiento?

Existen tres formas:

1. **Redes directamente conectadas:** Se añaden automáticamente cuando se activa una interfaz del enrutador con una dirección IP configurada.

2. **Rutas estáticas:** Configuradas manualmente por el administrador de red. Útiles en redes pequeñas o para rutas específicas.
   ```
   Ejemplo (sintaxis Cisco):
   ip route 10.0.0.0 255.0.0.0 192.168.2.254
   ```

3. **Rutas dinámicas:** Aprendidas automáticamente mediante **protocolos de enrutamiento** que permiten a los enrutadores intercambiar información sobre las redes que conocen. Ejemplos de protocolos de enrutamiento:
   - **RIP** (Routing Information Protocol): Sencillo, para redes pequeñas.
   - **OSPF** (Open Shortest Path First): Avanzado, para redes medianas y grandes.
   - **EIGRP** (Enhanced Interior Gateway Routing Protocol): Protocolo propietario de Cisco.
   - **BGP** (Border Gateway Protocol): El protocolo que interconecta las redes de Internet a nivel global.

**Analogía:** Las rutas estáticas son como escribir las instrucciones de cómo llegar a sitios en un papel (se quedan fijas). Las rutas dinámicas son como usar un GPS que se actualiza en tiempo real con información del tráfico.

#### Proceso de decisión del enrutador

Cuando un enrutador recibe un paquete:

1. Examina la **dirección IP de destino** en la cabecera del paquete.
2. Busca en su **tabla de enrutamiento** la ruta más específica que coincida (la que tenga la máscara más larga, conocido como "longest prefix match").
3. Reenvía el paquete por la **interfaz de salida** correspondiente, hacia el **siguiente salto**.
4. Si no encuentra ninguna ruta (ni siquiera la ruta por defecto), **descarta el paquete** y envía un mensaje ICMP de "Destino inalcanzable" al origen.

---

### 14.3 Crear una LAN

#### Componentes necesarios para crear una LAN básica

Para montar una red LAN funcional que se conecte a Internet, necesitamos:

1. **Un switch** para conectar los dispositivos finales entre sí.
2. **Un enrutador** para conectar la LAN con otras redes (Internet).
3. **Cables Ethernet (UTP Cat 5e o superior)** para las conexiones físicas.
4. **Configuración IP** en cada dispositivo: dirección IP, máscara, puerta de enlace y DNS (manual o por DHCP).

#### Ejemplo de LAN básica

```
                              Internet
                                 |
                          [Router]
                          G0/0: 192.168.1.1/24
                                 |
                          [Switch]
                         /    |    \
                       /      |      \
                 [PC-A]    [PC-B]  [Impresora]
           192.168.1.10  .1.20    .1.30
           /24           /24      /24
           GW: .1.1      GW: .1.1 GW: .1.1
           DNS: 8.8.8.8  DNS: 8.8.8.8
```

#### Pasos para configurar la LAN:

1. **Conectar el hardware:** Cablear los PCs y la impresora al switch. Conectar el switch al enrutador.
2. **Configurar el enrutador:** Asignar la IP 192.168.1.1/24 a la interfaz LAN. Configurar la interfaz WAN según las indicaciones del ISP. Activar DHCP o configurar IPs estáticas.
3. **Configurar los dispositivos finales:** Si se usa DHCP, simplemente seleccionar "Obtener una dirección IP automáticamente". Si se usan IPs estáticas, configurar IP, máscara, gateway y DNS en cada dispositivo.
4. **Verificar la conectividad:** Usar el comando `ping` para verificar que los dispositivos se comunican entre sí y con Internet.

```
  Verificación paso a paso:
  
  1. ping 127.0.0.1       → Verifica que la pila TCP/IP funciona.
  2. ping 192.168.1.10     → Verifica la propia IP (prueba local).
  3. ping 192.168.1.1      → Verifica la conectividad con el gateway.
  4. ping 8.8.8.8          → Verifica la conectividad con Internet.
  5. ping www.google.es    → Verifica que DNS funciona correctamente.
```

> **Consejo:** Si el paso 4 funciona pero el paso 5 no, el problema está en la configuración DNS, no en la conectividad.

---

### 14.4 Resumen del Módulo 14

En este módulo hemos aprendido que:

- El **enrutamiento** es el proceso por el que un enrutador decide el mejor camino para reenviar paquetes entre redes.
- La **tabla de enrutamiento** contiene las redes conocidas, el siguiente salto y la interfaz de salida.
- Las rutas pueden ser **directamente conectadas**, **estáticas** (manuales) o **dinámicas** (aprendidas por protocolos como RIP, OSPF, BGP).
- El enrutador usa el criterio de **coincidencia de prefijo más largo** para elegir la mejor ruta.
- La **ruta por defecto (0.0.0.0/0)** se usa cuando no hay una ruta más específica.
- Para crear una LAN funcional se necesitan: switch, enrutador, cables y una configuración IP correcta en todos los dispositivos.

> *Ya entiendes cómo los datos viajan entre redes. Pero, ¿cómo se asegura la red de que los datos lleguen completos y en orden? Para eso necesitamos los protocolos de transporte: TCP y UDP.*

---

## Módulo 15: TCP y UDP

### 15.0 Introducción

> *Imagina que envías un puzle de 1.000 piezas a un amigo, pieza por pieza, por correo postal. ¿Cómo te aseguras de que lleguen todas las piezas y en el orden correcto? ¿O quizá no te importa si se pierde alguna pieza porque lo importante es la velocidad? Estas dos filosofías son las que representan TCP y UDP, los dos protocolos fundamentales de la capa de transporte.*

---

### 15.1 TCP y UDP

#### La Capa de Transporte

La **capa de transporte** (capa 4 del modelo OSI, capa 3 del modelo TCP/IP) es responsable de:
- La comunicación **extremo a extremo** entre aplicaciones en dispositivos diferentes.
- La **segmentación** de los datos de aplicación en unidades más pequeñas.
- El **control de flujo** y la **fiabilidad** de la comunicación (en TCP).
- La **multiplexación**, permitiendo que múltiples aplicaciones compartan la misma conexión de red simultáneamente mediante números de puerto.

Los dos protocolos principales de esta capa son **TCP** y **UDP**.

#### TCP (Transmission Control Protocol)

**TCP** es un protocolo de transporte **orientado a conexión** y **fiable**. Garantiza que todos los datos lleguen al destino, en el orden correcto y sin errores.

**Analogía:** TCP es como enviar una carta certificada con acuse de recibo. Tú envías la carta, el cartero se asegura de que llegue, y recibes una confirmación de que fue entregada. Si la carta se pierde, se reenvía.

**Características de TCP:**

- **Orientado a conexión:** Antes de enviar datos, se establece una conexión formal entre emisor y receptor mediante un proceso llamado **three-way handshake** (saludo en tres pasos).
- **Fiable:** Cada segmento recibido se confirma con un **acuse de recibo (ACK)**. Si no se recibe ACK, se retransmite.
- **Ordenado:** Los segmentos se numeran con **números de secuencia** para que el receptor pueda reensamblarlos en el orden correcto.
- **Control de flujo:** El receptor puede indicar al emisor que reduzca la velocidad de envío si no puede procesarlos tan rápido (**ventana deslizante / sliding window**).
- **Control de congestión:** TCP ajusta la velocidad de envío para evitar saturar la red.

**El Three-Way Handshake (Establecimiento de conexión TCP):**

```
  Cliente                              Servidor
     |                                    |
     |  1. SYN  (¿Puedo conectarme?)      |
     |----------------------------------->|
     |                                    |
     |  2. SYN-ACK  (Sí, adelante)       |
     |<-----------------------------------|
     |                                    |
     |  3. ACK  (¡Perfecto, conectados!) |
     |----------------------------------->|
     |                                    |
     |  ← Conexión establecida →          |
     |  ... Transferencia de datos ...    |
```

**Analogía del handshake:** Es como una llamada telefónica. Tú llamas (SYN), la otra persona descuelga y dice "¿Dígame?" (SYN-ACK), y tú respondes "Hola, soy Joselu" (ACK). Solo entonces empezáis a hablar.

#### UDP (User Datagram Protocol)

**UDP** es un protocolo de transporte **sin conexión** y **no fiable** (en el sentido técnico: no garantiza la entrega ni el orden).

**Analogía:** UDP es como enviar una postal. La echas al buzón y esperas que llegue, pero no recibes confirmación. Si se pierde, no te enteras. A cambio, es más rápido y sencillo que enviar una carta certificada.

**Características de UDP:**

- **Sin conexión:** No se establece ninguna conexión previa. Los datos se envían directamente.
- **No fiable:** No hay acuses de recibo, ni retransmisiones, ni control de orden.
- **Rápido y ligero:** Al no tener la sobrecarga de TCP (handshake, ACK, números de secuencia), UDP es mucho más eficiente para ciertos tipos de tráfico.
- **Sin control de flujo ni de congestión.**

#### ¿Cuándo usar TCP y cuándo UDP?

| Característica | TCP | UDP |
|---------------|-----|-----|
| Conexión | Orientado a conexión | Sin conexión |
| Fiabilidad | Sí (ACK, retransmisión) | No |
| Orden de entrega | Garantizado | No garantizado |
| Velocidad | Más lento | Más rápido |
| Sobrecarga (overhead) | Mayor | Menor |
| **Uso típico** | Web (HTTP/HTTPS), correo (SMTP), transferencia de archivos (FTP), SSH | Streaming de vídeo/audio, DNS (consultas rápidas), VoIP, juegos en línea, DHCP |

**Analogía resumida:**
- **TCP** = Envío certificado de un contrato legal (no puede faltar ni una página).
- **UDP** = Retransmisión en directo de un partido de fútbol (si se pierde un fotograma, no merece la pena retransmitirlo; es mejor seguir con el siguiente).

---

### 15.2 Números de Puerto

#### ¿Qué son los números de puerto?

Los **números de puerto** son identificadores numéricos (de 0 a 65.535) que permiten que múltiples aplicaciones en un mismo dispositivo utilicen la red simultáneamente. Cada aplicación o servicio escucha en un puerto específico.

**Analogía:** Si la dirección IP es la dirección de un edificio de oficinas, el número de puerto es el número de la oficina dentro del edificio. El cartero (la red) lleva el paquete al edificio correcto (IP) y luego lo entrega en la oficina correcta (puerto).

```
  Dirección completa de comunicación (Socket):
  
  IP de destino : Puerto de destino
  192.168.1.100 : 80
  
  Esto identifica: el servidor web en la IP 192.168.1.100
```

#### Rangos de puertos

| Rango | Nombre | Descripción |
|-------|--------|-------------|
| 0 - 1.023 | **Puertos bien conocidos (Well-Known Ports)** | Reservados para servicios estándar (HTTP, FTP, DNS, etc.). Asignados por IANA. |
| 1.024 - 49.151 | **Puertos registrados (Registered Ports)** | Usados por aplicaciones específicas (bases de datos, servidores de aplicaciones). |
| 49.152 - 65.535 | **Puertos dinámicos / privados (Ephemeral Ports)** | Asignados temporalmente por el sistema operativo al cliente que inicia una conexión. |

#### Puertos bien conocidos más importantes

| Puerto | Protocolo | Servicio | Descripción |
|--------|-----------|----------|-------------|
| 20 | TCP | **FTP datos** | Transferencia de archivos (canal de datos) |
| 21 | TCP | **FTP control** | Transferencia de archivos (canal de control) |
| 22 | TCP | **SSH** | Acceso remoto seguro (cifrado) |
| 23 | TCP | **Telnet** | Acceso remoto NO seguro (texto plano) |
| 25 | TCP | **SMTP** | Envío de correo electrónico |
| 53 | TCP/UDP | **DNS** | Resolución de nombres de dominio |
| 67/68 | UDP | **DHCP** | Asignación dinámica de IPs |
| 80 | TCP | **HTTP** | Navegación web (sin cifrar) |
| 110 | TCP | **POP3** | Recepción de correo electrónico |
| 143 | TCP | **IMAP** | Recepción de correo (con sincronización) |
| 443 | TCP | **HTTPS** | Navegación web segura (cifrada) |
| 3389 | TCP | **RDP** | Escritorio remoto de Windows |

#### La combinación IP + Puerto = Socket

Un **socket** es la combinación de una dirección IP y un número de puerto. Identifica de forma única una comunicación en la red.

```
  Ejemplo de comunicación web:
  
  Tu PC                                    Servidor Web
  192.168.1.10:52301  ←→  93.184.216.34:443
  (IP cliente:Puerto      (IP servidor:Puerto
   efímero)                bien conocido HTTPS)
```

El sistema operativo de tu PC elige un **puerto efímero** aleatorio (p.ej., 52301) como origen. El servidor web escucha en el puerto 443 (HTTPS). La combinación de IPs y puertos de origen y destino identifica de forma única esta conversación.

---

### 15.3 Resumen del Módulo 15

En este módulo hemos aprendido que:

- La capa de transporte proporciona comunicación extremo a extremo entre aplicaciones.
- **TCP** es orientado a conexión, fiable y ordenado. Usa un **three-way handshake** (SYN, SYN-ACK, ACK) para establecer la conexión. Ideal para web, correo y transferencia de ficheros.
- **UDP** es sin conexión, no fiable pero rápido. Ideal para streaming, DNS, VoIP y juegos en línea.
- Los **números de puerto** identifican aplicaciones específicas en un dispositivo: puertos bien conocidos (0-1023), registrados (1024-49151) y dinámicos (49152-65535).
- Un **socket** (IP:Puerto) identifica de forma única cada extremo de una comunicación.

> *Ya dominas los protocolos de transporte. Es hora de subir a la última capa: la capa de Aplicación, donde viven los servicios que usamos todos los días.*

---

## Módulo 16: Servicios de la Capa de Aplicación

### 16.0 Introducción

> *Todo lo que hemos aprendido hasta ahora (redes, IPs, MAC, switches, enrutadores, TCP, UDP, puertos...) existe para una sola razón: que las aplicaciones que usamos a diario (navegador web, correo, mensajería, transferencia de ficheros) funcionen correctamente. En este módulo exploraremos los servicios y protocolos de la capa de Aplicación.*

---

### 16.1 La Relación Cliente-Servidor

Como vimos en el Módulo 2, el modelo **cliente-servidor** es el paradigma dominante en los servicios de red:

- El **cliente** es la aplicación que solicita un servicio (p.ej., tu navegador Chrome).
- El **servidor** es la aplicación que proporciona el servicio (p.ej., el servidor web de Google).

En la capa de Aplicación, esta relación es fundamental. Cada servicio tiene su propio protocolo y sus propios puertos:

```
  CLIENTE                 PROTOCOLO              SERVIDOR
  Navegador web    ←--    HTTP/HTTPS    --→    Servidor web
  Cliente de correo ←--   SMTP/POP3/IMAP --→   Servidor de correo
  Cliente FTP       ←--   FTP           --→    Servidor FTP
  Terminal SSH      ←--   SSH           --→    Servidor SSH
```

El cliente siempre **inicia** la comunicación. El servidor está constantemente "escuchando" en un puerto específico, esperando peticiones de los clientes.

---

### 16.2 Servicios de Aplicación de Red

Los servicios de la capa de aplicación se pueden agrupar en varias categorías:

| Categoría | Servicio | Protocolo | Descripción |
|-----------|----------|-----------|-------------|
| Web | Navegación | HTTP / HTTPS | Acceso a páginas web |
| Nombres | Resolución DNS | DNS | Traduce nombres a IPs |
| Correo | Envío y recepción | SMTP / POP3 / IMAP | Correo electrónico |
| Ficheros | Transferencia | FTP / SFTP | Subir y descargar archivos |
| Acceso remoto | Terminal | SSH / Telnet | Administración remota |
| Configuración | Direccionamiento | DHCP | Asignación automática de IPs |
| Diagnóstico | Pruebas | ICMP (ping) | Verificación de conectividad |

Vamos a profundizar en los más importantes.

---

### 16.3 Sistema de Nombres de Dominio (DNS)

#### ¿Qué es DNS?

El **DNS** (Domain Name System, o Sistema de Nombres de Dominio) es el servicio que traduce los **nombres de dominio** legibles para los humanos (como `www.google.es`) a las **direcciones IP** que necesitan los ordenadores (como `142.250.185.3`).

**Analogía:** DNS es como la agenda de contactos de tu teléfono móvil. Tú buscas "María" (nombre de dominio) y el teléfono marca automáticamente el número 612345678 (dirección IP). Sin la agenda, tendrías que memorizar el número de cada persona.

#### ¿Cómo funciona DNS?

Cuando escribes `www.google.es` en tu navegador:

```
  1. Tu PC consulta su caché DNS local.
     ¿Tiene la IP de www.google.es? 
     → Si SÍ: usa la IP en caché. Fin.
     → Si NO: pasa al paso 2.
  
  2. Tu PC consulta al servidor DNS configurado (p.ej., 8.8.8.8).
  
  3. El servidor DNS busca en su propia caché.
     → Si la tiene: responde con la IP. Fin.
     → Si no: inicia un proceso de consultas recursivas.
  
  4. Consulta recursiva (simplificada):
     Servidor DNS → Servidor Raíz (root) → "Pregunta al servidor de .es"
     Servidor DNS → Servidor de .es → "Pregunta al servidor de google.es"
     Servidor DNS → Servidor de google.es → "La IP de www es 142.250.185.3"
  
  5. El servidor DNS devuelve la IP a tu PC.
  
  6. Tu PC almacena la respuesta en su caché para futuras consultas.
```

#### Estructura jerárquica del DNS

```
                       . (Raíz / Root)
                      / | \
                    /   |   \
                 .es  .com  .org  .net  ...
                / \      |
             /     \     |
        google.es  marca.es  google.com
          |                      |
       www.google.es          mail.google.com
```

#### Servidores DNS más utilizados

| Proveedor | DNS Primario | DNS Secundario |
|-----------|-------------|----------------|
| Google | 8.8.8.8 | 8.8.4.4 |
| Cloudflare | 1.1.1.1 | 1.0.0.1 |
| OpenDNS | 208.67.222.222 | 208.67.220.220 |
| Quad9 | 9.9.9.9 | 149.112.112.112 |

DNS opera principalmente en el **puerto 53**, usando **UDP** para consultas rápidas y **TCP** para transferencias de zona (replicación entre servidores DNS).

---

### 16.4 Clientes y Servidores Web

#### El protocolo HTTP/HTTPS

**HTTP** (HyperText Transfer Protocol) es el protocolo que permite la comunicación entre los navegadores web (clientes) y los servidores web. **HTTPS** es la versión segura, que cifra la comunicación mediante **TLS/SSL**.

**Funcionamiento básico:**

```
  Navegador (Cliente)                  Servidor Web
       |                                    |
       |  1. GET /index.html HTTP/1.1       |
       |  Host: www.ejemplo.es              |
       |----------------------------------->|  Puerto 80 (HTTP)
       |                                    |  o 443 (HTTPS)
       |  2. HTTP/1.1 200 OK               |
       |  Content-Type: text/html           |
       |  <html>...</html>                  |
       |<-----------------------------------|
       |                                    |
```

- **HTTP** usa el puerto **80**.
- **HTTPS** usa el puerto **443**.

**Métodos HTTP principales:**
- **GET:** Solicita un recurso (página, imagen, etc.).
- **POST:** Envía datos al servidor (formularios, subida de ficheros).
- **PUT:** Actualiza un recurso existente.
- **DELETE:** Elimina un recurso.

**Códigos de respuesta HTTP más comunes:**

| Código | Significado |
|--------|-------------|
| **200** | OK - Solicitud exitosa |
| **301** | Redirección permanente |
| **404** | No encontrado (recurso inexistente) |
| **403** | Prohibido (sin permisos) |
| **500** | Error interno del servidor |

---

### 16.5 Clientes y Servidores FTP

#### ¿Qué es FTP?

**FTP** (File Transfer Protocol) es un protocolo dedicado a la **transferencia de archivos** entre un cliente y un servidor.

**Características de FTP:**
- Usa **dos conexiones TCP** simultáneas:
  - **Puerto 21:** Canal de control (comandos y respuestas).
  - **Puerto 20:** Canal de datos (transferencia de archivos).
- Soporta autenticación con usuario y contraseña.
- Permite navegar por directorios, subir y descargar ficheros.

```
  Cliente FTP                            Servidor FTP
       |                                      |
       |  Conexión de CONTROL (puerto 21)     |
       |<------------------------------------>|
       |  USER joselu                         |
       |  PASS ****                           |
       |  LIST (listar directorio)            |
       |                                      |
       |  Conexión de DATOS (puerto 20)       |
       |<------------------------------------>|
       |  (transferencia de archivos)         |
       |                                      |
```

> **Nota de seguridad:** FTP transmite las credenciales y los datos en **texto plano** (sin cifrar). Para transferencias seguras se usa **SFTP** (SSH File Transfer Protocol) o **FTPS** (FTP sobre SSL/TLS).

---

### 16.6 Terminales Virtuales

#### SSH y Telnet

Los protocolos de **terminal virtual** permiten a un administrador acceder y gestionar remotamente un dispositivo de red (enrutador, switch, servidor) como si estuviera sentado frente a él.

**Telnet (puerto 23):**
- Protocolo antiguo de acceso remoto.
- **NO SEGURO:** Toda la comunicación (incluida la contraseña) se transmite en **texto plano**.
- **No debe usarse nunca** en redes de producción.

**SSH (Secure Shell, puerto 22):**
- Protocolo moderno y seguro de acceso remoto.
- Toda la comunicación está **cifrada**.
- Soporta autenticación por contraseña o por clave pública.
- Es el estándar para la administración remota de cualquier dispositivo de red o servidor.

**Analogía:** Telnet es como enviar una postal sin sobre (cualquiera puede leer lo que pone). SSH es como enviar una carta dentro de un sobre blindado e ignífugo.

```
  Administrador                          Switch/Router
  (Cliente SSH)                          (Servidor SSH)
       |                                      |
       |  Conexión SSH (puerto 22, cifrada)  |
       |<------------------------------------>|
       |  switch> enable                      |
       |  switch# show running-config         |
       |  switch# configure terminal          |
       |  ...                                 |
```

---

### 16.7 Correo Electrónico y Mensajería

#### Protocolos de correo electrónico

El correo electrónico utiliza varios protocolos que trabajan juntos:

**SMTP (Simple Mail Transfer Protocol) — Puerto 25 / 587:**
- Protocolo para **enviar** correos electrónicos.
- Tu cliente de correo usa SMTP para enviar el correo al servidor de correo de tu proveedor.
- Los servidores de correo usan SMTP entre sí para reenviar los correos hasta el servidor del destinatario.

**POP3 (Post Office Protocol v3) — Puerto 110:**
- Protocolo para **recibir** (descargar) correos electrónicos del servidor al cliente.
- Por defecto, descarga los correos y los elimina del servidor.
- Pensado para acceder al correo desde un único dispositivo.

**IMAP (Internet Message Access Protocol) — Puerto 143:**
- Protocolo para **acceder** al correo electrónico manteniéndolo **sincronizado en el servidor**.
- Los correos se quedan en el servidor y se pueden leer desde múltiples dispositivos (móvil, portátil, tableta).
- Es el protocolo preferido en la actualidad por su flexibilidad.

```
  Flujo del correo electrónico:
  
  [Tu PC]                                    [PC del Destinatario]
  (Cliente correo)                           (Cliente correo)
       |                                            |
       | SMTP (envío)                    POP3/IMAP  |
       |                                 (recepción)|
       v                                            ^
  [Servidor Correo    SMTP (reenvío)    [Servidor Correo
   del Remitente] ==================>    del Destinatario]
  (ej: smtp.gmail.com)                 (ej: correo.orange.es)
```

**Analogía del correo electrónico:**
- **SMTP** es el servicio postal que recoge y entrega las cartas.
- **POP3** es como ir a la oficina de correos, recoger todas tus cartas y llevártelas a casa (desaparecen de la oficina).
- **IMAP** es como tener un buzón inteligente en la oficina de correos: puedes leer tus cartas desde cualquier sitio, y siguen estando allí para consultarlas de nuevo.

#### Mensajería instantánea

Además del correo electrónico, la mensajería instantánea (IM - Instant Messaging) se ha convertido en una forma de comunicación esencial. Aplicaciones como WhatsApp, Telegram, Signal o Microsoft Teams usan protocolos propietarios, aunque muchos se basan en estándares como **XMPP** o protocolos personalizados sobre **WebSocket** y **HTTPS**.

---

### 16.8 Resumen del Módulo 16

En este módulo hemos aprendido que:

- La capa de Aplicación es donde operan los servicios que los usuarios utilizan directamente, siguiendo el modelo **cliente-servidor**.
- **DNS** traduce nombres de dominio a direcciones IP (puerto 53). Es esencial para la navegación web.
- **HTTP/HTTPS** son los protocolos de la web (puertos 80 y 443). HTTPS cifra la comunicación.
- **FTP** se usa para transferencia de archivos (puertos 20 y 21). SFTP es su alternativa segura.
- **SSH** (puerto 22) es el estándar seguro para acceso remoto. **Telnet** (puerto 23) está obsoleto por inseguro.
- El correo electrónico usa **SMTP** (envío), **POP3** (descarga) e **IMAP** (sincronización).
- Todos estos servicios funcionan gracias a las capas inferiores que hemos estudiado en los módulos anteriores.

> *¡Ya conoces todos los servicios fundamentales de la capa de Aplicación! Solo nos queda un tema por cubrir: las herramientas prácticas para probar y diagnosticar problemas en la red.*

---

## Módulo 17: Utilidades de Pruebas de Red

### 17.0 Introducción

> *Un buen técnico de redes no solo sabe cómo configurar una red, sino también cómo diagnosticar y resolver problemas cuando algo falla. En este último módulo aprenderemos los comandos y herramientas esenciales que todo profesional de redes debe dominar.*

---

### 17.1 Comandos de Resolución de Problemas

#### ipconfig / ifconfig / ip

**Propósito:** Mostrar y verificar la configuración IP del dispositivo.

**En Windows: `ipconfig`**
```
C:\> ipconfig

Adaptador Ethernet:
   Dirección IPv4. . . . . . . . . . : 192.168.1.10
   Máscara de subred . . . . . . . . : 255.255.255.0
   Puerta de enlace predeterminada . .: 192.168.1.1

C:\> ipconfig /all        ← Muestra información detallada (MAC, DNS, DHCP)
C:\> ipconfig /release    ← Libera la dirección IP obtenida por DHCP
C:\> ipconfig /renew      ← Solicita una nueva dirección IP al servidor DHCP
C:\> ipconfig /flushdns   ← Limpia la caché DNS local
```

**En Linux: `ip addr` o `ifconfig`**
```
$ ip addr show
$ ifconfig
```

**En macOS: `ifconfig`**
```
$ ifconfig en0
```

#### ping

**Propósito:** Verificar la conectividad con otro dispositivo utilizando el protocolo **ICMP** (Internet Control Message Protocol).

```
C:\> ping 192.168.1.1

Haciendo ping a 192.168.1.1 con 32 bytes de datos:
Respuesta desde 192.168.1.1: bytes=32 tiempo=1ms TTL=64
Respuesta desde 192.168.1.1: bytes=32 tiempo=1ms TTL=64
Respuesta desde 192.168.1.1: bytes=32 tiempo<1ms TTL=64
Respuesta desde 192.168.1.1: bytes=32 tiempo=1ms TTL=64

Estadísticas de ping para 192.168.1.1:
    Paquetes: enviados = 4, recibidos = 4, perdidos = 0 (0% perdidos)
Tiempos aproximados de ida y vuelta en milisegundos:
    Mínimo = 0ms, Máximo = 1ms, Media = 0ms
```

**Interpretación:**
- **Respuesta recibida:** Hay conectividad con el destino.
- **Tiempo de espera agotado (Request timed out):** No hay respuesta. Puede significar que el destino está inaccesible, que hay un cortafuegos bloqueando ICMP, o que la ruta está mal configurada.
- **TTL (Time to Live):** Número de saltos restantes antes de que el paquete sea descartado.

**Estrategia de diagnóstico con ping:**

```
  Paso 1: ping 127.0.0.1    → ¿Funciona la pila TCP/IP local?
  Paso 2: ping [mi propia IP] → ¿Está bien configurada mi IP?
  Paso 3: ping [IP del gateway] → ¿Llego al enrutador?
  Paso 4: ping [IP remota]   → ¿Hay conectividad con Internet?
  Paso 5: ping [nombre dominio] → ¿Funciona DNS?
  
  Si falla en el paso 3 → Problema de red local.
  Si falla en el paso 4 → Problema del ISP o enrutamiento.
  Si falla en el paso 5 → Problema de DNS (el paso 4 funcionó).
```

#### tracert / traceroute

**Propósito:** Muestra la **ruta completa** (todos los saltos) que siguen los paquetes desde tu dispositivo hasta el destino. Es fundamental para identificar dónde se produce un problema de conectividad.

**En Windows: `tracert`**
```
C:\> tracert www.google.es

Traza a la dirección www.google.es [142.250.185.3]
sobre un máximo de 30 saltos:

  1    <1 ms    <1 ms    <1 ms   192.168.1.1         ← Tu router
  2    10 ms     9 ms    10 ms   10.20.30.1          ← Router del ISP
  3    15 ms    14 ms    15 ms   62.81.200.1         ← Red troncal ISP
  4    20 ms    19 ms    20 ms   209.85.149.100      ← Red de Google
  5    21 ms    20 ms    21 ms   142.250.185.3       ← Servidor Google

Traza completa.
```

**En Linux/macOS: `traceroute`**
```
$ traceroute www.google.es
```

**Interpretación:** Si la traza se interrumpe en un salto concreto (muestra `* * *` o tiempos muy altos), el problema probablemente está en ese punto o cerca de él.

#### nslookup / dig

**Propósito:** Consultar los servidores DNS para resolver nombres de dominio a direcciones IP (o viceversa).

```
C:\> nslookup www.google.es

Servidor:  dns.google
Address:  8.8.8.8

Respuesta no autoritativa:
Nombre:  www.google.es
Address:  142.250.185.3
```

En Linux se suele usar `dig`:
```
$ dig www.google.es
```

Es útil para diagnosticar problemas de DNS: si `ping 8.8.8.8` funciona pero `ping www.google.es` no, el problema está en la resolución DNS. Con `nslookup` puedes verificar si el servidor DNS responde correctamente.

#### netstat / ss

**Propósito:** Mostrar las conexiones de red activas, los puertos en escucha y las estadísticas de red.

```
C:\> netstat -an

  Proto  Dirección local        Dirección remota       Estado
  TCP    192.168.1.10:52301     93.184.216.34:443      ESTABLISHED
  TCP    192.168.1.10:52305     142.250.185.3:80       ESTABLISHED
  TCP    0.0.0.0:445            0.0.0.0:0              LISTENING
  UDP    0.0.0.0:68             *:*
```

**Parámetros útiles:**
- `-a`: Muestra todas las conexiones y puertos.
- `-n`: Muestra direcciones y puertos en formato numérico.
- `-b` (Windows): Muestra qué programa utiliza cada conexión.

En Linux moderno se prefiere `ss`:
```
$ ss -tunlp
```

#### arp

**Propósito:** Mostrar y gestionar la tabla ARP del dispositivo (como vimos en el Módulo 13).

```
C:\> arp -a

Interfaz: 192.168.1.10
  Dirección Internet    Dirección física      Tipo
  192.168.1.1           aa-bb-cc-dd-ee-ff     dinámico
  192.168.1.20          11-22-33-44-55-66     dinámico
  192.168.1.255         ff-ff-ff-ff-ff-ff     estático
```

#### Resumen de comandos de diagnóstico

| Comando | Sistema | Propósito | Ejemplo |
|---------|---------|-----------|---------|
| `ipconfig` / `ip addr` | Windows / Linux | Ver configuración IP | `ipconfig /all` |
| `ping` | Todos | Verificar conectividad | `ping 8.8.8.8` |
| `tracert` / `traceroute` | Windows / Linux | Ver ruta hasta el destino | `tracert www.google.es` |
| `nslookup` / `dig` | Windows / Linux | Consultar DNS | `nslookup www.google.es` |
| `netstat` / `ss` | Windows / Linux | Ver conexiones activas | `netstat -an` |
| `arp` | Todos | Ver tabla ARP | `arp -a` |

---

### 17.2 Resumen del Módulo 17

En este último módulo hemos aprendido que:

- **ipconfig/ip addr** muestra la configuración IP del dispositivo y permite gestionar DHCP y la caché DNS.
- **ping** es la herramienta básica para verificar la conectividad entre dos dispositivos usando ICMP.
- **tracert/traceroute** muestra todos los saltos que da un paquete hasta llegar a su destino, permitiendo localizar dónde falla la comunicación.
- **nslookup/dig** permite consultar y diagnosticar problemas de resolución DNS.
- **netstat/ss** muestra las conexiones activas y los puertos en escucha.
- **arp** permite ver la tabla de asociaciones IP→MAC.
- Una estrategia metódica de diagnóstico (de lo local a lo remoto) es clave para resolver problemas de red eficientemente.

> *¡Enhorabuena! Has completado todos los módulos de "Networking Basics". Ahora tienes una base sólida de cómo funcionan las redes, desde el cable físico hasta los servicios de aplicación que usamos cada día. Este conocimiento es el primer paso hacia certificaciones más avanzadas como el CCNA de Cisco.*

---

## Conclusión del Curso

Has recorrido un camino completo por los fundamentos de las redes:

1. **Módulos 1-4:** Descubriste qué son las redes, sus componentes, las tecnologías inalámbricas y cómo montar tu propia red doméstica.
2. **Módulos 5-7:** Comprendiste los protocolos, los modelos OSI y TCP/IP, los medios de red y cómo funcionan las tramas Ethernet y los switches.
3. **Módulos 8-11:** Dominaste el direccionamiento IPv4 e IPv6, la segmentación de redes y la asignación dinámica de direcciones con DHCP.
4. **Módulos 12-14:** Entendiste cómo los datos cruzan los límites de la red con NAT, cómo ARP conecta el mundo IP con el mundo MAC, y cómo los enrutadores deciden el camino de los paquetes.
5. **Módulos 15-17:** Conociste TCP y UDP, los servicios de la capa de Aplicación (DNS, HTTP, FTP, SSH, correo) y las herramientas esenciales de diagnóstico.

Cada concepto se ha construido sobre los anteriores, como los ladrillos de un edificio. Ahora tienes los cimientos sólidos para seguir aprendiendo y profundizar en el apasionante mundo de las redes.

**¡Mucho ánimo y a seguir aprendiendo!**

---

*Documento generado como material didáctico complementario. Basado en los contenidos del currículo Networking Basics de Cisco Networking Academy.*
