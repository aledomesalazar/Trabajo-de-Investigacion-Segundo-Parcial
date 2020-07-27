## Trabajo-de-Investigacion-Segundo-Parcial
### INTRODUCCIÓN A LA PROGRAMACIÓN EN PYTHON DE RASPBERRY EN CREATE.WITHCODE.UKL
**1. PLANTEAMIENTO DEL PROBLEMA**

La Raspberry PI surge por la necesidad de promover la enseñanza de la programación para estudiantes de secundaria y universidad, y se da por ser muy popular fuera del campo de la educación, en particular en la emulación de juegos, centros de medios, sistemas embebidos y robótica, con el fin de facilitar el aprendizaje de la programación en cualquier lenguaje dado para el control de información.

**1.1. Contexto Y Antecedentes**

La Fundación Raspberry Pi surgió en Caldecote, South Cambridgeshire, Reino Unido como una asociación caritativa que es regulada por la Comisión de Caridad de Inglaterra y Gales. Esta fundación surge con un objetivo en mente: desarrollar el uso y entendimiento de los ordenadores en los niños por medio de dispositivos portátiles y baratos, con la finalidad de que llegaran a entender el funcionamiento básico del ordenador de forma divertida, y sean ellos mismos los que desarrollen y amplíen sus dispositivos, argumento afirmado por David Braven. 

El cofundador de la fundación es Eben Upton, un antiguo trabajador de la empresa Broadcom, responsable de la arquitectura de software y hardware de la Raspberry PI, se puso en contacto con un grupo de profesores, académicos y entusiastas de la informática para crear un ordenador con la intención de animar a los niños a aprender informática como lo hizo en 1981 el ordenador Acorn BBC Micro.

Los primeros diseños de Raspberry Pi se basaban en el microcontrolador Atmel Atmega644. El primer prototipo basado en ARM fue montado en un paquete del mismo tamaño que una memoria USB. Tenía un puerto USB en un extremo y un puerto HDMI en el otro. El primer lote de 10.000 placas se fabricó en Taiwán, China, debido a sus bajos costos y la pronta entrega del producto. Con este ahorro conseguido, la fundación podía invertir más dinero en investigación y desarrollo.

En agosto de 2011, se fabricaron cincuenta placas Alpha del modelo inicial, el Model A (o modelo A), mientras que en diciembre de 2011, 25 placas Beta del modelo B fueron ensambladas y probadas de un total de 100 placas vacías. Durante la primera semana de diciembre del mismo año, se pusieron a subasta diez placas en eBay, por lo que la demanda de adquisición fue enorme provocando que los servidores estuvieran colapsados.

Actualmente, la fundación da soporte para las descargas de las distribuciones para arquitectura ARM, Raspbian (derivada de Debian), RISC OS y Arch Linux; y promueve principalmente el aprendizaje del lenguaje de programación Python, y otros lenguajes como Tiny BASIC, C y Perl. Es sobrecogedor que la tecnología esté cada vez a nuestro alcance y a su vez nos permita aprender de ella, siendo parte de la solución de problemas en la vida cotidiana. 

La intención de uso de este dispositivo no es solo su manejo interno, sino que los estudiantes de todas las edades, sobretodo niños, sepan diseñar circuitos eléctricos, donde su control se lo realiza en software. No es necesario saber mucho de electrónica de forma teórica, sino implementar la lógica tanto para encender un led como para controlar un juego de luces. Esto permite la iteración con el mundo real y ampliar su imaginación permitiendo que en un futuro diseñen auténticos artefactos.

Actualmente se han desarrollado plataformas que permiten programar sin necesidad de adquirir hardware. Existen numerosos IDEs online, pero uno especializado para ejecutar con el hardware de la Raspberry es create.withcode.uk. Ejecuta cualquier archivo en formato .py, pero también simula la librería GPIO, enfocada para el control de elementos electrónicos por medio de la activación de los pines de la Raspberry. Esto permite la realización de pruebas para asegurar las instrucciones escritas antes de ejecutarlo en un entorno físico. La principal página es el libre acceso a ella, facilitando el desarrollo de proyectos y su modelo es moderno, acoplándose rápido a su uso.

