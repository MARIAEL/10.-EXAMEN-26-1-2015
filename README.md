IFCT0509 Administración de Servicios de Internet

1.- Diferencia entre IP, dominio y servidor, explicar lo que es cada uno.
Las direcciones IP (IP es un acrónimo para Internet Protocol) son un número único e irrepetible con el cual se identifica una computadora conectada a una red que corre el protocolo IP. 
Una dirección IP es un conjunto de cuatro numeros del 0 al 255 separados por puntos.
Un dominio de Internet es una red de identificación asociada a un grupo de dispositivos o equipos conectados a la red Internet.
El propósito principal de los nombres de dominio en Internet y del sistema de nombres de dominio (DNS), es traducir las direcciones IP de cada nodo activo en la red, a términos memorizables y fáciles de encontrar
Las computadoras se conectan entre sí mediante sus respectivas direcciones IP. Sin embargo, a los seres humanos nos es más cómodo utilizar otra notación más fácil de recordar, como los nombres de dominio. 
Un servidor es un equipo (computadora) que se encarga de dar algún tipo de servicio a otros PCs que se denominan clientes. Pueden prestar distintos servicios: creación de páginas Web, base de datos, servidores de ficheros, servidores de impresión, etc.
Una vez explicado que es cada uno de los elementos que se nos pregunta, vemos claramente la diferencia entre ellos: Un servidor es una computadora que necesita una dirección de IP para que los demás PC de la red se puedan comunicar con él y al mismo tiempo tiene un dominio que lo identifica y lo singulariza respecto a los demás.

2.- Describir los siguientes términos, qué son y para qué sirven: HTML, TCP/IP, UDP
HTML ( HyperText Markup Language), es un lenguaje de marcado diseñado para estructurar textos y presentarlos en forma de hipertexto, que es el formato estándar de las páginas web. Gracias a Internet y a los navegadores como Internet Explorer, Opera, Firefox, Netscape o Safari, el HTML se ha convertido en uno de los formatos más populares y fáciles de aprender que existen para la elaboración de documentos para web.
En realidad HTML no es un lenguaje de programación sino que son sentencias  -etiquetas- que nos  indican qué operaciones se van a realizar con el texto o con los atributos que se estén manejando con ese sentencia -etiqueta-. Estas secuencias son muy necesarias para el diseño de una página web ya que cada una de ellas le indica a internet como ésta compuesta la estructura de cualquier Web.

TCP/IP, es una denominación que permite identificar al grupo de protocolos de red que respaldan a Internet http://definicion.de/internet/ y que hacen posible la transferencia de datos entre redes de ordenadores. En concreto, puede decirse que TCP/IP hace referencia a los dos protocolos más trascendentes de este grupo: el conocido como Protocolo de Control de Transmisión (o TCP) y el llamado Protocolo de Internet (IP). 
En este sentido, el primero de los protocolos citados lo que hace es proporcionar un transporte muy fiable de los datos dentro de lo que es el nivel de transporte de referencia OSI. Y mientras, el segundo, el protocolo IP se identifica y define especialmente por el hecho de que lo que hace, en el nivel de red, es ofrecernos la posibilidad de dirigir los citados a otras máquinas.
Asimismo, hay que subrayar que dentro de lo que es TCP/IP existen varios niveles que es muy importante que sean tenidos en cuenta. En concreto son cuatro:

Nivel de aplicación. Es el más alto dentro del protocolo que nos ocupa y en él se encuentran una serie de aplicaciones que tienen la capacidad de acceder a diversos servicios a los que se puede acceder vía Internet.
Nivel de transporte. Es el encargado de ofrecer una comunicación entre extremos de programas de aplicación.
Nivel de red. Se dedica a realizar una serie de acciones sobre la información que recibe del nivel anterior para luego acometer el envío al nivel que está por debajo de él.
Nivel de enlace. Su misión más clara es transmitir la información que recibe al hardware.


UDP, User Datagram Protocol es un protocolo del nivel de transporte basado en el intercambio de datagramas (Encapsulado de capa 4 Modelo OSI). 
Permite el envío de datagramas a través de la red sin que se haya establecido previamente una conexión, ya que el propio datagrama incorpora suficiente información de direccionamiento en su cabecera. 
Tampoco tiene confirmación ni control de flujo, por lo que los paquetes pueden adelantarse unos a otros; y tampoco se sabe si ha llegado correctamente, ya que no hay confirmación de entrega o recepción. 
Su uso principal es para protocolos como DHCP, BOOTP,DNS y demás protocolos en los que el intercambio de paquetes de la conexión/desconexión son mayores, o no son rentables con respecto a la información transmitida, así como para la transmisión de audio y vídeo en real, donde no es posible realizar retransmisiones por los estrictos requisitos de retardo que se tiene en estos casos.

