Proyecto de investigacion universitario llevado a cabo entre el 29-9-2025 hasta el 25-11-2025.

El escenario es ficticio, dado el contexto de la propia tarea.
[GitHub: Ch4mbi](https://github.com/Ch4mbi)

# Introducción

FINBANK EUROPA es un banco enfocado en la banca digital,bancos electrónicos y  servicios de criptomonedas. Recientemente la empresa ha sufrido diversos ciberataques: 
- Troyanos bancarios(TINBA, ZEUS) 
- Intentos de fraude de pagos electrónicos 
- Accesos no autorizados a carteras de criptomonedas 
- Phishing a clientes

Se va a: 
- Analizar amenazas y riesgos en servicios financieros tradicionales y emergentes
- Explicar la arquitectura de los mercados financieros y las cadenas de suministro 
- Evaluar vulnerabilidades de sistemas de pago(Aplicando el estándar PCI DSS)
- Identificar las obligaciones legales y regulatorias aplicables al sector ● Estudio de casos (TINBA,ZEUS,Carbanak) 
- Evaluación de amenazas emergentes en criptomonedas 
- Elaboración de un plan estratégico de mitigación 
- Estrategia de comunicación ejecutiva hacia la junta directiva 
Con el fin de poder prevenir o preparar al entorno financiero para poder defenderse frente a  diversos ataques.

# Amenazas y riesgos en servicios financieros 

Hoy en día, el sector financiero es uno de los principales ,al menos lateralmente, objetivos  de los grupos APT o ataques individuales u organizados ya que son un pilar necesario de  cada país. Objetivamente , el principal factor de riesgo es el factor humano ya que , en un  
primer lugar, es por errores humanos (como caer en correos de phishing). Más aún si el  empleado o el cliente no tiene experiencia en el sector de la seguridad, y da sus datos a  terceros con fines malintencionados. Por otro lado, otra “amenaza” integrada en el sector  financiero son los propios sistemas o procedimientos.  
Popularmente ,las amenazas a la seguridad del sector financiero son: 
- La cadena de suministro (Chain Supply) 
La cadena de suministros en el sector financiero contiene algunos elementos clave  para su correcto funcionamiento: 
  - Transferir datos 
  - Ciclos de tesorería 
  - Compartición de datos de terceros/ proveedores 
  - Almacenamiento de datos 
- Nuevas tecnologías:
A día de hoy las nuevas tecnologías son muy abundantes haciendo que se deba  usar o sea recomendable usarlas cada pocos años. Estos cambios pueden llevar a  vulnerabilidades de las propias tecnologías que si se usan pueden afectar al sector  financiero. Al ser nuevas tecnologías ,como programas o equipos, también requieren  formación adecuada en ellas, por lo que también una mala formación sobre el uso  de las mismas es un riesgo y , a la vez, amenaza en el sector financiero. ● Robo y manipulación de datos 
Debido a la cantidad de datos que mueven los datos, son un objetivo claro para los  atacantes amenazando con robarlos ,alterarlos o incluso bloquearlos usando  ransomware. 
- Falta de talento/concienciación/conocimientos:
Como se mencionó anteriormente los ataques de phishing dirigidos a clientes del  banco o a empleados del mismo es una de las principales razones por las cuales  una empresa o un banco sufre ataques. Eso se debe a la falta de concienciación de  la gente en general en la ciberseguridad, o , al menos, contra el phishing. O , por  ejemplo, en el uso de nuevas tecnologías, el trabajar con ellas sin tener experiencia  o conocimientos en ellas es una amenaza en sí 
- Ciberataques: 
El motivo más común. Hoy en día existen muchos ciberataques, cada uno enfocado  a un objetivo diferente dentro del campo de finanzas. No tiene porqué ser al banco  en sí, sino también, por ejemplo a métodos de pago externos. Diversos informes  indican que los ataques más llevados a cabo en el sector financiero son: ○ Inyección SQL 
    - Inclusión de archivos locales 
    - Secuencia de comandos en sitios cruzados 
    - Inyección Java OGNL 
(Kelly, 2021) 
- Empresas cooperadoras: 
Antes se habló de que los atacantes pueden usar el movimiento lateral para atacar  al banco. Un ejemplo sería el que atacan a un colaborador/rama del banco, con  menos recursos para defenderse, infectando algún equipo que contenga algún  contacto con un alto cargo del banco e ir a por él, como ya se ha hecho en otros  ataques de grupos APT(Carbanak) 

Ataques a finbank, en base a los riesgos y amenazas, en este campo pueden afectar a las  propias operaciones bancarias afectando a: 
- La reputación: 
Si los clientes no están satisfechos por sufrir pérdidas de dinero o fallas en la  aplicación del banco , afectará negativamente a la reputación del banco 
- Operaciones bancarias: 
De la mano con la reputación del banco, fallas en las operaciones bancarias por el  sistema o por ciberataques afectan a la opinión popular de los clientes 
- Continuidad del negocio: 
La continuidad del negocio, en el sector financiero, es crucial para la estabilidad  económica del banco ya que si se rompe la misma, conlleva multas, pérdidas y  también pérdidas reputacionales 
- Economía: 
Toda clase de incidente de seguridad que afecte negativamente al banco llevará a  pérdidas monetarias 
- Impacto independiente: 
   - Cadena de suministro: 
Ataques a la cadena de suministro pueden dar problemas principalmente a la  continuidad y reputación del negocio. 
   - Nuevas tecnologías: 
La mala implementación de las nuevas tecnologías puede llevar a errores  operativos, fallos en la continuidad del negocio y , por ende, pérdidas  financieras y reputacionales ya que no se posee una capacidad suficiente de  manejo de dichas tecnologías 
   - Robo y manipulación de datos:
El robo o la manipulación de los datos afecta a la economía del banco y a la  reputación del mismo. También puede interrumpir operaciones bancarias ,  principalmente si la manipulación de datos conlleva un ataque de  
ransomware,por ejemplo. 
   - Falta de talento/concienciación/conocimientos: 
La falta de talento es una de las principales razones por las cuales se sufren  ataques o los negocios sufren pérdidas. Este factor aumenta la posibilidad de  errores humanos o de ciberataques 
   - Ciberataques:  
Los ciberataques pueden comprometer la continuidad del negocio, la economía del banco, y la reputación del mismo.También pueden afectar a las  operaciones bancarias , interrumpiendo transacciones, bloqueando servicios,  reduciendo la confianza de los clientes,...

# Arquitectura de mercados financieros y cadenas  de suministro 

## Mercados financieros 

La arquitectura de los mercados financieros consiste en la organización de los mismos,  quienes toman lugar en ella y cómo influyen. Principalmente formado por los bancos  centrales siendo estos los responsables de aplicar políticas monetarias, regular las  instituciones financieras y mantener la estabilidad financiera.Las propias instituciones  financieras(Como bancos, empresas de inversión) o los mercados financieros(Compañías  de seguros) facilitan el comercio de activos financieros.  
La arquitectura financiera se refiere a las instituciones y normativas que rigen las relaciones  financieras del mundo. Se crearon, para la estabilidad y el mantenimiento del sector  financiero global tres ejes: 
- El fondo monetario internacional: 
Aporta asistencia financiera para asegurar los pagos de las deudas nacionales de  cada país. También, lleva a cabo un seguimiento e implementación de programas de  salvataje o políticas de ajuste. 
- El Banco Mundial: 
Tiene el objetivo de financiar las políticas de desarrollo en materia de asistencia  focalizada y obras públicas. 
- La organización mundial del comercio: 
Se encarga de amortizar las normas del comercio internacional y liberalizar el  comercio internacional para lograr el flujo comercial 
(Crédito, 2024)

La dependencia de los mercados financieros en la digitalización hoy en día ha supuesto una  notable exposición a riesgos a los mismos como: 
- Accesos no autorizados a sistemas bancarios 
- Manipulación de datos financieros (Junto con el acceso no autorizado)
- Interrupciones en los servicios, punto el cual el banco es el principal objetivo de los  atacantes en este aspecto ya que el sector financiero es un “pilar” de la sociedad  hoy en día 

Por lo que, para mitigar lo riesgos que supone la digitalización de los mercados financieros  se debe: 
- Tener implementado un monitoreo continuo de redes, transacciones, logs,… • Implementar controles de acceso 
- Implementar sistemas de autenticación seguros

## Cadena de suministro 

La cadena de suministros en el sector financiero es una solución que apoya a diversos  proveedores y socios dentro de la cadena productiva,siendo su objetivo principal mejorar la  liquidez de las empresas y permitiendo liberar capital circulante que quedaría retenido en la  cadena de suministros.  
(BBVA, 2024) 
La cadena de suministro tiene 3 actores principales: 
- Proveedores(Los que suministran bienes o servicios) 
- Compradores(Empresas que adquieren productos) 
- Intermediarios financieros(Bancos o plataformas que proporcionan fondos  necesarios para anticipar los pagos) 
En la cadena de suministro en el contexto financiero, hay diversos campos de venta que  intervienen en el proceso(Empresas automovilísticas,supermercados, tecnologías,...). Al  financiar la cadena de suministros, se obtiene ciertas ventajas: 
- Estabilidad económica 
- Reducción de riesgos en la interrupción de la cadena de suministro - - Proveedores satisfechos 
- Reducción de riesgo de retraso de pagos 
- Apoyo a las operaciones empresariales 
Dependiendo de las necesidades de cada individuo o de cada empresa, hay diferentes tipos  de financiamiento de la cadena de suministro: 
- Factoring: 
El proveedor vende las facturas a un intermediario que las paga por adelantado 
- Reverse Factoring: 
El comprador trabaja con el intermediario para garantizar pagos anticipados a los  proveedores 
- Inventory Financing: 
El comprador obtiene el crédito usando el inventario como garantía para financiar la  compra de materias primas o productos terminados 
(consulting, 2025) 
Los atacantes pueden usar estos proveedores para atacar al banco por vías menos  comunes. Esto se debe a que, si es un servicio compartido, los atacantes pueden  aprovechar la vulnerabilidad para acceder al banco, y , por otro, lado, los sistemas de los  proveedores pueden no ser compatibles con las herramientas del banco dificultando la  localización de vulnerabilidades. Para mitigar estos posibles vectores de ataque, se debe: 
- Identificar proveedores críticos 
- Establecer políticas de privacidad adecuadas
- Se deben preparar planes de respuesta ante incidentes para los proveedores  externos
   
## Impacto de la arquitectura financiera en la ciberseguridad 

Las propias arquitecturas , tanto del mercado financiero como de las cadenas de custodia  conllevan riesgos cibernéticos si se administran erróneamente. Un 60% de los ataques en  general suelen originarse de las cadenas de suministro. Finbank, como el resto de  entidades financieras, posee ramificaciones o, por decirlo de otro modo, proveedores  externos relacionados a esta entidad(Cloud, software,...). Estos proveedores externos  suponen riesgos notables ya que, los atacantes pueden moverse lateralmente y, atacando  un servicio externo, pueden atacar el banco. Esta clase de ataques suponen ataques a la  cadena de suministro 
(S., 2025) 
(E&N, 2025) 
La infraestructura compartida, en algunos casos, y los servicios que se usan normalmente  en estos sectores, facilita que una vulnerabilidad de un proveedor tenga un impacto muy  notable en el banco. También cabe destacar que la cadena de suministro, no es 100%  visible , ya que hay muchos procesos llevandose a cabo en cada entidad aliada al banco,  dejando muy posibles vulnerabilidades que no se hayan detectado todavía. Para mitigar  dichos riesgos, se debe de tener un plan de respuesta ante incidentes de terceros , ya que,  al ser “ajenos” al banco, se deben tratar de manera diferente a riesgos o vulnerabilidades  del mismo. Dicho plan debe incluir: 
- Identificación de proveedores criticos 
- Establecer políticas de privacidad respecto a aliados 
- Revisión de las políticas de privacidad de los servicios de terceros 
- Crear planes de mitigación específicos para ataques por estas “ramificaciones”
 Toda la arquitectura financiera y de la cadena de suministro está diseñada para mantener el  flujo de dinero y la constancia, pero esa misma dependencia de proveedores externos  facilita que los ciberataques, en su mayoría, provengan de ellos. Si no se integra la  ciberseguridad desde el principio , toda la infraestructura podría colapsar en cuanto se  produzca un fallo externo.

# Vulnerabilidades de sistemas de pago 

Existen diversos sistemas de pago(Que no usen efectivo), por lo que , debido a la variedad,  hay diversas vulnerabilidades en base al método de pago que se usa, en términos  generales: 
- Tarjetas de crédito: 
   - Phishing:
El uso de tarjetas personales en sitios web fraudulentos es uno de los  principales motivos por los que las estafas se producen. Introduciendo los  datos de la tarjeta de crédito se da acceso a terceros a la cuenta bancaria  personal 
   - Skimming: 
Usando tarjetas de crédito en lugares físicos, un atacante puede instalar  dispositivos en terminales confiables (Cajeros) con el fin de clonar la tarjeta  introducida 
   -  Seguridad de los datos en la transmisión: 
Si ,en caso de compra en tiendas físicas u online, la transmisión del pago no  es segura, el propio pago está en riesgo de sufrir un ataque de MITM 
- Pagos a través de internet con un intermediario 
   - Suplantación: 
Al igual que en el caso anterior, los atacantes pueden hacerse pasar por  sitios web fiables , como paypal por ejemplo, y robar los datos 
   - Exposición de datos: 
En caso de que la propia tienda en línea sea poco segura o no fiable, puede  ser un riesgo a la hora de introducir los datos de la tarjeta de crédito 
- Pagos con dispositivos móviles(NFC): 
   - Proximidad física: 
Hoy en día, con el avance de las tecnologías ,es posible llevar a cabo pagos  a tiendas o a otras personas solo acercando dispositivos móviles entre sí o a  datafonos específicos. Por lo que las personas son vulnerables a robos de  este estilo si tienen el dispositivo móvil con esa configuración 
   - Seguridad del teléfono móvil: 
Si el dispositivo móvil tiene algún tipo de malware puede llegar hasta a  obtener tus datos a medida que los introduces en los dispositivos o  
directamente robar tus datos 
   - Tokens mal implementadas: 
Normalmente las carteras móviles usan tokens para proteger la tarjeta. Si se  tienen errores en las tokens, se pueden generar riesgos 
- Bizum: 
   - Seguridad de la app bancaria: 
La seguridad del bizum depende de la propia app bancaria. Si la app no está  correctamente protegida, el sistema se vuelve mas vulnerable, y , por ende,  los datos de los clientes 
   - Ingeniería social: 
Los atacantes pueden usar la característica de “Solicitar bizum” con  
argumentos invencibles y aprovechar su espontaneidad para obtener  ganancias
(Incibe, 2022) 

## Finbank

Siendo Finbank un banco europeo, es evidente que a día de hoy, ofrece servicios de pago  con tarjetas de crédito o en línea, exponiéndose así a los riesgos que esto supone en un  primer lugar. Para evitar dichos riesgo se va a seguir el PCI DSS(Estándar de seguridad de  datos de la industria de Tarjetas de crédito), el cual se compone de 3 componentes  principales: 
- Gestionar la introducción de datos de tarjetas de crédito de los clientes 
- Almacenar los datos de manera segura(Según se describe en los 12 dominios de  seguridad de la normativa PCI) 
- Validar anualmente que se implementen controles de seguridad necesarios (Stripe, 2025) 
Para seguir el PCI DSS, se requiere aplicar12 requisitos del mismo en el banco finbank: 
1. Aplicar y mantener controles de seguridad 
Se deben configurar e instalar correctamente firewalls y se debe segmentar la red de  pagos de la del resto del banco. Por lo que se debe diseñar una red segmentada  aislada de otros sistemas bancarios 
Finbank debe implementar: 
- Firewalls que permitan mantener segura la red interna 
- Redes aisladas de otros sistemas de pagos y segmentación de la red interna
2. Aplicar configuraciones seguras para los componentes del sistema Usar contraseñas complejas, asegurar la seguridad de los sistemas. Se deben  aplicar en el banco: 
- Políticas que exijan contraseñas seguras 
- Una correcta configuración de los servidores y seguridad en los mismos
3. Proteger los datos de las cuentas 
Se deben cifrar los datos de las cuentas y limitar lo que se almacena según lo  necesario.Una manera de implementar este aspecto en el banco es implementar un  cifrado AES-256 para los datos que se guarden y que dichos datos guardados sean  mínimos 
4. Proteger los datos de las tarjetas mientras se lleva a cabo una transmisión en redes  públicas usando criptografía avanzada 
Las comunicaciones del banco , cuando se transmiten datos, se deben cifrar con  criptografía fuerte para redes públicas y también se debe añadir dicho cifrado a las  comunicaciones entre el cliente y los servidores del banco 
5. Proteger los sistemas y redes de malware 
Se debe tener instalado un antivirus efectivo en los servidores y sistemas 
6. Mantener los sistemas y redes seguros 
Los sistemas y aplicaciones se deben mantener seguros , y , además, se deben  llevar a cabo pruebas y aplicar parches de seguridad para arreglar vulnerabilidades.  Por lo que finbank deberá llevar a cabo dichas pruebas de seguridad y publicar los  parches respectivamente para mantener los sistemas seguros 
7. Restringir el acceso a los componentes del sistema y a los datos de tarjetas  dependiendo del nivel de necesidad 
Solo el personal necesario puede tener acceso a los datos de los dueños de las
tarjetas de crédito. Este acceso se garantiza con roles establecidos en el banco que  dan acceso o no a mas o menos información privada  
8. Identificar a los usuarios y autenticar el acceso a los componentes del sistema Cada empleado que acceda a los usuarios debe tener una identificación sólida y  única. Por lo que , para cada empleado del banco con acceso a datos sensibles , se  debe aplicar un método seguro de autenticación multifactor 
9. Restringir el acceso físico a los datos de las tarjetas 
Hay que controlar quién tiene acceso físico a los servidores o sistemas de  almacenamiento donde se almacenan datos de los usuarios. En el banco se deberá aplicar seguridad física ,como guardias, monitoreo con cámaras de seguridad, y uso  de credenciales de acceso físico(Tarjetas/pines) que den o no acceso físico a los  datos (A las salas con los servidores donde se almacenen) 
10. Registrar y supervisar el acceso a los componente del sistema y datos de tarjetas Todos los logs deben de monitorizarse continuamente para detectar posible  actividad sospechosa. Se deberá usar un SIEM para monitorizar accesos y poder  alertar sobre comportamientos raros y se deberá automatizar para alertar sobre  comportamientos extraños 
11. Probar regularmente la seguridad 
Se deben llevar a cabo pruebas para encontrar vulnerabilidades, normalmente cada  1-2 meses, pruebas de penetración, y llevar a cabo revisiones periódicas de  seguridad 
12. Apoyar la seguridad de la información con políticas y programas organizativos  Hay que tener políticas de seguridad formales para su seguridad de la información y  se deben comunicar a todo el personal. También, con esas políticas se formará al  personal en el sector de la ciberseguridad , al menos a un nivel base para que , si  las medidas de seguridad fallan, puedan identificar intentos de robo de credenciales  por ejemplo 
(secureframe, 2025)

En conclusión, para aplicar el PCI DS a finbank correctamente para afrontar los diversos  riesgos se deben aplicar al banco estos requisitos: 
- Segmentación de la red 
- Seguridad de la red interna con firewalls correctamente implementados • Usar un cifrado fuerte(AES-256) para encriptar los datos mínimos almacenados • Usar un SIEM para detectar comprometimientos anómalos y que se generen alertas  en tiempo real 
- Implementar el acceso basado en roles y la autenticación multifactor asegurando así  que el personal autorizado pueda interactuar con los sistemas de pagos Como resultado de la implementación de dichos requerimientos en el banco, los incidentes  de seguridad podrán ser contenidos sin exfiltraciones de datos , haciendo posible mantener  la continuidad de los servicios de pago. Demostrando así la efectividad del cumplimiento del  PCI DSS en la protección de los datos de las tarjetas de los clientes 

## Buenas prácticas 

Se van a redactar algunas buenas prácticas en algunos campos importantes del banco a  implementar para mejorar la seguridad 
- Red
   - Segmentación de red 
   - Correcta aplicación e implementación de firewalls 
- Configuraciones 
   - Contraseñas fuertes 
   - Cambios de contraseñas anuales(Mejora de seguridad) 
- Almacenamiento de datos 
   - Cifrado de datos 
   - Almacenar datos relevantes(Omitiendo datos no importantes) 
- Defensa 
   - Antivirus actualizado 
   - Detección proactiva(Equipos encargados de detectar amenazas) 
- Control de acceso 
   - Zero Trust 
- Autenticación 
   - Usuarios únicos junto con autenticación sólida 
   - Contraseñas débiles  
- Pruebas de seguridad 
   - Llevar a cabo escanear regulares para encontrar vulnerabilidades 
   - Llevar a cabo pruebas de penetración para hallar nuevas vulnerabilidades 

## Propuestas innovadoras de seguridad para los pagos 

También se pueden aplicar o tener en cuenta consideraciones para innovar la seguridad del  método de pago de finbank. Estas posibles medidas a implementar pueden rebajar el estrés  sobre los trabajadores o ayudarles a administrar mejor sus tareas o asignarles otras incluso. 
- Justificar pagos 
Este aspecto, aunque ya se ve en bizum y en otras plataformas de transferencias,  no se aplica a compras online o físicas, o al menos en pocos casos(suele llegar un  correo después de realizar la compra). Lo idóneo sería que al intentar llevar a cabo  
una compra física u online, llegue un mensaje al número de teléfono en el que se  confirme o se niegue el pago 
- Uso de ia para automatizar procesos de pago 
Con el anterior punto, el uso de ia está relacionado con una confirmación del usuario  al hacer la compra, pudiendo agilizar los procesos. También, aunque esto esté más  del lado de los logs, hacer un análisis de los momentos en los que los usuarios  suelen entrar a la app del banco o suelan o tiendan a hacer compras en línea o física  en mayor cantidad(Festividades o cumpleaños), para que se envíe un correo de  confirmación al usuario dueño de la cuenta si es él(Número de teléfono y correo  electrónico requiriendo una confirmación de los dos en caso de que sea desde otro  dispositivo, por ejemplo, por un cambio de teléfono o móvil)

# Obligaciones legales y regulatorias 

Siendo el sector financiero uno de los sectores más importantes del mundo, es necesario  aplicar ciertas obligaciones regulatorias para evitar fallas de seguridad y legales para evitar  cometer delitos de cualquier forma, incluso al sufrir un ataque es posible salir perdiendo aún  más si , por ejemplo, no se publica el ataque(Si ha sido de gran magnitud) en un periodo de  tiempo determinado, esto no solo afecta a los bancos sino también a negocios. Algunas  obligaciones legales y regulatorias que el banco debe seguir son: 
- GDPR(Reglamento general de protección de datos): 
   - Obliga a Finbank a proteger y responsabilizarse de los datos personales de  los clientes, garantizando su privacidad y confidencialidad 
   - Si llegase a ocurrir una brecha de seguridad que pueda llegar a afectar a los  datos personales, el suceso se deberá notificar a la Agencia española de  protección de datos y/o a los clientes afectados 
   - Las regulaciones que contiene este reglamento permite evitar sanciones  legales severas y proteger la reputación del banco y sus servicios 
- PCI DSS: 
   - Es un estándar internacional que regula no la seguridad de los propios datos  personales en sí, sino los datos de las tarjetas de crédito 
   - Obliga a implementar medidas de seguridad como: 
      - Encriptación de los datos 
      - Autenticación de seguridad fuerte 
      - Monitorización constante de las transacciones para poder detectar  tráfico inusual 
      - Control de acceso 
   - El cumplimiento de esta normativa permite reducir el riesgo de fraude y  mejora la confianza de los clientes 
(Acosta, 2024) 
- DORA: 
 - Reglamento europeo que exige a las entidades financieras gestionar los  riesgos tecnológicos  
 - Impone pruebas periódicas en sistemas y supervisión de los proveedores  tecnológicos críticos 
 - Exige pruebas de resiliencia 
 - Requiere llevar a cabo un monitoreo constante 
 - Necesario para la aplicación del banco y para garantizar la continuidad de los  servicios financieros 
- Notificación de incidentes 
   - Finbank debe notificar sus incidentes de seguridad con un procedimiento  formal dentro de los plazos legales. El plazo máximo para notificar un  incidente varía dependiendo de la gravedad de dicho incidente y del punto de  tiempo pasado desde el incidente: 
      - Informe inicial 
4 horas máximo desde el incidente(Si es grave)(El tiempo de  
notificación empieza cuando se determina la gravedad del incidente) , y como  muy tarde, 24 horas
  - Informe intermedio 
72 horas ,como muy tarde  
  - Informe final 
Como mucho 1 mes después del incidente 
Si se sufren retrasos , se deben notificar los motivos del mismo lo antes  posible. En España, las alertas se deben notificar al Banco de España, el  cual actúa como autoridad ante incidentes de este tipo(Cibernéticos), aunque  dependiendo del tipo de institución, o del reglamento que se está siguiendo,  el receptor puede variar 
(Gómez, 2025) 
 - No respetar el RGPD(GDPR) conlleva el pago de multas junto con la pérdida  de confianza de los clientes 
(Asociados, 2024) 
(EALDE, 2020) 
(España, 2024) 

# Casos de estudio

Finbank ha sufrido ciertos incidentes de seguridad recientemente relacionados con ataques  de malware y grupos APT(Aadvanced Persisted Thereat): 
- TINBA 
- ZEUS 
- Carbanak 
Ya que estos ataques, se componen por correos de phishing a empleados y  clientes,accesos no autorizados a cuentas o a carteras de criptomonedas, fraudes,... Es  necesario analizar sus técnicas, tácticas y procedimientos para no ser vulnerables a ellos, y  poder entender cómo cada uno atacaba, comportamienos comunes de los mismos, modo  de “expansión” de los mismos 

## TINBA 

También llamado Tinybanker y Suzy,TINBA es un troyano que infecta dispositivos  windows(7,8,vista y xp) con el objetivo de robar credenciales o información útil  principalmente sobre datos bancarios. El troyano se instala por medio de spam,  suplantación de organizaciones, usando ingeniería social para que el usuario visite sitios  web maliciosos 
(Incibe, 2024) 
Es un troyano que empezó el ataque en EEUU,Turquía,Croacia, y República Checa para,  posteriormente, trasladarse a Polonia,Holanda ,Italia y Alemania(Esta migración se debe a  que el troyano era “maleable”/”editable” dependiendo del atacante).A día de hoy ,se sabe  que el troyano afectó a más de 4,1 millones de usuarios y a casi 1500 instituciones  financieras. Tinba simula la red del banco de cada usuario, permitiendo al atacante obtener  datos bancarios y, en algunos casos , funciona a modo de red de botnets. El malware se  ejecuta en la propia red del banco y el usuario afectado recibe un mensaje de un fallo de  ingreso de dinero en su cuenta, y piden reembolsar dicho dinero a un enlace que  envían(Ingeniería social). El dinero supuestamente transferido al usuario no es real, pero  por otro lado, el dinero que devuelva será del propio usuario
(Barrera, 2015) 
El funcionamiento de TINBA consiste en: 
1. Infección inicial 
Usando técnicas de ingeniería social(Correos electrónicos con links/archivos,  mensajes en la propia pagina del banco,...) 
2. Ejecución y persistencia 
Tras la instalación del troyano, se ejecuta como un proceso oculto. El troyano  modifica configuraciones del sistema para asegurar su persistencia en el sistema
3. Inyección de código 
El troyano inyecta código en los navegadores web, modificando sus procesos para  insertar scripts diseñados para interceptar datos. 
4. Captura de información 
Tinba puede obtener información por medio de la inyección de formularios falsos o la  modificación de páginas web legítimas, haciendo que la víctima ingrese datos  pensando que van a estar seguros. 
5. Comunicaciones con el servidor C&C 
El troyano se comunica cada cierto tiempo con el servidor C&C para recibir  actualizaciones o para enviar datos.  
6. Evasión de detección 
Usa técnicas para pasar desapercibido en los sistemas. Por ejemplo, técnicas de  ofuscación, uso de técnicas de persistencia, y la ocultación para evitar el análisis de  amenazas 
7. Actualización y configuración 
El troyano recibe actualizaciones desde el servidor C&C que modifican su  funcionamiento u objetivos o añaden nuevas maneras de evadir sistemas. 8. Exfiltración de datos 
Los datos robados son enviados al servidor C&C del atacante, pudiendo estar  ubicado en una infraestructura comprometida o una red de servidores  comprometidos. 
(CiberWiki, 2024) 

## ZEUS 

Zeus, también llamado Zbot es un troyano ,el cual se originó en 2006(Identificado en 2007 y  creado en el 2005), de equipos Windows(7,8,vista y xp) con el objetivo de robar  credenciales bancarias o información importante. Y los ordenadores infectados pasan a  formar parte de una red botnet(Red la cual se vio mejorada por una de las versiones de  Zeus, GameOver, que cifraba las comunicaciones). Con este contexto, se puede decir con  seguridad que tinba y zeus forman parte de la misma “familia” de malware, aunque zeus sea  más antiguo y no esté nada relacionado con tinba, pero son indiscutiblemente similares en  algunos aspectos. 
Zeus se usó en un primer lugar para robar información confidencial(sobre los  sistemas,credenciales de usuario,...), pero por su alto nivel de personalización , se podía  modificar para que recopilase toda clase de información y no solo antes de empezar el  ataque, el troyano tenía conexión establecida con el servidor C&C del atacante y podía  recibir actualizaciones.
El troyano era distribuido por medio de spam y phishing para que la víctima acceda a sitios  web malintencionados, por medio de un enlace, para infectarle. Aunque por lo modificable  que era Zeus, podía haber más métodos. 
(incibe, 2024) 
(MITRE, 2024) 
Zeus está orientado a empresas ,diseñado para interrumpir la productividad o ganar dinero,  pudiendo robarle a clientes o a empresas. Tras que el ordenador objetivo es infectado y se  añade a la botnet, se comunica con el servidor C&C y es supervisado por el atacante, el  cual puede acceder con control remoto y controlarlo(Solo en algunas versiones del mismo).  El troyano monitoriza la actividad de los navegadores web de las víctimas para obtener  credenciales bancarias y/o inyectar scripts en páginas web abiertas. 
Los creadores de Zeus crearon el virus con la idea de que pase desapercibido, dejando  trabajar a las víctimas con sus dispositivos sin ningún tipo de problema. Mientras el troyano  estuviera más tiempo en el ordenador, más datos recogería. Cada ordenador en la red  botnet puede usarse como respaldo en caso de que otro ordenador se desconecte de la red  botnet. 
(proofpoint, 2025) 
Al principio, Zeus robaba contraseñas por medio de la función de almacenamiento de  contraseñas de Internet Explorer obteniendo las contraseñas almacenadas en el navegador  y, si detectaba que la víctima visitaba una web bancaria, usaba el registro de tecleos del  teclado o métodos de captura de formularios desde el navegador para obtener nombres de  usuario y contraseñas. 
(Belcic, 2022) 

## Carbanak 

Carbanak es un grupo APT enfocado en el sector financiero, aunque también ese nombre  se le da a una familia de malware del mismo grupo. Anunciado en diciembre de 2014 y en  febrero de 2015. El grupo no buscaba sacar la mayor cantidad posible de beneficios a  ciegas, sino que más bien se centraba en ataques a objetivos específicos, equipos de alto  valor ,por ejemplo, los infectan y los usaban para moverse lateralmente hacia otros  dispositivos de los cuales sacar beneficios(Confirmado por medio de un análisis de las  muestras comportamiento de red y análisis estático para comparar código). Uno de sus ataques fue a un hotel casino. El vector siendo un correo electrónico phishing  que contenía un exploit. El grupo lo llevó a cabo con el objetivo de comprometer servidores  en los puntos de venta usados para procesar pagos. El backdoor usado era conocido como  meterpreter(programa de interpretación de comandos), aunque el código de dicho programa  fue alterado para añadirle una nueva funcionalidad, la inyección del proceso svchost.exe(Se  confirmó por el analisis del código binario). El backdoor metia 2 malware: 
- Win32/Spy.Sekur→Malware reconocido usado por Carbanak 
  - Win32/Wemosis→Un backdoor para los PoS(Point of Sale) denominado Ram  Scraper. Ataca cualquier PoS que almacene en memoria datos de tarjetas de  crédito. También está programado en Delphi(Lenguaje de programación usado para  crear apps nativas de Windows) que permite el control remoto de los equipos  infectados.
Ambos ejecutables estaban certificados por la empresa Blik, esto se sabe por la  comparación de los metadatos. El mismo certificado fue usado también para la firma digital  de otro malware también usado por el grupo apt, Win32/Spy.Agent.ORM. 
  - Win32/Spy.Agent.ORM era un troyano usado como primer ataque (payload) en la  primera etapa del ataque carbanak. Su código comparte similitudes del código con el  malware que carbanak usa normalmente(Sekur). Esto se sabe por el análisis de  código que se llevó a cabo. El troyano se encarga de conectar con su servidor C&C  y recibe comandos para tomar capturas de pantalla o enumerar procesos activos en  el dispositivo. De esta manera, podían descartar los dispositivos que no les eran  útiles. Se sabe que el troyano para obtener privilegios del sistema e instalarse a sí  mismo,intentaba aprovecharse de la vulnerabilidad CVE-2015-2046. Hoy en día,esta  familia de malware ya es conocida ya que en 2015, Cyphort informó sobre los  ataques a un portal de noticias y Windows ya parcheó las vulnerabilidades. 
Tras que el malware Spy.Agent.ORM fuera anunciado, la empresa Blue Coat informó sobre  correos de phishing enviados a empleados del Banco central de armería junto con un  payload en el mismo. 
Se notan los repetidos intentos de atacar a empresas de origen ruso y ucraniano por medio  de correos de phishing , con contexto del banco ,con archivos .SCR (Con iconos de word o  de adobe acrobat) o exploits RTF. Aunque no se limitaba a Rusia, sino que también  enviaron correos similares a bancos de los Emiratos Árabes, Alemania,... y también es un  grupo que sigue activo hoy en día ,con intentos de ataque a Estados Unidos junto con  Emiratos Árabes , Alemania,... 
El análisis y la comparación de código y certificados junto con la recolección de los  indicadores(Nombres de fichero, patrones de phishing,...) ayudó a los investigadores a  reconstruir la campaña para comprender lo sucedido en este ataque 
(Cherepanov, 2015)

# Evaluación de amenazas en criptomonedas 

Hoy en día, la criptomoneda más conocida es el bitcoin, cuyo precio varía y su valor se  puede disparar. Este sistema de inversión posee una gran dificultad de seguimiento de las  transacciones. A la hora de adquirir criptomonedas, hay que tener en cuenta diversos  aspectos o vulnerabilidades o ataques que pueden sufrir que habría que mitigar en un  primer lugar si se va a incluir en el nuevo método de pago: 
- Ataques de puentes 
Es un tipo de ataque que se lleva a cabo a las operaciones de las criptomonedas. El  ataque consiste en mover criptomonedas de un “grupo” a otro(blockchain). El  proceso de movimiento de un grupo a otro se le llama puente entre cadenas. Los  atacantes pueden interceptar dichos puentes usando errores de código,  introduciendo malware o atacando (MITM). También de aquí pueden salir ataques a  las carteras de las personas, principalmente a las conocidas como “calientes” ya que  estas están conectadas todo el rato a internet, aprovechando las vulnerabilidades en  redes , los atacantes las atacan 
- Ataque a la plataforma de criptomonedas 
Algunos dueños de criptomonedas prefieren usar plataformas de intercambio para  gestionar sus criptomonedas. Al tener almacenadas o transmitir grandes volúmenes  de criptomonedas, estas plataformas son objetivos de los atacantes, los cuales , en  estos casos, suelen recurrir a phishing, o la ingeniería social para robar las  criptomonedas. 
- Ataques al intercambio de criptomonedas 
   - Phishing 
Uso de correos electrónicos de atacantes que engañan a los dueños de  criptomonedas para que den su propia información personal o se descarguen  malware que vacíe sus carteras 
   - Malware 
Ya que las plataformas relacionadas con criptomonedas se basan en código  y están conectadas a internet, los atacantes pueden encontrar  
vulnerabilidades por las cuales instalar código malicioso. 
   - Robo de claves 
Los propietarios de criptomonedas necesitan claves para acceder a sus  criptomonedas. Los atacantes pueden intentar conseguir dichas contraseñas  de diversas maneras 
- Exploits de protocolos DeFi 
El ataque a Balancer causó 100 millones de dólares de pérdidas. Esta pérdida se  debió a errores en el propio código, en el contrato inteligente que permitió retiros no  autorizados. 
(Arruda, 2025) 

También hay que tener en cuenta ataques que se han llevado a cabo en otros momentos a  otras empresas: 
- Ronin Network 
En 2022,la sidechain llamada Ronin Network sufrió un ataque del que robaron  173000 eth y 25,5 millones de usdc(Superando un total de 600 millones). El ataque  consistió en usar claves privadas comprometidas para falsificar retiros
(Harán, 2022) 
- Poly Network 
Empresa que facilita el movimiento entre varias cadenas de bloques cuando los  usuarios intercambian una cadena por otra. En 2021, polinetwork sufrió un gran robo  de criptomonedas. Los atacantes aprovecharon un fallo de validación de mensajes  entre las block chains conectadas al puente, permitiéndoles firmar transacciones  como si fueran legítimas. El hacker devolvió la mayoría de fondos para demostrar la  vulnerabilidad 
(Russon, 2021) 
- FTX 
FTX, que es uno de los exchanges más grandes de criptomonedas, en 2022 sufrió  un colapso causado por una empresa aliada mantenía expuestas tokens privadas de  usuarios. Ante esta exposición , comenzaron las retiradas masivas, y FTX congeló  los retiros y , poco después, se declaró en bancarrota 
(Fran, 2025) 
- Mt.Gox 
Uno de los primeros sitios que permitía a los usuarios intercambiar bitcoin. En junio  de 2011,un hacker usó credenciales robadas para alterar el valor nominal del bitcoin  de $16.85 a $0,01 y transfirió 2000 bitcoins fuera de las cuentas de los clientes y los  clientes compraron bitcoins baratos durante el hackeo 
(101, 2023) 
(kaspersky, 2025) 

## Medidas de mitigación 

Frente a las amenazas de las carteras de criptomonedas o a la compra de criptomonedas,  ya que finbank posee un servicio del mismo, se deben implementar maneras de asegurar  las carteras de los clientes para que no sufran ataques ni pérdidas. 
- Uso de una cartera segura 
Es una de las maneras más sencillas de asegurar las ganancias. Se debería de usar  una cartera en frío ya que al no estar conectadas a internet, son más seguras que  las que están en caliente. Una cartera en frío es un hardware usado para proteger y  almacenar las monedas en un espacio independiente del internet 
- Autenticación multifactor 
Se recomienda activar la autenticación multifactor siempre que sea posible, siendo,  en el uso de carteras, algo indispensable. 
- Usar redes privadas y seguras 
Los atacantes pueden atacar tu dispositivo desde espacios con wifi públicos y , si se  tienen almacenadas en el dispositivo conectado, pueden intentar y conseguir las  monedas. 
(kaspersky, 2024) 
- Seguridad de los puentes 
Como en el ataque de puente a Ronin, los atacantes robaron claves privadas para  robar los datos de los clientes. Por eso se deben llevar a cabo auditorías de  seguridad para los puentes que se usen y también se deben validar los contratos  inteligentes
- Backups cifrados 
Se deben cifrar con un cifrado suficientemente seguro los datos y los backups de  los mismos. También, se deben almacenar fuera de internet, en ubicaciones seguras  para que el atacante no pueda acceder a dichos backups 
- Custodia híbrida 
Se debe adoptar un sistema de custodia híbrida, en la cual los fondos se almacenan  en carteras en frío mientras que una pequeña parte está en carteras en caliente  destinadas a operaciones diarias. 
(Arruda, 2025)

## Predicciones de amenazas futuras 

- Aumento de ataques a puentes 
Los atacantes pueden optar por intentar romper la seguridad o, por otro lado,  pueden centrarse en encontrar fallos en el propio código. Estos ataques aumentarán  cuanto mayor sea la superficia propia de ataque(A más carteras digitales, o  expansiones del banco, más “territorio” pueden tener para atacar) 
- Robos a carteras 
A pesar de usar diferentes tipos de carteras, no se puede estar realmente protegido  al 100%. Los atacantes, en este caso, pueden estar desarrollando nuevos malware  como troyanos que obtengan claves privadas de los usuarios y robar las  cuentas/tarjetas 
- Interés de los atacantes en el banco 
Ya que finbank, como otros bancos, ofrecen servicios de criptomonedas, los  atacantes pueden optar por atacar al centro de todo para obtener claves o acceso a  información confidencial, ya que los bancos mueven más información y dinero que  las propias carteras dgitales 

# Plan estratégico de mitigación 

Ante incidentes de seguridad, en el nuevo método de pago de Finbank, y en el propio banco  en sí, hay que establecer un plan estratégico que se deba llevar a cabo en caso de  incidentes de seguridad. Se van a redactar varios pasos a seguir: 
1. Preseguridad  
Posiblemente el menos relacionado con un plan en sí, pero el nuevo método de  pago debe de tener unas medidas de seguridad previas para no hacerlo totalmente  vulnerable, y, al mismo tiempo, mejorar la seguridad del propio banco. Este apartado  de seguridad recoge las medidas que se deben aplicar inmediatamente para poder  preparar un entorno suficientemente seguro en un primer lugar. Algunas medidas  preventivas ante ataques son: 
- Encriptación segura de los datos con AES-256 
- Uso de contraseñas fuertes 
- Red protegida 
Segmentación de la red para separar pagos, compras online, servidores,... 
- Uso de VPN y un cifrado en las comunicaciones 
- Backups
- Pruebas de penetración junto con arreglo de vulnerabilidades y  
actualizaciones constantes 
- Monitorización continua junto con control de transacciones 
- Aplicación de métodos autenticación para todos los empleados 
- Evaluaciones anuales de riesgos  
- Formación continua y concienciación de los empleados(Tanto de  
ciberseguridad como ajenos a este sector) 
2. Preparación 
Se debe definir, organizar , y formar un equipo adecuado especializado en la  respuesta ante incidentes de seguridad con diferentes roles(Analistas, soporte legal  y técnico, directores,...). Se debe tener todo redactado y documentado ,los roles, las  responsabilidades, las maneras de abordar incidentes,... Se deben de tener  preparadas copias de seguridad cifradas aisladas mensualmente 
3. Detección y contención del incidente 
En un primer lugar, para detectar comportamiento anómalo, se debe de usar un  SIEM para poder identificar accesos no autorizados o comportamientos  sospechosos. En caso de detectar tráfico malintencionado, se debe de aislar los  sistemas afectados.También se debe de activar la autenticación. 
4. Erradicación y recuperación 
- Eliminación de malware 
- Restaurar datos y servicios con backups 
- Verificar la integridad de los datos críticos 
- Llevar a cabo un informe técnico 
5. Mejora  
Se debe elaborar un informe final en el que se explique claramente:  
- El impacto del ataque 
- Costes del ataque 
- Tiempo de recuperación 
- Medidas de seguridad que fallaron y cómo mejorarlas 
También se deben llevar a cabo simulacros de seguridad para probar la eficacia del  plan y llevar a cabo mejores planes en el futuro que puedan ayudar en la seguridad de la  empresa 
(Padua, 2025)

# Comunicación ejecutiva hacia la junta directiva 

El análisis llevado a cabo en finbank muestra que el banco enfrenta riesgos y retos de  seguridad considerables. Debido a eso, la empresa debe mejorar sus defensas y resiliencia  mediante la implementación del plan estratégico de mitigación ya diseñado. Un incidente de  seguridad en finbank puede tener varios tipos de impactos: 
- Pérdidas económicas y reputacionales 
- Sanciones regulatorias (Según el GDPR, PCI DSS o Dora) 
- Trabajar más en las defensas de la organización 
En resumen ,se deben de implementar estas medidas para mejorar la seguridad y evitar  riesgos innecesarios del banco: 
- Mejora la seguridad de los pagos/transacciones y criptomonedas usando la  autenticación multifactor , el cifrado avanzado y la custodia híbrida 
- Reforzar la protección frente a malware bancario 
- Se debe de asegurar la cadena de suministros, llevan a cabo auditorías de  seguridad  
- Se debe crear un equipo capacitado de respuesta ante indecentes con roles y  responsabilidades bien definidas 
- Se debe invertir tiempo y dinero en capacitar a los empleados para que no caigan en  estafas tanto como fuera como dentro del entorno laboral

# Bibliografía 

101, C., 2023. ¿Qué es Mt. Gox?. [En línea]  
Available at: https://www.bitstamp.net/es/learn/crypto-101/what-is-mt-gox/ [Último acceso: 22 11 2025]. 
Acosta, D., 2024. ¿Qué es PCI DSS?. [En línea]  
Available at: https://www.pcihispano.com/que-es-pci-dss/ 
[Último acceso: 20 11 2025]. 
Arruda, G., 2025. Ciberseguridad en el mundo cripto: avances, riesgos y aprendizajes de  2025. [En línea]  
Available at: https://www.welivesecurity.com/es/seguridad-digital/avances-riesgos ciberseguridad-cripto-2025/ 
[Último acceso: 22 11 2025]. 
Arruda, G., 2025. Ciberseguridad en el mundo cripto: avances, riesgos y aprendizajes de  2025. [En línea]  
Available at: https://www.welivesecurity.com/es/seguridad-digital/avances-riesgos ciberseguridad-cripto-2025/ 
[Último acceso: 23 11 2025]. 
Asociados, A. &., 2024. Normas específicas para el sector financiero: Todo lo que necesitas  saber. [En línea]  
Available at: https://alasociados.es/normas-sector-financiero/ 
[Último acceso: 20 11 2025]. 
Barrera, S., 2015. Tinba, el virus informático que incrementa el saldo de tu cuenta para  luego robártelo. [En línea]  
Available at: https://www.lasexta.com/tecnologia-tecnoxplora/internet/ciudad-con-ley/tinba virus-informatico-que-incrementa-saldo-cuenta-luego 
robartelo_2015101357fd28fe0cf2fd8cc6b1e650.html 
[Último acceso: 21 11 2025]. 
BBVA, 2024. ¿Qué es el supply chain finance y para qué sirve?. [En línea]  Available at: https://www.bbvacib.com/es/insights/news/que-es-el-supply-chain-finance/ [Último acceso: 18 11 2025]. 
Belcic, I., 2022. El troyano Zeus: qué es y cómo eliminarlo y evitarlo. [En línea]  Available at: https://www.avast.com/es-es/c-zeus 
[Último acceso: 21 11 2025]. 
Cherepanov, A., 2015. El grupo de APT Carbanak volvió con nuevos trucos bajo la manga.  [En línea]  
Available at: https://www.welivesecurity.com/la-es/2015/09/08/carbanak-nuevos-trucos/ [Último acceso: 22 11 2025]. 
CiberWiki, 2024. Tinba. [En línea]  
Available at: https://darfe.es/ciberwiki/index.php?title=Tinba 
[Último acceso: 20 11 2025]. 
consulting, s., 2025. El Supply Chain Financing: qué es y cómo aprovecharlo. [En línea]  Available at: https://www.simcoconsulting.com/es/articulos-logistica-cadena-suministro/el supply-chain-financing-que-es-y-como-aprovecharlo.html 
[Último acceso: 18 11 2025].
Crédito, J. e. D., 2024. La arquitectura del sistema financiero global. [En línea]  Available at: https://jadireldoctorcredito.com/la-arquitectura-del-sistema-financiero-global/ [Último acceso: 18 11 2025]. 
E&N, 2025. Hasta 60 % de ciberataques surgen de vulnerabilidades en la cadena de  suministro. [En línea]  
Available at: https://www.revistaeyn.com/empresasymanagement/hasta-60-de-ciberataques surgen-de-vulnerabilidades-en-la-cadena-de-suministro-NB25356182 [Último acceso: 19 11 2025]. 
EALDE, 2020. Normativas básicas en Compliance financiero. [En línea]  Available at: https://www.ealde.es/compliance-financiero-normativas-basicas/ [Último acceso: 20 11 2025]. 
España, B. d., 2024. Tecnologías de la información en el sector financiero. [En línea]  Available at: https://www.bde.es/wbe/es/areas-actuacion/normativa/regulacion-sistema financiero/tecnologias-de-la-informacion-en-el-sector-financiero.html 
[Último acceso: 20 11 2025]. 
Fran, 2025. ¿Cómo fue la caída de FTX? El imperio de Sam Bankman-Fried. [En línea]  Available at: https://es.beincrypto.com/aprende/caida-ftx-sam-bankman-fried/ [Último acceso: 22 11 2025]. 
Gómez, C. C., 2025. DORA, ¿cuáles son los plazos de notificación, qué sanciones  contempla y cuál es el papel de los CSIRT?. [En línea]  
Available at: https://blog.grupocfi.es/es/dora-plazos-sanciones-csirt 
[Último acceso: 20 11 2025]. 
Harán, J. M., 2022. Robaron más de 620 millones en ataque a Ronin, la red blockchain que  utiliza Axie Infinity. [En línea]  
Available at: https://www.welivesecurity.com/la-es/2022/03/31/ataque-ronin-red-blockchain utiliza-axie-infinity/ 
[Último acceso: 22 11 2025]. 
Incibe, 2022. Métodos de pago y su seguridad. [En línea]  
Available at: https://www.incibe.es/ciudadania/blog/metodos-de-pago-y-su-seguridad [Último acceso: 20 11 2025]. 
Incibe, 2024. Tinba. [En línea]  
Available at: https://www.incibe.es/servicio-antibotnet/info/Tinba 
[Último acceso: 21 11 2025]. 
incibe, 2024. Zeus. [En línea]  
Available at: https://www.incibe.es/ciudadania/servicio-antibotnet/info/zeus [Último acceso: 21 11 2025]. 
kaspersky, 2024. ¿Cómo reforzar la seguridad de tu criptomoneda?. [En línea]  Available at: https://www.kaspersky.es/resource-center/preemptive-safety/strengthen cryptocurrency-security 
[Último acceso: 23 11 2025]. 
kaspersky, 2025. Los ataques más importantes al intercambio de criptomonedas: cómo  protegerse contra la piratería. [En línea]  
Available at: https://www.kaspersky.es/resource-center/threats/crypto-exchange-hacks [Último acceso: 22 11 2025]. 
Kelly, B., 2021. Amenazas de seguridad en los servicios financieros. [En línea]  Available at: https://www.globalsign.com/es/blog/5-friday-5-security-threats-facing-financial services-industry 
[Último acceso: 18 11 2025].
MITRE, 2024. Zeus Panda. [En línea]  
Available at: https://attack.mitre.org/software/S0330/ 
[Último acceso: 21 11 2025]. 
Padua, M., 2025. Plan de ciberseguridad: Pasos esenciales para construirlo. [En línea]  Available at: https://www.itmastersmag.com/ciberseguridad/construir-un-plan-de ciberseguridad-pasos-esenciales/ 
[Último acceso: 23 11 2025]. 
proofpoint, 2025. ¿Qué es el troyano Zbot (Zeus)?. [En línea]  
Available at: https://www.proofpoint.com/es/threat-reference/zeus-trojan-zbot [Último acceso: 21 11 2025]. 
Russon, M.-A., 2021. Poly Network: los hackers que devolvieron casi la mitad de la  millonaria suma que habían robado. [En línea]  
Available at: https://www.bbc.com/mundo/noticias-58186888 
[Último acceso: 22 11 2025]. 
S., J. L., 2025. La importancia de la Arquitectura de Ciberseguridad. [En línea]  Available at: https://www.linkedin.com/pulse/la-importancia-de-arquitectura-ciberseguridad juan-luis-saavedra-0qhxe/ 
[Último acceso: 19 11 2025]. 
secureframe, 2025. Los 12 requisitos de cumplimiento de PCI DSS. [En línea]  Available at: https://secureframe.com/es-es/hub/pci-dss/12-requirements [Último acceso: 20 11 2025]. 
Stripe, 2025. Introducción al cumplimiento PCI. [En línea]  
Available at: https://stripe.com/es-us/guides/pci-compliance 
[Último acceso: 20 11 2025].


[GitHub: Ch4mbi](https://github.com/Ch4mbi)


