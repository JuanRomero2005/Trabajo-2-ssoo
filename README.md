TerminalApp con Tkinter y Turtle


Este proyecto es una aplicación de terminal básica que utiliza la biblioteca Tkinter para la interfaz gráfica de usuario (GUI) y la biblioteca Turtle para dibujar números en la ventana de la aplicación. La aplicación permite al usuario ejecutar comandos en una terminal simulada, donde puede rodar dados, ver una tabla de clasificación de los resultados de los dados y ejecutar otros comandos personalizados.

Funcionalidades principales:

Interfaz de usuario con Tkinter: La aplicación utiliza Tkinter para crear una interfaz de usuario intuitiva con una ventana principal que muestra un cuadro de texto desplazable para la salida del terminal y una entrada para que el usuario ingrese comandos.
Ejecución de comandos: La aplicación permite al usuario ingresar comandos en la entrada de la terminal. Actualmente, la aplicación admite dos comandos predefinidos: rolls y table. El comando rolls genera un número aleatorio según ciertas probabilidades predefinidas, lo muestra en la salida del terminal y lo dibuja utilizando la biblioteca Turtle. El comando table muestra una tabla de clasificación de los números generados previamente.
Dibujar números con Turtle: Cuando se ejecuta el comando rolls, la aplicación utiliza la biblioteca Turtle para dibujar el número generado en la ventana principal. Los números se dibujan utilizando un formato ASCII predefinido.
Manejo de errores de comandos: La aplicación maneja errores de ejecución de comandos y los muestra en la salida del terminal.

Cómo ejecutar la aplicación:

Para ejecutar la aplicación, simplemente ejecuta el script main.py. Asegúrate de tener Python instalado en tu sistema. La aplicación abrirá una ventana con la interfaz de usuario. Desde allí, puedes ingresar comandos en la entrada de la terminal y ver los resultados en la salida del terminal y en la ventana de Turtle.

Dependencias:

Python 3.x
Bibliotecas estándar de Python: tkinter, subprocess, random, turtle.

Notas adicionales:

El proyecto es una implementación básica y puede ser extendido agregando más funcionalidades, como soporte para más comandos personalizados, personalización de la apariencia de la ventana, etc.
Actualmente, la ventana de Turtle se oculta automáticamente después de dibujar un número. Esto se hace para evitar que la ventana de Turtle interfiera con la interfaz de usuario principal. Sin embargo, si deseas mantener la ventana de Turtle visible después de dibujar un número, simplemente comenta la línea turtle.getcanvas().master.withdraw() en el código.

