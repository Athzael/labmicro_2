# Descripcion
- El ADC tienene una resolcuion igual a 10 bits.
- Es de aproximaciones sucesivas.
![](https://cdn-reichelt.de/bilder/web/xxl_ws/B300/ARDUINO_UNO_A06.png)


# EXAMEN INSTITUCIONAL DE MICROCONTROLADORES.
# NOMBRE : Francisco Athzael Flores Meza                                                           .
Instrucciones: Contestar las siguientes preguntas y enviar el archivo en PDF en TEAMS, donde vendrá una carpeta llamada INSTITUCIONAL, fecha límite jueves 8 de agosto antes de las 23:59.
#Sección 1

# 1. ¿Cuántos puertos tiene el microcontrolador ATMEGA328P?
   - El ATMEGA328P tiene tres puertos: PORTB, PORTC y PORTD.

# 2. ¿Cuál es la diferencia entre el microcontrolador y la tarjeta de desarrollo Arduino?
   - El microcontrolador, como el ATMEGA328P, es un componente que contiene una CPU, memoria y periféricos. La tarjeta de desarrollo Arduino es una plataforma que incluye un microcontrolador (como el ATMEGA328P) junto con otros componentes necesarios para facilitar la programación, la conexión a periféricos y la alimentación eléctrica.

# 3. ¿Cuántos volts entrega cada pin de los puertos?
   - Cada pin de los puertos del ATMEGA328P entrega 5 volts en estado alto (HIGH) y 0 volts en estado bajo (LOW).

# 4. ¿Cuánta corriente entrega cada uno de los pines de los puertos del microcontrolador?
   - Cada pin puede entregar un máximo de 40 mA, pero la corriente total de todos los pies juntos no debe superar los 200 mA.



# 5. Se necesita conectar dos LEDs, para lo cual se van a utilizar los pines 0 (cero) y 7 (siete) del microcontrolador (PUERTO D), escribe el número en binario y hexadecimal que se le tiene que escribir al puerto para encenderlos.
   - Para encender los LEDs en los pines 0 y 7 del PUERTO D:
     - Binario: 10000001
     - Hexadecimal: 0x81

# 6. ¿Qué es una localidad de memoria en el microcontrolador?
   - Una localidad de memoria es una dirección específica en la memoria del microcontrolador donde se puede almacenar y acceder a los datos.

# 7. ¿Cuál es la capacidad del microcontrolador para la memoria de programa?
   - La capacidad de la memoria de programa (flash) del ATMEGA328P es de 32 KB.

# 8. ¿Cuál es la capacidad del microcontrolador para la memoria de datos?
   - La capacidad de la memoria de datos es de:
     - 2 KB de SRAM
     - 1 KB de EEPROM

# 9. ¿Cuál es la diferencia entre la arquitectura Harvard y Von Neumann?
   - **Arquitectura Harvard:  Tiene memorias y buses separados para instrucciones y datos, lo que permite un acceso simultáneo.
   - **Arquitectura Von Neumann: Utiliza la misma memoria y bus para instrucciones y datos, lo que puede provocar cuellos de botella en el acceso.

# 10. ¿De cuantos bits es el microcontrolador ATMEGA328P?
  El ATMEGA328P es un microcontrolador de 8 bits

# 11. ¿De cuantos bits es el ADC del microcontrolador? 
  El ADC del ATMEGA328P es de 10 bits.

# Sección 2

# 12. Se requiere controlar un motor DC, para lo cual se debe conectar directamente el motor a la tarjeta Arduino UNO para hacerlo funcionar.
CIERTO  FALSO    NO SE  
R= FALSO ya que no se debe conectar un motor DC directamente a la tarjeta Arduino UNO ya que puede exceder la corriente que los pines pueden manejar. Se necesita un controlador de motor o un transistor para manejar la corriente y así poder que realice su tarea de la forma deseada.

# 13. Necesito conectar un LED a la tarjeta Arduino UNO, ¿es necesario forzosamente poner una resistencia a tierra?
   SI  NO    
R= SI Es necesario colocar una resistencia en serie con el LED para limitar la corriente y evitar dañar tanto el LED como el pin del microcontrolador aunque se puede hacer no serviría de nada ya que encendería por unos pocos segundos y se quemaría el pin del Arduino o el led

# 14. Describe los comandos del git flow básico para subir archivos al repositorio de GIT. 
  1. git add (Añade todos los archivos al área de preparación)
  2. git commit -m "Descripción del cambio"` (Confirma los cambios con un mensaje descriptivo)
  3. git push origin máster (Sube los cambios al repositorio remoto en la rama especificada)


# Sección 3

# 1. ¿Qué es una señal?
   - Una señal es una variación de una cantidad física que transmite información. Puede ser eléctrica, óptica, acústica, entre otras.

# 2. ¿Sería posible procesar una señal sin recurrir al muestreo?
   - No, para procesar una señal analógica en un sistema digital, es necesario muestrearla para convertirla a una forma digital.

# 3. ¿Por qué se debe muestrear una señal?
   - Se debe muestrear una señal para convertirla de analógica a digital, lo cual permite su procesamiento mediante dispositivos y algoritmos digitales.

# 4. ¿Cómo relacionas el tamaño de paso del microcontrolador con los números binarios?
   - El tamaño de paso del microcontrolador se refiere a la cantidad de bits que puede manejar simultáneamente. En un microcontrolador de 8 bits, cada instrucción o dato procesado está en formato binario de 8 bits.

# 5. ¿Cuál crees que sea la diferencia entre lo análogo y lo digital?
   - Lo análogo representa valores continuos y puede tomar cualquier valor dentro de un rango, mientras que lo digital representa valores discretos y solo puede tomar valores específicos dentro de un rango, típicamente representados en formato binario.