3.- ¿Qué son Javascript, PHP?
Ambos son lenguajes de programación.
Existen diferencias importantes entre ambos. 
JavaScript se utiliza principalmente del lado del cliente (es decir, se ejecuta en nuestro ordenador, no en el servidor) permitiendo crear efectos atractivos y dinámicos en las páginas web.
 Los navegadores modernos interpretan el código JavaScript integrado en las páginas web. 
Para entender lo que es JavaScript consideremos lo siguiente. Un usuario escribe una dirección web en su navegador, por ejemplo http://www.aprenderaprogramar.com. El servidor recibe la petición y como respuesta a esa petición envía al ordenador del usuario código HTML junto a código JavaScript. El código HTML se encarga de que en la pantalla se muestre algo, por ejemplo una imagen, un menú, etc. El código JavaScript se puede encargar de crear efectos dinámicos en respuesta a acciones del usuario, por ejemplo que se despliegue un menú tipo acordeón cuando el usuario pasa el ratón por encima de un elemento del menú.
La ventaja de JavaScript es que al estar alojado en el ordenador del usuario los efectos son muy rápidos y dinámicos.  Al ser un lenguaje de programación permite toda la potencia de la programación como uso de variables, condicionales, bucles, etc. También podemos citar algún inconveniente: por ejemplo si el usuario tiene desactivado JavaScript en su navegador, no se mostrarán los efectos. No obstante, hoy día la mayoría de los usuarios navegan por la web con JavaScript activado.
PHP  es un lenguaje de programación de uso general de código del lado del servidor originalmente diseñado para el desarrollo web de contenido dinámico.
Fue uno de los primeros lenguajes de programación del lado del servidor que se podían incorporar directamente en el documento HTML en lugar de llamar a un archivo externo que procese los datos. El código es interpretado por un servidor web con un módulo de procesador de PHP que genera la página Web resultante. PHP ha evolucionado por lo que ahora incluye también una interfaz de línea de comandos que puede ser usada en aplicaciones gráficas independientes. Puede ser usado en la mayoría de los servidores web al igual que en casi todos los sistemas operativos y plataformas sin ningún costo.

4.- Diferencia entre una base de datos SQL y una no-SQL, características de MySQL y MongoDB. Para que sirve phpMyAdmin.
Una base de datos SQL (Structured Query Language) utiliza un lenguaje de programación diseñado para almacenar, manipular y recuperar datos almacenados en bases de datos relacionales. Una de sus características es el manejo del álgebra y el cálculo relacional que permiten efectuar consultas con el fin de recuperar de forma sencilla información de interés de bases de datos, así como hacer cambios en ellas.
MySQL es un sistema de gestión de bases de datos relacional.  
Las principales características de este gestor de bases de datos son las siguientes:
1.	Aprovecha la potencia de sistemas multiprocesador, gracias a su implementación multihilo.
2.	Soporta gran cantidad de tipos de datos para las columnas.
3.	 Dispone de API’s en gran cantidad de lenguajes (C, C++, Java, PHP, etc).
4.	 Gran portabilidad entre sistemas.
5.	 Soporta hasta 32 índices por tabla.
6.	 Gestión de usuarios y passwords, manteniendo un muy buen nivel de seguridad en los datos.

Por otra parte, una base de datos noSQL , significa que en lugar de guardar los datos en tablas como se hace en las bases de datos relacionales, guarda estructuras de datos en documentos tipo JSON con un esquema dinámico (BSON), haciendo que la integración de los datos en ciertas aplicaciones sea más fácil y rápida.
MongoDB es una base de datos NoSQL orientada  a documentos, desarrollada con código abierto. Sus principales características son:
1.	Consultas Ad hoc: permite búsqueda de campos, consulta de rangos y expresiones regulares 
2.	Indexación: cualquier campo en un documento de MongoDB puede ser indexado y es posible realizar índices secundarios, similar a las bases de datos relacionales.
3.	Replicación: soporta el tipo de replicación maestroesclavo , muy útil para sistemas distribuídos. 
4.	Balanceo de carga: balancea la carga en múltiples servidores.
PhpMyAdmin es una herramienta escrita en PHP con la intención de manejar la administración de MySQL a través de páginas web, utilizando Internet. Actualmente puede crear y eliminar Bases de Datos, crear, eliminar y alterar tablas, borrar, editar y añadir campos, ejecutar cualquier sentencia SQL, administrar claves en campos, administrar privilegios, exportar datos en varios formatos.

