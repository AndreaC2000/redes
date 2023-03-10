
FECHA: 6/03/2023
NOMBRE: ANDREA CUATINDIOY ORTIZ
CÓDIGO SIMCA:104618021757


Preguntas de lectura: Capítulo 1
1. Describir el efecto que tienen las redes en nuestra vida cotidiana.
Las redes son fundamentales para nuestra vida cotidiana,  dado que en la actualidad se emplean incluso para tomar decisiones frente a compras,
ofrecen entretenimiento, ventas, uso empresarial, chat, video llamadas, nos conectan con el mundo en sí, son indispensables como lo indica el capítulo uno 
“indispensables como el aire”, un ejemplo de esto es cuando se cae Whatsapp y Facebook las pérdidas  millonarias que tienen.  

3. Dar ejemplos de herramientas de comunicación que utiliza o ha utilizado
Facebook
Whatsapp
Twitter
Instagram
Meet
Telegram
Discord
Skype
Hangouts 
Tiktok

5. Identificar los componentes clave de cualquier red de datos y describir su funcionamiento.
Reglas: Protocolos que especifican cómo se envían los mensajes, cómo se dirigen o redirigen y la forma en que serán interpretados, en general 
son reglas que permiten la comunicación entre el emisor y el receptor final. 
Medios: Puede ser por una red por cable o una red inalámbrica por donde viajará nuestro mensaje.
Mensajes: Se tienen diferentes tipos de mensajes entre ellos podemos encontrar, texto, imágenes,  videos, voz.
Todo mensaje será convertido en bits, señales digitales que serán codificadas en binario para viajar por la red y decodificadas  cuando lleguen a su destino final.
Dispositivos finales e intermedios: Son utilizados para conectarse a un servicio, con el fin de acceder se utilizan dispositivos,
el más común es el computador el cual puede enviar y recibir mensajes por una red, pero existen otros dispositivos como: el servidor, teléfono, camaras, 
impresoras, consolas de videojuegos, entre otros.
Para lograr tener una comunicación se utilizan routes tanto alámbricos como inalámbricos, los cuales unen una o dos redes y así asegurar
que el mensaje llegue al destino de la manera más rápida y eficaz.

7. Describir las características de las arquitecturas de red: tolerante a fallas, escalabilidad, calidad del servicio y seguridad.
Mostrar sus respectivos ejemplos. 
Tolerante a fallas: Es la capacidad con la que la red confronta las posibles fallas ya sea al hardware o al software y se logra recuperar rápidamente de ellas, 
si un enlace falla, se logra redireccionar hacia otra de forma rápida siendo esto transparente para el usuario.
Escalabilidad: Esta red cuenta con la capacidad de admitir  nuevos usuarios y aplicaciones sin afectar al servicio, ni el rendimiento de los usuarios actuales. 
Calidad del servicio: La calidad es importante como las dos características mencionadas anteriormente, ya que se debe brindar una buena experiencia para el usuario, como en las transmisiones en vivo ya que se transmite simultáneamente audio y video, lo cual es más atractivo para el usuario.
Seguridad: Al tratar información delicada de cada usuario se debe brindar protección, ya que se debe resguardar la privacidad de cada uno, ya que existen redes, empresariales, institucionales, gubernamentales por lo que se busca incorporar protocolos de seguridad.

9. Describa que es la calidad del servicio y que se necesita para mantener una buena calidad de servicio para las aplicaciones que lo requieren.

La Calidad del servicio es aquella que busca brindar servicios seguros, garantizados, tolerante a fallos, escalables, con el fin de brindar el mejor servicio al usuario, independientemente de la cantidad de usuarios que estén usando ese servicio ya que debe administrar el tráfico de redes congestionado, 
la información se encuentre protegida y que al momento de usarlo no cuente con un mal servicio de red. 
Se deben utilizar mecanismos QoS para garantizar la calidad de servicio

