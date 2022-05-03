# Proyecto CapStone UTNG
[![Contribuidores][contribuidores-shield]][contributors-url]

## contenido
<details>
  <summary>Tabla contenidos</summary>
  <ol>
    <li>
      <a href="#acerca-del-proyecto">Acerca Del Proyecto</a>
      <ul>
        <li><a href="#construido-con">Construido Con</a></li>
      </ul>
    </li>
    <li>
      <a href="#iniciando">Iniciando</a>
      <ul>
        <li><a href="#requisitos">Prerrequisitos</a></li>
        <li><a href="#instalacion">Instalación</a></li>
      </ul>
    </li>
    <li><a href="#uso">Uso</a></li>
    <li><a href="#guias">Guias</a></li>
    <li><a href="#contribucion">Contribución</a></li>
    <li><a href="#licencia">licencia</a></li>
    <li><a href="#contacto">Contacto</a></li>
    <li><a href="#participantes">Participantes</a></li>
  </ol>
</details>

<!-- Acerca del proyecto -->
## Acerca del proyecto

### Nombre del proyecto
**Smart Ventas para el comercio de Talavera Dolores Hidalgo**

### Justificación del proyecto

> El mejor servicio al cliente que podemos tener, es no tener la necesidad de usar el servicio al cliente.

> El servicio al cliente bajo la óptica del Internet de las Cosas se vuelve una actividad esencial, automática, proactiva y constante. El mejor servicio al cliente es aquel que logramos canalizar antes de que los clientes noten el problema; y para ello, necesitas potenciar tus operaciones y flujos de trabajo.

> Dolores Hidalgo se encuentra en la zona norte del estado de Guanajuato, pocas ciudades del país pueden decir que viven completamente de la artesanía. En Dolores Hidalgo, Guanajuato, encontrarás calles repletas de todo tipo de objetos cerámicos. Además de ser cuna de la Independencia Nacional, Dolores Hidalgo es una población fantástica donde innumerables alfareros y ceramistas han hecho de la cerámica de talavera su forma de vida al trabajarla en diversas formas (algunas caprichosas) y tonos multicolores que engalanan al México popular país con un hondo espíritu folclórico.
> El principal turista de ocio que llega a la Cuna de la Independencia, es de tipo familiar por el potencial que tenemos en el personaje de José Alfredo Jiménez y la cerámica tipo Talavera, pero una de los grandes incovenientes es que el turista dura en la ciudad de uno a dos días y después se van a otras ciudades como Guanajuato, San Miguel de Allende, San Luis de la Paz. Generalmente, los pequeños comercios que comercializan los productos de Talavera contratan al personal femenino para el servicio de atención al cliente, pero una de las grandes inquietudes que tienen los empresarioss de los estos comercios es usar la tecnología para atrapar al turista e  incrementar sus ventas. 

### Objetivo del proyecto: 

> Impulsar el incremento de  ventas de los pequeños comercios de comercializan Talavera y Cerámica mediante el uso de la tecnología del Internet de las Cosas.

### Descripción general del proyecto

> Este proyecto consiste generar un prototipo que propone incrementar ventas en los comercios de Talavera a través del análisis de datos tomados por los sensores, en el momento que un cliente o turista ingresa al establecimiento.


### Material de uso:

<table> <tr> <th>Componente</th><th>Imagen</th><th>Descripción</th><th>Cantidad</th></tr>
  <tr>
    <td>Raspberry Pi 4</td>
    <td>
    <img src="https://user-images.githubusercontent.com/36056832/165995675-da53df0d-9c67-46af-94e3-22f30ad2aa4d.png" alt="Raspberry Pi 4" width="100"/>
    </td>
     <td><ul><li>Raspberry Pi 4 Modelo B 8GB RAM Original Uk.<li>Memoria microSD 32GB Clase 10 A1 con adaptador.<li>Cable microHDMI a HDMI 1.5m.<li>Carcasa con soporte para ventilador.<li>Ventilador 5VDC con tornillos y tuercas.<li>Fuente 5V 3A USB-C con Switch On/Off.<li>Kit de disipadores de calor cobre y aluminio con cinta térmica adherible.</ul></td>
    <td>1</td>
  </tr> 
  <tr>
    <td>ESP32 Cam</td>
    <td>
    <img src="https://user-images.githubusercontent.com/36056832/165996397-e9527b13-6ad4-4e73-a732-7721e0ffac59.png"  alt="ESP32 Cam" width="100"/>
    </td>
    <td><ul><li>Voltaje: 5 V<li>CPU de 32 bits de doble núcleo de baja potencia para procesadores de aplicaciones<li>Frecuencia principal de hasta 240 MHz<li>Potencia de cálculo de hasta 600 DMIPS<li>SRAM integrado de 520 KB<li>PSRAM externo de 4 M<li>Es ideal para interfaces como: UART. SPI. I2C. PWM. ADC. DAC<li>Soporta cámaras OV2640 y OV7670 (flash incorporado)<li>Apoyo imagen WiFi subir<li>Apoyo TF tarjeta</ul></td>
    <td>1</td>
  </tr> 
  <tr>
    <td>Display LCD 16x2</td>
    <td>
    &nbsp;
    </td>
    <td>
      <ul>
        <li>Voltaje: 5 V</li>
        <li>Un pin de selección de registro (RS) que controla en qué parte de la memoria de la pantalla LCD está escribiendo datos. </li>
        <li>Un pin de lectura/escritura (R/W) que selecciona el modo de lectura o el modo de escritura</li>
        <li>Un pin Habilitar que permite escribir en los registros</li>
        <li>8 pines de datos (D0 -D7) . Los estados de estos pines (alto o bajo) son los bits que estás escribiendo en un registro cuando escribes, o los valores que estás leyendo cuando lees,</li>
      </ul>
    </td>
    <td>1</td>
  </tr> 
  <tr>
    <td>
    </td>
  </tr>

</table>

#### Requerimientos
<table>
  <tr>
    <th>No.</th>
      <th>Requerimiento</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Medición de variables a partir de sensores de temperatura, humedad, PH, lluvia, luminosidad.</td>
  </tr>
  
  <tr>
    <td>2</td>
    <td>Almacenamiento de datos de manera continua y permanente.</td>
  </tr>
  
  <tr>
    <td>3</td>
    <td>Graficar los datos almacenados para su análisis en línea</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Activar el riego automatizado de acuerdo al analisis de datos.</td>
  </tr>
  
  <tr>
    <td>5</td>
    <td>Control a partir de aplicación móvil de riego, sombra y protección.</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Notificar alertas a partir del estado de las variables que involucren un riesgo para la planta.</td>
  </tr>
</table>

#### Diagrama inicial

![image](https://user-images.githubusercontent.com/96089377/165986643-432dfef7-ffff-4755-a768-ecdb5e8252b4.png)

### Prototipo de pared verde


<!-- Construido con -->


<!-- Construido con -->
### Construido con
Construido con.

<!-- Iniciando -->
## Iniciando
Iniciando.

<!-- Requisitos -->
### Requisitos
Requisitos.

<!-- Instalación -->
### Instalacion
Instalación.

<!-- Uso -->
### Uso
Uso.

## Guias
Guias.

## contribucion
Contribucion.

## Licencia
Licencia.

## Contacto
Contacto.

## Participantes
* [Gerardo Reyna Ibarra]()
* [Anastasio Rodríguez García]()
* [Gabriel Barrón Rodríguez]()

[contribuidores-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
