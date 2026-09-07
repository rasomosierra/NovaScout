En este repositorio se encuentran las distintas aplicaciones desarrolladas para el Arduino UNO Q utilizadas en el Robot NOVASCOUT, 
organizadas desde las implementaciones más básicas y funcionales hasta las de mayor complejidad. Todas ellas están diseñadas para 
ejecutarse directamente en Arduino AppLab, facilitando la prueba, evolución y despliegue del software del robot.

1.LEDintermitente, programa básico que apaga y enciende un led.

2. MatrizLED, programa que utiliza la matriz de leds de Arduino Q.
3. 
3.1 Bridge LED parpadea, programa que enciende y apaga un led pero cuando la orden viene desde la parte de Linux del microprocesador utilizando el bridge.
   
3.2 Bridge 1 parámetro, programa para pasar un parámetro utilizando el bridge desde el microcontrolador hacia el microprocesador (parte Linux)

3.3 Bridge 3 parámetros, idem que el anterior programa, pero con tres parámetros.

4.1 Contador pulsos y vueltas encoder, programa para contar los pulsos de los encoders de cuadratura de los motores.

4.2 Distancia recorrida rueda, programa que calcula la distancia recorrida de la rueda utilizando los pulsos de los encoders de cuadratura.

4.3 Velocidad rueda, programa que calcula la velocidad de la rueda, es decir, distancia recorrida en un periodo de tiempo.

4.4 Distancia y velocidad ruedas, programa que calcula la distancia recorrida y velocidad de las dos ruedas.

4.5 Dirección motores, programa que calcula la dirección en la que se mueven los motores utilizando la información de los encoders de cuadratura.

5.1 Odometría encoders, programa que calcula la x,y, theta de la posición del robot.

5.2 Odometría encoders con Bridge, programa que pasa los datos de la posición del robot a la parte de microprocesador para después tratarlos allí.

6.1 QRD1114 Prueba entrada Analógica, programa para probar los sensores ópticos.

6.2 Modulino Distancia, programa para probar el sensor Modulino Distance.

6.3 Sonar URM37 DFRobot, programa para probar el sensor Sonar URM37.

6.4 Sensor Lidar 8x8, programa para probar el sensor Lidar 8x8.

6.5 Todos los sensores juntos, programa en el que funcionan todos los sensores a la vez.

7.1 Odometría, Sensores y Bridge (x,y,z), programa en el que hacemos funcionar la odometría, los sensores y el bridge todo a la vez.

7.2 Recogida de datos en .txt, primera versión del programa que recoge los datos de un sensor y los envía por sockets al ordenador para puedan ser visualizados en pantalla y que sean recogidos en un archivo .txt

7.3 Recogida de datos en .txt Lidar 8x8, programa que recoge los datos del sensor Lidar 8x8 y los envía por sockets al ordenador para que sean recogidos en un .txt 

7.4 Recogida de datos final, programa donde se recogen todos los datos de todos los sensores, odometría y se envía por sockets al ordenador para que sean recogido en un .txt y puedan ser visualizados en tiempo real en pantalla.

8.1.1 Sigue-Lineas, programa donde se realiza el control para que el robot siga una línea de color negro sobre blanco utilizando los sensores ópticos.

8.1.2 Sigue-Lineas mejorado, programa que mejora al anterior y suaviza los movimientos.

8.1.3 Sigue-Lineas con Odometría, programa que envía los datos de odometría al ordenador para después ver el recorrido que ha hecho el robot sobre el circuito sigue-lineas.

8.2 Esquiva obstáculos Sonar URM37, programa donde se realiza un control del sensor Sonar URM37 para que el robot no choque con objetos de su alrededor.

8.4 Sigue Objetos Lidar 8x8, programa donde utilizamos el sensor Lidar 8x8 para localizar un objeto que se mueve de derecha a izquierda delante de el, y el robot sea capaz de seguirlo girando sobre su propio eje.

