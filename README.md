# TerminalApp con Tkinter y Turtle

Este proyecto es una aplicación de terminal básica que combina la biblioteca Tkinter para la interfaz gráfica de usuario (GUI) y la biblioteca Turtle para dibujar números en la ventana de la aplicación. La aplicación simula una terminal donde los usuarios pueden ejecutar comandos personalizados, como lanzar dados y ver una tabla de clasificación de resultados.

## Funcionalidades Principales

### 1. Interfaz de Usuario con Tkinter
La aplicación utiliza Tkinter para proporcionar una interfaz de usuario intuitiva. La ventana principal incluye un cuadro de texto desplazable para la salida del terminal y un campo de entrada para que los usuarios ingresen comandos.

### 2. Ejecución de Comandos
La aplicación permite a los usuarios ingresar comandos en la terminal. Actualmente, admite dos comandos predefinidos: `rolls` y `table`. El comando `rolls` genera un número aleatorio según probabilidades predefinidas, lo muestra en la salida del terminal y lo dibuja utilizando Turtle. El comando `table` muestra una tabla de clasificación de los números generados previamente.

### 3. Dibujar Números con Turtle
Al ejecutar el comando `rolls`, la aplicación utiliza Turtle para dibujar el número generado en la ventana principal. Los números se representan en un formato ASCII predefinido.

### 4. Manejo de Errores de Comandos
La aplicación maneja errores de ejecución de comandos y los muestra en la salida del terminal.

## Cómo Ejecutar la Aplicación

1. Asegúrate de tener instalado Python 3.x en tu sistema.
2. Ejecuta el script `main.py`.
3. La aplicación abrirá una ventana con la interfaz de usuario. Puedes ingresar comandos en la terminal y ver los resultados en la salida del terminal y en la ventana de Turtle.

## Dependencias

- Python 3.x
- Bibliotecas estándar de Python: tkinter, subprocess, random, turtle.

## Notas Adicionales

- Este proyecto es una implementación básica y se puede ampliar agregando más funcionalidades, como soporte para comandos adicionales, personalización de la apariencia de la ventana, etc.
- La ventana de Turtle se oculta automáticamente después de dibujar un número para evitar interferencias con la interfaz principal. Si deseas mantener visible la ventana de Turtle después de dibujar un número, comenta la línea `turtle.getcanvas().master.withdraw()` en el código.
