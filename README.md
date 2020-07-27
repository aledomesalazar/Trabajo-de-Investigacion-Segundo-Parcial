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

Actualmente existen 2 modelos diferentes de Raspberry Pi. 