5.- Diferencia entre Apache y Node.js
Tanto PHP (que es el lenguaje con que trabaja Apache) como Node.JS funcionan del lado servidor y son opciones viables para el desarrollo de sitios y aplicaciones web.
PHP es un lenguaje de programación de uso general, open source, que funciona del lado de servidor. Originalmente diseñado para producir páginas web dinámicas, fue uno de los primeros lenguajes del lado de servidor que pueden ser embebidos dentro de HTML. El código PHP en un archivo tipo script que, al ser solicitado, es interpretado por un servidor web (generalmente Apache con un módulo procesador de PHP), el cual genera el contenido e imágenes dinámicamente. PHP puede ser desplegado en la mayoría de los sistemas operativos, servidores web y plataformas.
Node.JS es un entorno de programación en la capa del servidor basado en el lenguaje de programación Javascript, con I/O de datos en una arquitectura orientada a eventos y basado en el motor Javascript V8. Por lo tanto, permite que el servidor y las aplicaciones de escritorio se comuniquen por medio de Javascript. En contraste con el uso convencional de Javascript, las aplicaciones con Node.js se ejecutan más rápidamente porque no necesitan de un compilador que interprete el código. De este modo, las aplicaciones creadas con Node.js necesitan menos recursos, funcionan más rápido y por lo tanto ofrecen mejor rendimiento que los servidores tradicionales.

6.- Diferencia entre IP fija /IP dinámica
Dirección IP estática
La dirección IP estática, como su propio nombre indica, permanece estática durante un determinado periodo de tiempo. Esto quiere decir que no se puede cambiar a menos que el usuario así lo decida.
Las direcciones IP estáticas a menudo se emplean en redes protegidas, conexiones de redes privadas virtuales (VPN) y servidores web, entre otros usos.
También pueden ser muy útiles cuando necesite realizar un reenvío de puertos en la red.
El equipo o dispositivo al que se le asigna tiene siempre la misma. Ya sea en Internet (IP fija pública) o en una red doméstica o empresarial (IP fija privada).
Dirección IP dinámica
Por otro lado, la dirección IP dinámica es aquella que cambia cada vez que el usuario se conecta a la red. Un ejemplo perfecto de una dirección IP dinámica es aquella que asigna el proveedor de servicios de Internet (ISP).
Las IP de este tipo son variables. Un equipo o dispositivo puede tener una IP en un cierto momento y una distinta en otro.
No hay una norma fija sobre la frecuencia con que pueden cambiar. A veces se mantienen iguales durante mucho tiempo, mientras que otras cambian a menudo.
Muchos proveedores de Internet asignan IPs dinámicas a sus clientes. Si uno de ellos se desconecta de Internet -y ya "no necesita" su IP- el proveedor puede reutilizarla asignándosela a otro cliente que se conecte.
La "reutilización" de IPs optimiza recursos y abarata costos. Imagina a tu ISP como un hotel. Tiene un número limitado de habitaciones (IPs). Es mejor usar una misma habitación (una misma IP) para varios clientes que mantener la habitación cerrada (la IP sin usar) a la espera de que vuelva un cliente específico.