Con las herramientas dadas para la construcción de proyectos de electrónica, solo queda enfocar en la programación en Python, especialmente con la librería GPIO, aprender su sintaxis, detectar errores y mostrar sus resultados. Así que por ello se tratará de que este trabajo sea lo más entendible para una persona que tenga poco o nulo conocimiento sobre estas herramientas.

**1.2. Formulación del Problema**

¿Cómo influye la programación en Python en la plataforma online create.withcode.uk. para la transmisión de datos en la Raspberry PI?

**1.3. Hipótesis de Investigación**

La programación en Python para el envío y recepción de datos en una Raspberry PI es óptimo para el control de dispositivos electrónicos.

**2. OBJETIVOS**

**2.1 Objetivo General**

Analizar los principales métodos de programación de Python en la plataforma online create.withcode.uk. para la transmisión de datos en la Raspberry PI 

**2.1 Objetivos Específicos**
- Identificar los elementos del hardware y software del dispositivo.
- Investigar las instrucciones básicas de la librería GPIO de Python para el control de información del dispositivo.
- Describir los principales componentes de la página web create.withcode.uk

**3. ESTADO DEL ARTE**

*Identification of Fruit Size and Maturity Trough Fruit Images Using OpenCV-Python and Raspberry Pi.*

En el año 2017, Izadora Mustaffa y Sywal Fikri Bin Mohd Khairul, investigadores de la Universidad Teknikal Malaysia, realizaron un algoritmo en el lenguaje de programación Python que permite la detección de la madurez de las frutas de mango; el código fue ejecutado en una Raspberry Pi. El algoritmo procesa imágenes ingresadas y es totalmente capaz de determinar el tamaño de la fruta aplicando el agrupamiento K-mean (una función de Python) para poder determinar el color de la fruta y decir si ésta se encuentra madura o no. (Mustaffa & Khairul, 2018)

*Implementation of Google Assistant on Raspberry Pi*

Septimiu Mischie, Liliana Mâiu-Iovan y Gabriel Gpresc, investigadores de la Universidad Politécnica de Timisoara, desarrollaron en 2018 una investigación detallada sobre cómo implementar la voz del asistente de Google en una microcomputadora Raspberry Pi. En el artículo se encuentran todos los detalles y cada uno de los pasos para poder implementar el asistente de Google a este dispositivo que tan solo contiene un micrófono y un altavoz. Además, de la implementación también realizaron la evaluación de un sistema de reconocimiento de voz. (Mischie, Matiu-Iovan, & Gasparesc, 2018)

*A Survey: How Python Pitches in IT-World*

Arun Kumar, Supriya P.Panda, investigadores del Departamento de CSE de MRIIRS en Faribadab, realizaron en 2019 el artículo con el objetivo de dar a conocer a la comunidad de programadores sobre todas las funcionalidades del lenguaje de programación Python. Este lenguaje cuenta con distintas estructuras de datos, bibliotecas que permiten la implementación de distintos códigos. Además de explicar el funcionamiento, también muestran como funciona Python con distintas comunidades, comercios, etc., proporcionando resultados deseables. (Kumar & Panda, 2019)

**4. MARCO TEÓRICO**

**4.1. Raspberry PI**

*4.1.1. Definición*

Raspberry PI es una placa computadora con bajo coste, se podría decir que es un ordenador de tamaño reducido, como un ordenador de bolsillo. Su hardware es principalmente un ordenador desnudo, en la cual todos los accesorios se pueden eliminar sin que afecte al funcionamiento básico. A la raspberry Pi la han definido como una maravilla en miniatura, que guarda en su interior un importante poder de cómputo en un tamaño muy reducido. Es capaz de realizar cosas extraordinarias.(RASPBERRY PI – Historia de la Informática, 2020).

*4.1.2 Hardware*

4.1.2.1 Elementos Básicos
- Pines de entrada y salida de propósito general (Conector GPIO):
Posee un conector de GPIO de 8 pines, sin un propósito específico, cuyo comportamiento (incluyendo si es un pin de entrada o salida) se puede controlar (programar) por el usuario en tiempo de ejecución.

