# Fundamentos-Redes
## capas
-------------------------------------------
Cosas que aprendi y aplica de estas materia
4cJ%U^9tS7q7
-------------------------------------------

firewall
antivirus
vpn


cable conarcial, todos tiene informacion de todos

dns traduce el nombre a un dominio

asignacion de ip automatica host config todo

email el primero enviar los otros reciben

mandar achivos de file tranfer

ucp mandar la informacion una vez y tcp manda la veces necesarias para mantener uan red

capa 1

cuando se sabe la red, solo faltaria la ip fisica 
la capa 2 esta divididad en 2 sub capas
y se encarga de el control de acceso en los medios, como se ingresar y extraer los bits ese es su rol, sus divisiones son llc  control de enlaces logicos que se comunica con la capa de red o protocolosy mac control de acceso a medios que se comunica con el hardware

estandar llc llc-ieee 121

ka subcapa llc toma los datos del protocolo de red, y agregar informacion de control de capa 2 

la subcapa mac cntrola la mic y otro hardware responsable de enviar y recibir datos en los emdios 
la subcpa mac propciona encapsulamiento de datos

los protocolos d cpa de enlace de datos los definen las organizaciones ieee, itu, uso, ansi

topologia nos referemos a la forma que esta distristubuilos los nodos y cable

topologia fisica, muestra las conexiones fisicas y como los deispositvos estan inter conectados

topologia logica las dirreciones ip y como se comunicar entre ellos

entre las topologia mas comunicas de la wan
punto a punto
los dispositivods esta conectados uno a uno estan conectaod directo, el protocolo no tiene gran funcionamiento, el protocolo no es tran estricto puede ser completa fisica o logica, se le llama un circuito virtual, ya que se configuraron asi
hub and spoke
yba toplogia wan tambien conocida como topologia estrella es una diseno de red donde todos los diitos remotes es una rede daea ream palica se conectan una lugar central llamda hub si falla todo tendra problema

malla
una topologia en malla es que todos los dipositovs son independiente ya que se se cae uno se puede ir desde otra punta pero mas costoso
craando una estructura de red completamento o pparcialmente interconectada, e nuan topologia de malla, cada nodod tine una conexiion directa con todos los demas nodods formando una red redundante y robusta

tipos comunues de malla
malla completa y malla parcial

las lan sueler usaruan topologia estrella o estrealla entendida 
bus topologia en bus o anillo

comunicacion duplex medio y completo

comunicacion semiduplex
solo permite que un dispotivo envie o reciba a la vez en un medio compartido 
se utiliza en wlan y topologias de bus heredadas con hubs ethernet

comunicion duplex completo full
permite que ambos dispositivos transmitan y reciban simulltaneamente  es una medio compartido
los swiches ethernet funcionan en modo full-duplex

netidis de control de acceso

 acceso basads en al contencion

 todos los nodos operan en semidubples por el uso de medios mpuede citarse como ejemoplo

 carrier sense mutiple access with collision detection csmm/cd como  sew uen la ethernt de topolida de bus

 carrier sense mutiple access with collision avoiddance cssma/ca como se usa en lan inalambrica

  acceso controlado acceso determinista donde cadauno tiene su propioa tiempo en el medio 
  se utiliza e neredes antiguos como tiken ring y arcnet, si tu turno paso y no tiene nada pasa turno y espera que tenga su turno, red poco eficente

  acceos baea da en contencion

  csma cd utilizacion por lantehernet ntiguos 
  funciona en modo semidubples donde sol ocun dispotivos envia oc recibe a la vez
  utliza un prorecos deteccion de collision para controlar cuando se puede enviar ispotvivo y que sucede si vaerios disposivos envan al mismo tiepo

  proceso de deteccuib de cikusuibes csna cdma cd
   los dispotivos que trasmiten simultaneamente procaran una colision de senal en ele medio
   los dispotivos etan la colision
   los dispotivos esperan un periodo aleatorio de tiempo y retransmiten datos

   acceos badao en ela cntencion csma ca

   utilizado por wlan ieee 802.11
   funcioan en modo semidubples donde solo funcioan envios

   la trama unidad de based datos formada por el encabezado, datos y trailer
   - el primero los datos de control
   - los datos
   - para comprobar si s corrompio en el camino

DIRRECIONES DE CAPA 2 tambiens e cono como uan direccion fisica solo se tiene como uan red privada ya que fuera de ella no tiene sentido

contenid oen la encabezado de la trama 

   

http 80 o cualquiera

conecion enternet es lan
- ethnert funicona en la capa enlace de datos en la capa fisca
- es una familia de tecnologia de red definidad en los estandares ieee 802.2 y 802.3