7.- Qué son y para qué sirven virtualbox y VMWareplayer
Son un software de virtualización para arquitecturas x86/amd64. Por medio de esta aplicación es posible instalar sistemas operativos adicionales, conocidos como «sistemas invitados», dentro de otro sistema operativo «anfitrión», cada uno con su propio ambiente virtual.”
Así podemos disponer de una máquina virtual que nos permite interactuar con la máquina real.
8.- ¿Qué es una conexión puente o bridge y NAT?
Son  dispositivos de interconexión de redes de computadoras
Cuando instalamos un servidor web en una máquina virtual, hemos de comprobar que la IP del servidor sea la misma que la de la máquina real para que funcione correctamente, pero puesto que lo hemos instalado en una máquina virtual con VMVirtualbox, se nos da una IP virtual por defecto (NAT), la hemos de cambiar a ADAPTADOR PUENTE. De este modo tendremos una IP real que  coincidirá con la del servidor.
9.- ¿Qué es un servicio y un puerto?
Un servicio web es una tecnología que utiliza un conjunto de protocolos y estándares que sirven para intercambiar datos entre aplicaciones. Distintas aplicaciones de software desarrolladas en lenguajes de programación diferentes, y ejecutadas sobre cualquier plataforma, pueden utilizar los servicios web para intercambiar datos en redes de ordenadores como Internet. Algunos ejemplos son Apache, MySQL, PHP, etc.
Puerto designa a una interfaz (conexión establecida entre dos computadoras, accediendo a una comunicación entre éstas) por medio de la cual es posible la recepción y transmisión de datos e información.
Los puertos pueden ser clasificados de la siguiente forma:
PUERTO SERIE
PCI (PERIPHERAL COMPONENT INTERCONNECT)
PUERTOS DE MEMORIA
PUERTOS INALÁMBRICOS
PUERTO USB

10.- ¿Qué significa FQDN y para qué se usa?
Un FQDN (sigla en inglés de fully qualified domain name) es un nombre que incluye el nombre de la computadora y el nombre de dominio asociado a ese equipo. Por ejemplo, dada la computadora llamada «serv1» y el nombre de dominio «bar.com.», el FQDN será «serv1.bar.com.»; a su vez, un FQDN asociado a serv1 podría ser «post.serv1.bar.com.». 
En los sistemas de nombre de dominio de zonas, y más especialmente en los FQDN, los nombres de domino se especificarán con un punto al final del nombre.
El FQDN consta de dos partes: el nombre de host y el nombre de dominio. 
Un ejemplo es miequipo.midominio.com.
La longitud máxima permitida para un FQDN es 255 caracteres (bytes), con una restricción adicional a 63 bytes por etiqueta dentro de un nombre de dominio.
Las etiquetas FQDN se restringen a un juego de caracteres limitado: letras A-Z de ASCII, los dígitos, y el carácter «-» , y no distinguen mayúsculas de minúsculas. 
11.- Diferencia entre los servicios ssh y ftp
SSH (o Secure SHell) es un protocolo que facilita las comunicaciones seguras entre dos sistemas usando una arquitectura cliente/servidor y que permite a los usuarios conectarse a un host remotamente. A diferencia de otros protocolos de comunicación remota tales como FTP o Telnet, SSH encripta la sesión de conexión, haciendo imposible que alguien pueda obtener contraseñas no encriptadas.
SSH está diseñado para reemplazar los métodos más viejos y menos seguros para registrarse remotamente en otro sistema a través de la shell de comando, tales como telnet o rsh. Un programa relacionado, el scp, reemplaza otros programas diseñados para copiar archivos entre hosts como rcp. Ya que estas aplicaciones antiguas no encriptan contraseñas entre el cliente y el servidor, hay que evitar usarlas mientras sea posible. El uso de métodos seguros para registrarse remotamente a otros sistemas reduce los riesgos de seguridad tanto para el sistema cliente como para el sistema remoto.
El acrónimo de FTP es protocolo de transferencia de ficheros (File Transfer Protocol) y es un software cliente/servidor que permite a usuarios transferir ficheros entre ordenadores en una red TCP/IP.
FTP tiene sus orígenes en 1971, y aunque ha evolucionado con el paso de los años, es uno de los protocolos más antiguos que todavía están en uso. Hoy en día se usa principalmente en redes corporativas y la red más grande que existe, Internet.
El funcionamiento es sencillo. Una persona desde su ordenador invoca un programa cliente FTP para conectar con otro ordenador, que a su vez tiene instalado el programa servidor FTP. Una vez establecida la conexión y debidamente autenticado el usuario con su contraseña, se pueden empezar a intercambiar archivos de todo tipo.
Muy simple, el protocolo FTP es el sistema de transferir archivos más estable y fiable que hay en Internet. Esto significa que la descarga y subida de archivos que hagas tendrán más opciones de completarse si errores de transferencia, y quedarán intactos después del envío.
Por lo tanto la principal diferencia entre ambos servicios es la seguridad que nos proporciona SSH al encriptar la sesión de conexión.

12.- Calcular el número de subredes y de hosts para estas configuraciones:
192.168.1.112 – 255.255.255.240
8 subredes 
192.168.1.112 – 255.255.255.252