- Energía y Alimentación:
La placa carece de botón de encendido y apagado, con lo que la energía le llega mediante un conector microUSB estándar de 5 [V]. El consumo de la placa es de 700 [mA], (3,5[W]). Muchos cargadores diseñados para smartphones funcionarán con la Raspberry Pi, pero no todos, ya que, algunos solo suministran hasta 500mA y la raspberry consume más energía que la mayoría de los dispositivos micro-USB y requiere de al menos 700mA para funcionar.

- S.O. soportados (Linux vs Windows/OS X):
La Raspberry Pi está diseñada para ejecutar el sistema operativo GNU/Linux, S.O. de código abierto, a diferencia de los sistemas operativos de código oculto como Microsoft Windows o Apple OS X. Esto quiere decir que es posible descargar el código fuente del sistema operativo por completo y hacer los cambios que uno desee. Nada es ocultado, y todos los cambios hechos están a la vista del público.

4.1.2.2 Elementos generales:

Su placa, de forma general, está constituido por los siguientes elementos:
- Un Chipset Broadcom BCM2835, que contiene un procesador central (CPU) ARM1176JZF-S a 700 MHz.
- Un Procesador gráfico (GPU) VideoCore IV
- Un módulo de 512 MB de memoria RAM
- Un conector de RJ45 conectado a un integrado lan9512 -jzx de SMSC que  conectividad a 10/100 Mbps
- Dos buses USB 2.0
- Una salida analógica de audio estéreo por Jack de 3.5 mm.
- Una Salida digital de video + audio HDMI
- Una salida analógica de video RCA
- Pines de entrada y salida de propósito general (GPIO)
- Conector de alimentación microUSB
- Lector de tarjetas SD

*4.1.3 Software*

Los sistemas operativos disponibles son:
- Raspbian
- Arch Linux
- RaspBMC
- Pidora 
- OpenELEC
- Windows 10

**Figura 1**

Actualmente existen 2 modelos diferentes de Raspberry Pi. 

Modelo A:
- Posee un solo puerto USB
- No tiene controlador Ethernet
- Tiene 256MB de RAM
- No tiene un puerto RJ45. Se puede conectar a una red usando un adaptador USB-Ethernet suministrado por el usuario.

Modelo B
- Tiene dos puertos USB y controlador Ethernet 10/100
- Tiene 512MB de RAM

**Figura 2**

**4.2 Python**

Este lenguaje de programación fue creado en 1991 por Guido van Rossum en CWI - Holanda, con el propósito de análisis de datos. En él se puede realizar múltiples operaciones matemáticas entre variables, listas, arreglos, matrices, entre otros. Es multiparadigma, enfocándose en la programación estructurada, dinámica, funcional y orientada a objetos; además es adaptable en cualquier plataforma. Empresas o instituciones lo han utilizado  aplicaciones como Facebook, Google, Amazon, NASA e IBM.

Es el lenguaje recomendado para aprender a programar debido a que se maneja con una sintaxis simple y entendible, caracterizándose por ser un lenguaje de alto nivel, es decir, lenguaje más acercado a la comunicación con el programador. Es un lenguaje interpretado, es decir, no requiere compilar, ni enlazar a comparación de otros lenguajes, permitiendo que las variables obtengan un tipado dinámico. Gracias a su gran capacidad de manejo de datos, tendencias como la Inteligencia Artificial, ciencia de datos e internet de las cosas han utilizado esta herramienta para su progresivo desarrollo.

*4.2.1. Conceptos básicos*

Comentarios

Es un texto en la cual la consola ignora cuando está siendo ejecutada.

Creación de variables

Son tres datos que maneja Python: numéricos, cadenas de caracteres (string) y booleanos.Para crear un dato, se debe asignar una letra o palabra con cualquiera de esos tres datos por medio del signo =.

Salida de datos

Para ello se implementa el comando print(). Para mostrar el valor de las variables se debe escribir el nombre de la variable dentro de él.

Entrada de datos

Es el medio en la cual los valores de las variables se asignan cuando el usuario ingresa datos al teclado en el momento de la ejecución del programa. Se utiliza el comando input(), donde el argumento debe contener un mensaje que permita al usuario conocer el dato que está ingresando.