Los protocolos IEEE 802 LAN/MAN, incluyendo Ethernet, utilizan las dos subcapas independientes siguientes de la capa de enlace de datos para operar. Son el Control de enlace lógico (LLC) y el Control de acceso a medios (MAC), como se muestra en la figura.

Recuerde que LLC y MAC tienen los siguientes roles en la capa de enlace de datos:

- Subcapa LLC - Esta subcapa IEEE 802.2 se comunica entre el software de red en las capas superiores y el hardware del dispositivo en las capas inferiores. Coloca en la trama información que identifica qué protocolo de capa de red se utiliza para la trama. Esta información permite que múltiples protocolos de Capa 3, como IPv4 e IPv6, utilicen la misma interfaz de red y medios.
  
- Subcapa MAC - Esta subcapa (IEEE 802.3, 802.11 o 802.15, por ejemplo) se implementa en hardware y es responsable de la encapsulación de datos y control de acceso a medios. Proporciona direccionamiento de capa de enlace de datos y está integrado con varias tecnologías de capa física.

  Los protocolos IEEE 802 LAN/MAN, incluyendo Ethernet, utilizan las dos subcapas independientes siguientes de la capa de enlace de datos para operar. Son el Control de enlace lógico (LLC) y el Control de acceso a medios (MAC), como se muestra en la figura.

Recuerde que LLC y MAC tienen los siguientes roles en la capa de enlace de datos:

Subcapa LLC - Esta subcapa IEEE 802.2 se comunica entre el software de red en las capas superiores y el hardware del dispositivo en las capas inferiores. Coloca en la trama información que identifica qué protocolo de capa de red se utiliza para la trama. Esta información permite que múltiples protocolos de Capa 3, como IPv4 e IPv6, utilicen la misma interfaz de red y medios.
Subcapa MAC - Esta subcapa (IEEE 802.3, 802.11 o 802.15, por ejemplo) se implementa en hardware y es responsable de la encapsulación de datos y control de acceso a medios. Proporciona direccionamiento de capa de enlace de datos y está integrado con varias tecnologías de capa física.

calidad de servicio DS, DSCP , ECN

traduccion de una red privada a una red publica se traduce la ip address

route print mostra la tabla de dirreciones locales de equipo y virtuales
netstat tabla de enrutamiento

tabla mac arp -a

gatewat predeterminado

debe de tener la misma estructara que la red privada y tiene una interfaz que se comunica con la red publica

## Desconocer la dirrecion de MAC de una red
Resolucion de direccion

Destino de la misma red
A veces, un host debe enviar un mensaje, pero solo conoce la dirección IP del dispositivo de destino. El host necesita saber la dirección MAC de ese dispositivo, pero ¿cómo se puede descubrir? Ahí es donde la resolución de direcciones se vuelve crítica.

Hay dos direcciones primarias asignadas a un dispositivo en una LAN Ethernet:

- Dirección física de capa 2 (la dirección MAC) – Se utiliza para comunicaciones NIC a NIC en la misma red Ethernet.

- Dirección lógica de capa 3 (la dirección IP) – Se utiliza para enviar el paquete desde el dispositivo de origen al dispositivo de destino. La dirección IP de destino puede estar en la misma red IP que la de origen o en una red remota.

Las direcciones físicas de capa 2 (es decir, las direcciones MAC de Ethernet) se utilizan para entregar la trama de enlace de datos con el paquete IP encapsulado de una NIC a otra NIC que está en la misma red. Si la dirección IP de destino está en la misma red, la dirección MAC de destino es la del dispositivo de destino.

Considere el siguiente ejemplo utilizando representaciones de direcciones MAC simplificadas.

se buscara en la red mediante el defaulf gateways y buscar esa dirrecion nic 

destino en una red remota
cuando la direccion ip destino esta en una red remota, la direccion mac de destino es la de la puerta de enlace predetermninada
- ipv4 utiliza arp para acociar la direccion ipv4 de una dispositvo con la direccion mac de la nic del dispositivo
- ipv6 utiliza ICMPV6 para asociar la direccion ipv6 de un dispositivo con la direccion MAC de la nic del dispositvo

arp protocolo de resolicon dirrecion

ára enviar una dispositivo buscar en su tabla arp 

Cuando se envía un paquete a la capa de enlace de datos para encapsularlo en una trama de Ethernet, el dispositivo consulta una tabla en su memoria para encontrar la dirección MAC que está asignada a la dirección IPv4. Esta tabla se almacena temporalmente en la memoria RAM y se denomina tabla ARP o caché ARP.

El dispositivo emisor busca en su tabla ARP la dirección IPv4 de destino y la dirección MAC correspondiente.

