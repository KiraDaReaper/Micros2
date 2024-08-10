# Descripcion
- El ADC tiene una resolucion de 10 bits
- Es de aproximaciones sucesivas

![](https://http2.mlstatic.com/D_NQ_NP_852732-MLM50615744323_072022-O.webp)

### ¿Pregunta?
/ Respuesta


### 1.	¿Cuántos puertos tiene el microcontrolador ATMEGA328P?
- TIene 3
### 2.	¿Cuál es la diferencia entre el microcontrolador y la tarjeta de desarrollo Arduino?
- El microcontrolador es el circuito integrado que puede tener la memoria o cpu y la tarjeta arduino es la placa donde se pone el microcontrolador junto con otros componentes y tiene la ranura usb para implementarle programacion.
### 3.	¿Cuántos volts entrega cada pin de los puertos?
- 5V
### 4.	¿Cuánta corriente entrega cada uno de los pines de los puertos del microcontrolador?
- La maxima coreiente que pueden entregar es de 40mA
### 5.	Se necesita conectar dos LEDs, para lo cual se van a utilizar los pines 0 (cero) y 7 (siete) del microcontrolador (PUERTO D), escribe el numero en binario y hexadecimal que se le tiene que escribir al puerto para encenderlos.
- Binario: 10000001
- hexadecimal: 0x81
### 6.	¿Qué es una localidad de memoria en el microcontrolador?
- Es el lugar especifico en la memoria del micro donde se puede guardar datos o acciones.
### 7.	¿Cuál es la capacidad del microcontrolador para la memoria de programa?
- 32kb
### 8.	¿Cuál es la capacidad del microcontrolador para la memoria de datos?
- Es de 2KB (SRAM) y 1KB (EEPROM).
### 9.	¿Cuál es la diferencia entre la arquitectura Harvard y Von Newmann?
- La arquitectura de Harvard separa la memoria del programa y de datos y la otra de Von utiliza un mismo espacio de memoria para los dos.
### 10.	¿De cuantos bits es el microcontrolador ATMEGA328P?
- 8 bits
### 11.	¿De cuantos bits es el ADC del microcontrolador?
- 10 bits

## Sección 2
Responde cierto o falso.
### 12.	Se requiere controlar un motor DC, para lo cual se debe conectar directamente el motor a la tarjeta Arduino UNO para hacerlo funcionar.
CIERTO                   FALSO         NO SE
- Respuesta: FALSO

### 13.	Necesito conectar un LED a la tarjeta Arduino UNO, ¿es necesario forzosamente poner una resistencia a tierra? 
SI                                NO
- Respuesta: No, pero lo preferible es que si

### 14.	Describe los comandos del git flow básico para subir archivos al repositorio de GIT.
- Te ubicas en la carpeta donde este el archivo, pones el comando “git add (nombre del archivo), despues agregas el comentario: “git commit – m (comentario), y al ultimo: “git push origin master”.

## Sección 3
Reflexiona y responde las siguientes preguntas.
### 1.	Que es una señal.
- Es algo que puede ser en voltake corriente o luz que varia en el tiempo y es fisica.
### 2.	¿Sería posible procesar una señal sin recurrir al muestreo?
- No porque se ocupa convertir la senal analogica a digital para que puesa se procesada.
### 3.	¿Porque se debe muestrear una señal?
- Para convertirla de analogica a digital y que esta ya pueda ser procesada y capturar la informacion por una computadora o microcontrolador 
### 4.	¿Cómo relacionas el tamaño de paso del microcontrolador con los números binarios?
- Por la cantidad de tiempo y de datos que pueden se procesados o almacenados al mismo tiempo.
### 5.	¿Cuál crees que sea la diferencia entre lo análogo y lo digital?
- Los valores analogos suelen ser infinitos y los digitales no y usan binario.
