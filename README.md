# **EXAMEN PARCIAL- Orlando Ramirez**

## **Descripción**

Aplicación web simple de CRUD (Crear, Leer, Actualizar, Borrar) desarrollada en *HTML, JavaScript, PHP y MySQL*. 

*Tambien contamos con un video en tiempo de ejecucion de la web*

**Su propósito es gestionar una lista de productos, clientes, categorias y facturacion en una base de datos.**

**Estructura de la aplicación**

1. Estructura HTML: Utiliza Bootstrap para el diseño y estilo, y DataTables para la visualización de tablas.
   
3.	Navegación: Una barra de navegación permite acceder a diferentes secciones, como Facturación, Categorías, Clientes y Productos.
   
5.	Consulta de Facturas: En el cuerpo de la página, un script PHP consulta una base de datos para mostrar una lista de facturas emitidas, incluyendo el número de factura, cliente, fecha e importe total.
   
6.	Acciones en la tabla:
   
	•	Imprimir: Botón que abre una nueva pestaña con una versión PDF de la factura seleccionada.

	•	Borrar: Botón que abre un modal de confirmación para borrar la factura seleccionada.

8.	Botón “Nueva Factura”: Redirige al usuario a una página para emitir una nueva factura.
   
10.	Modal de Confirmación de Borrado: Aparece al hacer clic en “Borrar”, confirmando si el usuario realmente desea eliminar la factura.
    
12.	JavaScript/jQuery: Controla la interacción del usuario con la interfaz, como mostrar el modal de confirmación y redirigir según las acciones elegidas.

## **Funcionalidades :**

* CRUD de Productos.

* CRUD de Categorias
  
* CRUD de Clientes

* Facturacion

## **Cómo utilizar**

* Clonar el repositorio y configurar la conexión a la base de datos en conexion.php.

* Ejecutar el archivo para visualizar la lista de artículos e interactuar con las funcionalidades CRUD.