*4.2.2. Operadores*
- Aritméticos: suma, resta, multiplicación, división, módulo y potencia.
- Relacionales: >, >=, <, <=, ==, =.
- Lógicos: AND, OR y NOT.
- Asignación: operaciones recursivas.

*4.2.3. Condicionales*
- If: condición principal
- Elif: condición alterna
- Else: condición contraria a las anteriores

*4.2.4. Cíclos*
- While: ejecuta las instrucciones tantas veces mientras la condición sea verdadera.
- For: ejecuta las instrucciones en un rango de números.

*4.2.5. Funciones*

Se definen como un conjunto de instrucciones que se ejecutan cuando son llamadas desde parte principal del programa. Su ventaja es especializar ciertas instrucciones mejorando su optimización ya que se puede reutilizar en otras partes del código. Para definirlas se declaran con def(), donde sus argumentos van en el paréntesis. Después de ello, solo falta invocarlas.

*4.2.6. Librerías*

En informática, una biblioteca o, llamada por vicio del lenguaje librería es un conjunto de implementaciones funcionales, codificadas en un lenguaje de programación, que ofrece una interfaz bien definida para la funcionalidad que se invoca.

**4.3 Librería GPIO**

*4.3.1. Pines GPIO*

Es un sistema de entrada y salida de propósito general, es decir, consta de una serie de pines o conexiones que se pueden usar como entradas o salidas para múltiples usos. Estos pines están incluidos en todos los modelos de Raspberry Pi.

**Imagen 3**

Existen 2 formas de numerar los pines de la Raspberry Pi, en modo GPIO o en modo BCM.
- En el modo GPIO, los pines se numeran de forma física por el lugar que ocupan en la placa (representados por el color gris) viene siendo igual para todas las versiones (comenzamos a contar desde arriba a la izquierda y finalizamos abajo a la derecha).
- En el modo BCM, los pines se numeran por la correspondencia en el chip Broadcom (que es la CPU de la Raspberry Pi).

**Imagen 4**

*4.3.2. Librería GPIO*


**5. DIAGRAMAS**

Un ejemplo sencillo de la implementación de la librería GPIO para la ejecuciób del programa en Python.
**Imagen 5**

**6. LISTA DE COMPONENTES**
- Raspberry Pi
- Create with Code

**7. EXPLICACIÓN DEL CÓDIGO FUENTE**
En este punto vamos a detallar un poco sobre la estructuración del código, mas no en el funcionamiento y ejecución del mismo, si desea revisar sobre el funcionamiento del código para ello revisar el manual de usuario que se encuentra aproximación en el siguiente punto. 

Al utilizar Python en la Raspberry Pi tenemos la ventaja de poder utilizar los pines GPIO para conectar el mundo digital con el mundo físico mediante la electrónica y programación.

Debido a que no se cuenta con el sistema operativo de Raspbian donde podamos simular en Python, swe programará en “Create with Code” que es una plataforma online para programar como si se lo hiciera en Python.

*7.1 Programación de un Led Intermitente en Raspberry interpretando el envío y salida de datos*

En nuestro código implementado presentado a continuación detallaremos el comportamiento de cada línea.

**Figura 6**

1. En nuestra primera línea de código importamos la librería GPIO, está librería es la que nos permite utilizar las funciones para controlar los pines de nuestra Raspberry Pi. Además, se debe importar la librería time, esta nos permite controlar el tiempo y la frecuencia con la que el LED se prende y apaga.

**Figura 7**

2. Esta línea de código presentada, la función setmode nos permite definir los pines de la Raspberry Pi, es decir que pines son los pines de reciben los datos y cuáles los que envían.

**Figura 8**

3. Nuestra cuarta línea de código, es donde vamos a definir a un pin cualquiera como entrada o salida con la función setup, en este caso decimos que el pin 7 va a ser definida como nuestra salida.

**Figura 9**

4. Nuestra quinta línea es donde definimos la función setup que sirve para definir a mi pin si será entrada o salida. Esta vez lo hemos definido al pin 5 como entrada.

**Figura 10**