Capitulo 2:

1. Describir la estructura de una red, incluidos los dispositivos, medios y servicios necesarios para lograr comunicaciones exitosas. 

Red: Hace referencia a redes de información capaz de transportar  diferentes tipos de datos, que incluyen datos informáticos, 
voz interactiva, video y productos de entretenimiento, entre otros.

Mensaje -> Codificador -> transmisor -> medio de transmisión “canal” -> receptor -> decodificador -> destino del mensaje

Al hablar de comunicación del mensaje hablamos de segmentación de mensajes, donde el mensaje es dividido en partes más pequeñas.
La multiplexación que entrelaza las piezas de conversaciones separadas.
En las comunicaciones de red, cada segmento del mensaje debe seguir un proceso similar para asegurar que llegue al destino correcto y que pueda
volverse a unir en el contenido del mensaje original.

Las redes usan dispositivos, medios y servicios para lograr su mejor funcionamiento.
Los dispositivos físicos hardware son generalmente el componente visible de la plataforma de red, como una computadora, un switch, un cableado para 
conectarlos entre estos, o puede ser inalámbrico (wifi).
Los servicios y procesos son los programas de comunicación, el software, que ejecuta cada dispositivo conectado a esta red, para que se permita la comunicación.


Los dispositivos de red con los que la gente está más familiarizada se denominan dispositivos finales como computadoras, impresoras, teléfonos VoIP, cámaras de seguridad.
Los dispositivos finales se denominan host, que puede ser el origen o el destino del mensaje transmitido. Cada host en la red se identifica por una dirección.
La red depende de dispositivos intermedios para proporcionar conectividad y para trabajar detrás de escena, para garantizar que los datos fluyan a través de la misma.
Ejemplos de dispositivos de red intermediarios: hubs, switches, routers, modems, firewalls.


3. ¿Cuál es la diferencia entre INTERNETWORK E INTERNET?
Como se observó anteriormente la definición de estos dos conceptos, se podría decir que tenemos que internetwork es una red específica mientras que el internet es una red global. Un conjunto de internetwork son los encargados de originar la red de internet. 

5.  ¿Por qué se dice que un protocolo es independiente de la tecnología? 
Los protocolos son específicos de las características de la conversación. Los protocolos o reglas rigen los distintos métodos de comunicación que existen actualmente en el mundo, no solo hablamos de comunicación por redes, si no en general, es por ello que podríamos decir que es independiente de la tecnología, ya que para hablar o enviar un mensaje, no necesariamente deber ser por un medio tecnológico. 
Los protocolos generalmente no describen cómo cumplir una función en particular. 
Al describir solamente qué funciones se requieren de una regla de comunicación en particular, pero no cómo realizarlas, es posible que la implementación de un protocolo en particular sea independiente de la tecnología.

7. Explicar la función de los protocolos en las comunicaciones de redes y para qué es el proceso de encapsulamiento de los datos 
(ilustrar el nombre que adopta cada PDU en cada capa del modelo TCP/IP mediante un dibujo).

Los protocolos son reglas para que los dispositivos se puedan comunicar de forma exitosa.
Los protocolos usan una suite, la cual debe describir los requerimientos e interacciones 
precisos.
- el formato o estructura del mensaje.
- el método por el cual los dispositivos de networking comparten información sobre rutas 
con otras redes
- cómo y cuándo se pasan los mensajes de error y del sistema entre dispositivos
- el inicio y terminación de las sesiones de transferencia de datos.
El encapsulamiento de paquetes, es como una manera de proteger el mensaje hasta llegar a 
su destino y ser desencapsulado.
Datos: PDU que se utilizan en la capa de aplicación.




Segmento: PDU de la capa de transporte.



Paquete: PDU de la capa de internetwork.


Trama: PDU de la capa de acceso a la red.




Bits: PDU que se utiliza cuando se transmiten físicamente datos a través de un medio



