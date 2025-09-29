Diseño e implementación de un controlador PID analógico para un sistema de tercer orden que modela el comportamiento de una turbina eólica. Las ganancias del controlador (Kp, Ki, Kd) se ajustan en tiempo real mediante potenciómetros digitales, controlados desde una interfaz gráfica de usuario (GUI). El controlador permite a la turbina seguir una referencia de velocidad constante, con respuesta ajustable según los parámetros del PID.

En las siguientes imagenes se muestra el esquematico del circuito que modela la turbina y su respuesta al impulso:

<img width="1139" height="496" alt="image" src="https://github.com/user-attachments/assets/786ff2f7-df91-4773-a5d1-4959e20bb4c3" />

<img width="1314" height="591" alt="image" src="https://github.com/user-attachments/assets/0aadc1ab-2532-4562-ac88-7f386e906aaf" />

Después de construir el circuito se obtuvo la siguiente respuesta al escalón unitario:

<img width="1292" height="774" alt="image" src="https://github.com/user-attachments/assets/c04375ca-c6c7-4471-8e2a-606786f1781c" />

Se implemento el controlador PID análogo el cual se observa en el siguiente esquema:

<img width="1682" height="655" alt="image" src="https://github.com/user-attachments/assets/68f2c725-d2ea-4642-8c64-b986d0a39cf2" />

Con el circuito anterior se procedieron a realizar diferentes pruebas variando las ganancias de controlador. Para ver los resultados obtenidos consultar el informe.