Si la dirección IPv4 de destino del paquete está en la misma red que la dirección IPv4 de origen, el dispositivo busca la dirección IPv4 de destino en la tabla ARP.
Si la dirección IPv4 de destino está en una red diferente que la dirección IPv4 de origen, el dispositivo busca la dirección IPv4 del gateway predeterminado.
En ambos casos, se realiza una búsqueda de la dirección IPv4 y la dirección MAC correspondiente para el dispositivo.

En cada entrada o fila de la tabla ARP, se enlaza una dirección IPv4 con una dirección MAC. Llamamos a la relación entre los dos valores un mapa. Esto solamente significa que es posible buscar una dirección IPv4 en la tabla y encontrar la dirección MAC correspondiente. La tabla ARP almacena temporalmente (en caché) la asignación para los dispositivos de la LAN.

Si el dispositivo localiza la dirección IPv4, se utiliza la dirección MAC correspondiente como la dirección MAC de destino de la trama. Si no se encuentra ninguna entrada, el dispositivo envía una solicitud de ARP.

Haga clic en Reproducir en la figura para ver una animación de la función ARP.

modulo 11 direccionamiento ipv4

porciones de red y host
- una direccion ipv4 es una dirrecion jerarquica de 32 bits que se compone de una porion de red y una porcion de host
- al determinar la posrcion de red frente a la porcion de host, debe mirar la secuenciia de 32 bits
- se utiliza una mascara de subred ya que ip no permite la direccion duplica desde los primeros 3 conjuntos de 8 bits

- para idetentiicar las porciones de red ya que la porcion de red ya que 255.255.255.0 es una parte de los primeros obtentos

la longitud de prefijo
- mascara uan longitud de prefijo es una metodo mas sencillo utilizando para udebtufucar una masara de subred
- a mayor numero de red menor host pero mas pontencia y a menor red mayores host tengo
- esta escrito en notacion de host por lo tanto, cuente el numero de bits en la mascara de subred y anadalo con una barra
- los hostetos debe ser continuos

  determinacion de la red and logica

  uan operacion logica and boolean se utiliza para determinar la dirrecion mediante una tabla de verdad con modulacion y

descubrimiento de venico

dirreciones ed red,host y difusion
- direcion de red
- direcion de host
- direccion de broadcast

  rango util es toda la dirrecion ip que esta entre el identificar de la red y el broadcast
si el ultimo obtento cuando terminar 0 no se puede usar como referencia de esa
unicast
- la transimision unicast esta enviado un paquete a una direciion ip

broadcast

- es cuando se manda a todos los dispositivos de la red
- se envia por todos los puertos menos por donde envio

multicast

- la transmision de multicast esta envida a algunos equipos en especifico
224.255.255.255 se utilizo
  

  tipos de direcciones ipv4

  las direcciones privada tiene fecha sde expiracion

  rango de red privada
10.0.0.0/8
172.16 al 172.31 es privadi
tambien 192.168 a 192.168

nuestra dirrecion privada se traduce con una dirrecion publica 

direccion de loopback es cuando el equipo esta capacitado para comunicarse con ella misma.

dirrecion de enlace local se le conoce con direcion de apipa i direccuibes autoasignadas

direccionamiento con clase legcy

rfc 790 asigna direcciones ipv4

en clase A 0.0.0.0/8 a 127.0.0.0/8
en clase B 128.0.0.0/16 a 191.255.0.0/16 camaras ip toman las clases b
en Clase C 192.0.0.0/24 a 223.255.255.0/24
en Clase D 224.0.0.0 a 239.0.0.0
en Clase E 240.0.0.0 255.0.0.0

problemas con lso dominios de broadcast grandes

- segmentando al red
- al segmentar la red se puede hacer una porcion de sub red

motivos para dividir en subredes

- la division en subredes disminuye ek trafico de red general y mejora su rendimiento
- se puede utilizar para implementar de seguridad entre subredes ka subredees reduce el numero de dispostis afectadir oir ek trafico de broadcast anormal

subnetear una red ipv4

son mas faciles dividir redes en /8 /16 /24 y tiene host 16777214 65534 254

subred privada frente al espacio de direcciones ipv4 publico
las redes empresariales tendra un intranet la red interna de una empresa nomrlmente utiliza direcciones ipv4 privadas 
dmz contiene recursos disponible para internet, los dispositivos de la dmz utilizan direcciones ipv4 

uan empresa podria utilizar 10.0.0.0/8 y la sybred en el limite de red /16 o /24

los dispositivos de dmz tendrian que configurarse con direcciones ip publicas.

VLSM


