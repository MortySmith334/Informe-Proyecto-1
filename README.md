# Informe-Proyecto-1
-Aguirre Johan

-Calahorrano Sarahi

-Lara Melany

1. OBEJTIVOS

  * Objetivo General:
    
    - Demostrar la función del potenciómetro y el transistor bipolar, mediante la elaboración de un circuito, el cual nos permitirá regular la intensidad de la luz de un diodo LED, además de controlar el encendido y el apagado del LED utilizando un fotorresistor el cual detectará el paso de luz o a su vez no detectará nada. 
    
  * Objetivos Específicos:

    - Verificar el funcionamiento de un transistor de unión bipolar en corriente directa
    - Conocer su composición, y su funcionamiento
    - Comprender la función de una fotorresistencia y el proceso que realiza
    
2. MARCO TEÓRICO

  TRANSISTOR BIPOLAR NPN 2N 3904 
  
   - Está diseñado para funcionar a bajas intensidades, bajas potencias, tensiones medias, y puede operar a velocidades razonablemente altas. 
   - Es activado por corriente positiva polarizada en la base para controlar el flujo de corriente del Colector al Emisor

  DIODOS LED 
   
  -	Es una fuente de luz que emite fotones cuando se recibe una corriente eléctrica de muy baja intensidad.
  - La terminal positiva, o ánodo, por lo general es la más larga de las dos terminales, algunos diodos leds tienen una base plana que sirve para identificar la terminal negativa, o cátodo.
  - Es importante recordar que un LED tiene una caída de voltaje de 1.5 a 2.5V al ser polarizado directamente

  FOTO RESISITENCIA

   - Su componente principal, el sulfuro de cadmio.
   - La composición química es un semiconductor que puede cambiar su resistencia según la cantidad de luz irradiada sobre él.
   - Cuanto mayor sea la intensidad de la luz que incide sobre el sulfuro de cadmio, menor será la resistencia.

  POTENCIOMETRO DE 100K
  
   - Es una resistencia de tres terminales con un contacto deslizante o giratorio que forma un divisor de tensión ajustable. 
   - Utilizado para medir el potencial eléctrico, habitualmente para controlar dispositivos eléctricos, como los controles de volumen de los equipos de audio.
   
   FUENTE DE ALIMENTACION
  
   - Es un componente esencial de cualquier dispositivo electrónico ya que es ella quien se encarga de darle vida. En cualquier equipo, por pequeño que sea, siempre hay una FA.
   
3.	EXPLICACIÓN DEL PROCEDIMIENTO

   3.1.  MATERIAL Y EQUIPO REQUERIDO
   
   - Transistor Bipolar NPN 2N 3904
   - Diodos Led
   - Foto resistencia 
   - Potenciómetro de 100K
   - Resistencia 220 ohmios
   - Resistencia 10kohmios
   - Fuente de Alimentación 9V
   
   3.2.  PROCEDIMIENTO
   
   ![image](https://user-images.githubusercontent.com/105056762/204443991-12b45d67-4797-4ffb-bfc7-345c0029ec46.png)

   - En el protoboard, el transistor se polariza a negativo en su pin emisor, en el colector se conecta dos diodos led con una conexión en serie, hasta llegar al positivo mediante una resistencia de 220Ω 
   - Se desactiva constantemente el transistor por su base, usando una foto celda o foto resistencia conectada hacia negativo, ya que el transistor se activa por una señal positiva.
   - Se envía una señal positiva mediante un potenciómetro de 100k y una resistencia de 10kΩ , la línea azul se le considera como positivo principal y la roja como positivo de los leds
   - Se conecta la resistencia y el potenciómetro en serie, hasta llegar a la base del transistor desde el pin medio del potenciómetro.
   - Se conecta la resistencia de 220Ω a los led´s, se alimenta el circuito con 9 v
   - La fotocelda al recibir luz, mantendrá apagado al transistor, pero al momento de obstruir la luz, su valor subirá, permitiendo pasar la señal positiva de las resistencias al transistor activando los led´s 

   I) SIMULAR EL CIRCUITO EN EL SOFTWARE TINKERCAD
   
   ![image](https://user-images.githubusercontent.com/105056762/204444184-646afc81-cefb-44c6-8ac5…
