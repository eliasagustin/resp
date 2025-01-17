## De que se trata
La iniciativa del proyecto es presentar la realización de un asistente respiratorio de emergencia como una solución alternativa, rápida y económica; ante una posible crisis en el sistema sanitario nacional Argentino.

Por lo que se prenseta esta idea como económica debido a que el dispositivo no supera el valor de los 15000 pesos en la suma de todos sus componentes necesarios; además de que estos son de facil acceso para su compra, a pesar de la cuarentena. Y rápida teniendo en cuenta la fabricacion de sus piezas con impresión 3d sumado a la gran cantidad de gente solidaria en la comunidad de impresion 3d.

Esto se desarrollo luego de estudiar y probar con diferentes sistemas mecánicos con "engranajes impresos" lo que se traduce en mucho ruido y calor; o sistemas de donde se requería mucho torque, al final pude encontrar esta solución realizada por Sebastian Gaggino [Sebastian Gaggino](https://github.com/SebaGaggino/rees31) que usa un sistema de poleas para la distribución de la fuerza ejercida a los laterales del ambu.


<br />
<div align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/pcKIJMWP4SA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<br />
<br />

## El Modelo utilizado

<div align="center">
<img src="Modelo1.png" alt="hi"  width="800" class="inline"/>
</div>
<br />
Como ya mencioné arriba, realice unas pequeñas variaciones al modelo de Sebastian Gaggino
<br />
[Descarga de STLs](repirador31_V5.rar "Descarga del Modelo")

## Esquema de conexiónes

<div align="center">
<img src="EsquemaV1.png" alt="hi"  width="800" class="inline"/>
</div>
<br />
<br />

## Estado del Proyecto

Resumen de desarrollo respecto a las características:<br />
Sistema mecánico para la compresión de un Ambu ------- Listo<br />
Motor de gran torque y funcionamiento continuo -------- Listo<br />
Controlador/Fuente para abastecer el motor -------------- Listo<br />
Electrónica general de sistema ----------------------------- Lista<br />
Interfaces del sistema para setear parámetros ------------- Fase Intermedia<br />
&nbsp;&nbsp;&nbsp;Frecuencia de compresión -------------------------------- Lista<br />
&nbsp;&nbsp;&nbsp;Amplitud de compresión ---------------------------------- a desarrollar<br />
&nbsp;&nbsp;&nbsp;Proporción entre inhalación y exhalación -------------------- a desarrollar<br />
&nbsp;&nbsp;&nbsp;Acción de inhalación y exhalación por demanda -------- a desarrollar<br />
Instalación de sensor de presión diferencial ---------------- No empezada<br />


## Materiales Utilizados
<br />

### Fuente Switching 12v 5a
proximamente 24v 5a para usar otro Motor mas grande que el del video
<br />
<img src="fuente12_5a.webp" alt="hi"  width="200" class="inline"/>

### Driver Modular Tb6600 4a Motor Paso A Paso 42v
<br />
<img src="driver.webp" alt="hi"  width="200" class="inline"/>

### Motor Nema23
proximamente Nema24 de muy Alto Torque
<br />
<img src="motor-paso-a-paso-nema-23.webp" alt="hi"  width="200" class="inline"/>

### Modulo Lm2596 Hvs Step Down In 52v Out 4.5-32v
<br />
<img src="modulo-lm2596-hvs-step-down-in-52v-out-45-32v.webp" alt="hi"  width="200" class="inline"/>

### Display Lcd 2004 Backlight Azul 20x4 + Serie I2c
<br />
<img src="display-lcd-2004-backlight-azul-20x4-serie-i2C.webp" alt="hi"  width="200" class="inline"/>

### Encoder Rotativo Ky-040 - 20 Pasos X Vuelta
<br />
<img src="encoder-rotativo-20-pasos-x-vuelta.webp" alt="hi"  width="200" class="inline"/>

### Switch Final Carrera 
<br />
<img src="switch-final-carrera.webp" alt="hi"  width="200" class="inline"/>

### Filamento PetG
<br />
<img src="filamento-petg.webp" alt="hi"  width="200" class="inline"/>

### Barra rectificada 8mm
Dos barras de 14.5cm
<br />
<img src="barra.webp" alt="hi"  width="200" class="inline"/>

### Rodamiento SKF R3zz
2 Rodamientos R3zz que son en pulgadas, la medida interna es de 4.76mm y externa 12.7mm espesor de 4.98mm
<br />
<img src="R3zz.webp" alt="hi"  width="200" class="inline"/>

<br />
<div align="center">
<b>Cualquier aporte de modificación en el codigo y/o diseño mecánico es mas que bienvenido.</b> 
<br />
<strong>eliasagustin@gmail.com</strong>
</div>