5. Nuestro bucle While es donde vamos a manejar todo el control sobre nuestros pines ya antes definidos, decimos que mientras sea verdad se ejecute nuestro código, es decir en todo momento estará esté actuando.

**Figura 11**

6. En la séptima y octava línea de código usamos la función output indicando el pin que habíamos seleccionado como salida anteriormente,poniendo True para que nuestra salida envíe la información correspondiente en el tiempo definido por la función time.

**Figura 12**

7. En la novena y décima Similar a la anterior situación,En la  línea de código usamos la función output indicando el pin que habíamos seleccionado como salida anteriormente,poniendo False para enviar otra información cuando se cumpla esta condición en el tiempo ya definido por nuestra función time.

**Figura 13**

8. Después de haber enviado la información cualquiera mediante nuestro pin número 7 considerado como salida, necesitamos que esta información sea recibida por alguien, por lo tanto esta información asignamos a una variable, que en nuestro caso es “a”, es decir es la variable  quien recibe la información enviada por el pin 7, por lo tanto necesitamos un pin que reciba la información, al cual hemos denominado como el pin 5 que mientras sea Verdadero recibirá la información enviada correspondiente.

**Figura 14**

9. Por último, mostraremos por pantalla la información recibida por el pin 5, cómo fue validado por verdadero(True),quiere decir que cuando cumpla, este nos imprimirá un 1 por pantalla,caso contrario 0.

 **Figura 15**
 
**8. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN**

Para poder ejecutar de manera eficiente y sin ningún tipo de inconveniente se debe tener los siguientes componentes.
- Computadora, sea de escritorio o portátil, con acceso a internet. 
- La dirección de la página web create.withcode, la cual es la siguiente. https://create.withcode.uk/
- Tener conocimiento previo acerca del funcionamiento de los comandos en el lenguaje programación Python.

**9. CONCLUSIONES**
- Se concluye que se puede enviar y leer datos en la Raspberry mediante la programación de sus pines en created.withcode.uk a través de la definición de cada uno de estos, asignándoles como salidas o entradas de datos.
- La librería GPIO nos permitió manejar la información en los pines de la Raspberry Pi logrando controlar cualquier actuador externo.
- Se concluye que se necesita tener conocimientos básicos de programación para un mejor entendimiento de los códigos, además saber claramente el funcionamiento de los atributos y funciones que posee la librería GPIO. 


**10. RECOMENDACIONES**
- Se recomienda saber la numeración y ubicación de los pines de la Raspberry Pi para asignar correctamente que pines utilizar como transmisores o receptores de información.
- La librería GPIO es una librería muy amplia y necesaria cuando se requiere utilizar los pines de la Raspberry Pi, por lo tanto se recomienda investigar más acerca de los atributos y funciones que contiene esta librería.
- Previamente a utilizar la Raspberry Pi, se recomienda aprender el lenguaje de programación Python utilizando los varios recursos encontrados en el internet.

**11. CRONOGRAMA**

**12. BIBLIOGRAFÍA**

Mischie, S., Matiu-Iovan, L., & Gasparesc, G. (2018). Implementation of Google Assistant on Rasberry Pi. 2018 13th International Symposium on Electronics and Telecommunications, ISETC 2018 - Conference Proceedings, 1–4. https://doi.org/10.1109/ISETC.2018.8583899

Mustaffa, I. B., & Khairul, S. F. B. M. (2018). Identification of fruit size and maturity through fruit images using OpenCV-Python and Rasberry Pi. Proceeding of 2017 International Conference on Robotics, Automation and Sciences, ICORAS 2017, 2018–March, 1–3. https://doi.org/10.1109/ICORAS.2017.8308068

Kumar, A., & Panda, S. P. (2019). A Survey: How Python Pitches in IT-World. Proceedings of the International Conference on Machine Learning, Big Data, Cloud and Parallel Computing: Trends, Prespectives and Prospects, COMITCon 2019, 248–251. https://doi.org/10.1109/COMITCon.2019.8862251
 
RASPBERRY PI – Historia de la Informática. (19 de 07 de 2020). Obtenido de RASPBERRY PI – Historia de la Informática: https://histinf.blogs.upv.es/2013/12/18/raspberry-pi/

