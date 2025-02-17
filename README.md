Introducción
 Una tienda de frutas y verduras ("Fruber") necesita un sistema de caja
 registradora que permita gestionar la venta de productos de manera
 sencilla y eficiente. El sistema debe estar desarrollado en Python,
 utilizando la biblioteca Tkinter para la interfaz gráfica. Además, debe
 manejar excepciones y organizar el código en múltiples archivos
 para una mejor estructuración

 Objetivos
 Desarrollar una aplicación de escritorio que permita:
 Seleccionar productos desde una lista.
 Especificar la cantidad a comprar.
 Verificar la disponibilidad del producto antes de añadirlo a la
 compra.
 Calcular el total de la compra en tiempo real.
 Registrar el historial de ventas y mostrarlo en pantalla.
 Gestionar correctamente la actualización del stock de productos.

 Requisitos de Software
 Lenguaje de Programación y Librerías
 Python 3.x (versión recomendada: 3.8 o superior).
 Tkinter (para la interfaz gráfica).
 ttk (Themed Tkinter Widgets) para mejorar la apariencia.

 Estructura del Código
 El proyecto debe estar organizado en múltiples archivos de la
 siguiente manera:
 main.py → Archivo principal que ejecuta la interfaz gráfica.
 productos.py → Contiene los productos disponibles y sus atributos
 (nombre, precio y stock).
 operaciones.py → Implementa funciones auxiliares como
 agregar
 productos y calcular el total.
 excepciones.py → Módulo para manejar errores y excepciones.

 Requisitos Funcionales
 1. Interfaz gráfica con Tkinter
 La ventana principal debe mostrar:
 Una lista de productos con su nombre, precio y cantidad
 disponible.
 Un campo de entrada para seleccionar la cantidad.
 Botones para agregar productos al carrito, finalizar la compra y
 ver el historial de ventas.
 Una sección donde se vea el total acumulado de la compra.

 Requisitos Funcionales
 1. Interfaz gráfica con Tkinter
 La ventana principal debe mostrar:
 Una lista de productos con su nombre, precio y cantidad
 disponible.

 2. Selección y compra de productos 
 Un campo de entrada para seleccionar la cantidad.
 Botones para agregar productos al carrito, finalizar la compra y
 ver el historial de ventas.
 Una sección donde se vea el total acumulado de la compra

 3. Finalización de compra y recibo
 Al presionar "Finalizar Compra", se debe mostrar un mensaje con
 el resumen de la compra.
 Los productos comprados deben agregarse al historial de ventas.
 Se debe limpiar el carrito de compras después de finalizar la
 compra. 

 4. Historial de ventas 
 Nombre del producto.
 Cantidad vendida
 Precio total de cada venta
 Al presionar "Ver Historial de Ventas", se debe abrir una
 ventana con una tabla que muestre:
 También se debe mostrar la ganancia total acumulada

 Manejo de Excepciones
 El sistema debe manejar adecuadamente los errores para evitar
 bloqueos o
 cierres inesperados. Algunas validaciones incluyen:
 Evitar la selección de productos sin especificar cantidad.
 Evitar ingresar valores no numéricos en el campo de
 cantidad.
 Controlar que no se puedan comprar más unidades de
 las disponibles.
 Mostrar mensajes de error en caso de operaciones
 incorrectas.

