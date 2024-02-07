# ProyectoCarrito
## Actividad:
Creación de un carrito con Arduino

## Índice
1. [Objetivo General](#objetivo-general)
2. [Objetivos específicos](#objetivos-específicos)
3. [Desarrollo](#desarrollo)
   - [Configuración del Hardware](#configuración-del-hardware)
   - [Montaje Físico del Carrito](#montaje-físico-del-carrito)
   - [Configuración del Software en Arduino](#configuración-del-software-en-arduino)
   - [Desarrollo de la Aplicación Android](#desarrollo-de-la-aplicación-android)
   - [Un plus a nuestro carrito](#un-plus-a-nuestro-carrito)

## Introducción
En la intersección entre la ingeniería y la programación, nuestro equipo de cuatro personas ha dado vida a un proyecto innovador: un carrito controlado por Arduino mediante una aplicación Android desarrollada con Android Studios y conectado vía Bluetooth. Esta fusión de hardware y software no solo destaca la versatilidad de nuestras habilidades, sino que también representa la creación de una solución práctica e intuitiva. A lo largo de este informe, exploraremos los desafíos, procesos y logros que conforman esta emocionante colaboración tecnológica.

## Objetivo General
- Diseñar, construir y demostrar nuestros conocimientos creando un carrito programado con Arduino.

## Objetivos específicos
- Crear un carrito con componentes Arduino para darle funcionalidades extra.
- Utilizar sensor de distancia para identificar la distancia entre el carrito y una obstrucción del camino.
- Creación de una aplicación móvil en Android Studios para poder vincular un módulo bluetooth.
- Uso del módulo HC05 para la conexión a bluetooth.
- Uso de un puente 1298N para el control de las llantas.

## Desarrollo
Para poder lograr este proyecto debemos tener los conocimientos básicos de Arduino, aprender a encender un led por señales que recibe y así, los módulos más importantes en esa actividad son el módulo HC05 y L298N.

### Configuración del Hardware:
- Conectar el módulo HC-05 al Arduino según las especificaciones.
- Configurar el módulo Bluetooth para permitir la conexión desde el dispositivo Android.
- Conectar y configurar el módulo L298N para controlar los motores del carrito.

### Montaje Físico del Carrito:
- Instalar los motores y las ruedas en el chasis del carrito.
- Asegurarse de que las conexiones eléctricas sean sólidas y funcionales.
- Verificar que el carrito pueda moverse en todas direcciones sin obstáculos.

### Configuración del Software en Arduino:
- Desarrollar un código que espere comandos desde el módulo Bluetooth.
- Implementar funciones para controlar el movimiento del carrito según los comandos recibidos.
- Subir el código al Arduino y verificar la comunicación Bluetooth.

### Desarrollo de la Aplicación Android:
- Crear una interfaz de usuario intuitiva con botones de control.
- Programar la lógica para gestionar la conexión Bluetooth con el módulo HC-05.
- Desarrollar funciones que envíen comandos al Arduino según las acciones del usuario.

### Un plus a nuestro carrito
Llegado a este punto el carrito necesitaba un diseño así que escogimos la nave de Rick y Morty.

Entonces la idea que pusimos es que con un sensor de distancia mande una señal y retroceda el carrito unos centímetros para que no colisione y siga el camino.

Para la aplicación también tratamos de tener un diseño o Layout de acuerdo a la temática de nuestro carrito.

Al final el resultado fue favorable, funcional y logramos las competencias que no habíamos planteado.

<p align="center">
    <img src="https://eloctavobit.com/wp-content/uploads/2020/08/conectar-modulo-bluetooth.jpg"/>
  <br>
<br>
