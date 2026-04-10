# Los-Grises-WRO-2026

Official repository of Team Los Grises for the **Future Engineers - World Robot O1ympiad 2026**.
<div align="center">
<img width="1000" height="500" alt="team-image" src="https://github.com/RSA967/Los-Grises-WRO-2026/blob/9e32aee27e9ebda8a6da08e632b9680e6d41e43a/LOS_GRISES_1.webp" />
</div>

El código de nuestro robot está dividido en varias partes (módulos) que ayudan a que el robot funcione correctamente y pueda interactuar con el mundo real. Cada módulo tiene una función diferente, pero todos trabajan juntos.
Uno de los módulos más importantes es el de la cámara, donde usamos el sensor "HuskyLens",este sensor funciona como “los ojos” del robot, ya que puede reconocer colores gracias a esto, el robot puede detectar objetos que ya fueron entrenados previamente y obtener información como su posición (X y Y) y su tamaño (ancho y alto).
Otro módulo es el que controla el funcionamiento del programa. Este hace que el robot esté constantemente revisando si detecta algún objeto. También incluye el uso de un botón, que permite detener el programa cuando sea necesario.
También tenemos el módulo de procesamiento de datos. Aquí, el robot toma la información que recibe de la cámara y la guarda en variables. Por ahora, estos datos se muestran en la pantalla, pero después pueden servir para que el robot tome decisiones, como moverse hacia un objeto y/o esquivarlo.
El código se relaciona con los componentes electromecánicos del robot, como los motores, el regulador y los sensores. Los motores permiten que el robot se mueva, y el regulador controla la energía que reciben. Aunque en este código todavía no se controlan directamente los motores, la información de la cámara será utilizada después para decidir cómo moverse.
Para usar el código, primero lo escribimos en el entorno de programación del robot,después se revisa y se compila para asegurarnos de que no tenga errores

Finalmente, se sube al controlador del robot usando un cable USB. Una vez cargado,el robot puede ejecutar el programa y empezar a detectar objetos.
En conclusión este código permite que el robot vea su entorno usando la cámara y es la base para que en el futuro pueda moverse y tomar decisiones automáticamente
