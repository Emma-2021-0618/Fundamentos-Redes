## Fundamentos-Redes
fundamentos de red
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
