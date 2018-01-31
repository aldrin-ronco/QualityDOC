===============================================
Definición de Variables y Constantes de Nómina
===============================================

Ubicación
=========

:Módulo:
 Nómina

:Grupo:
 Parámetros

:Descripción:
  Definición de Variables y Constantes de Nómina

Introducción
============

	Las transacciones en nómina pueden incluir variables que, por su naturaleza, son fijas o variantes según el empleado. 

	Por ejemplo, el 'Subsidio de transporte' es una variable **Global** (constante) ya que no varía según el trabajador (se pide el valor una sola vez), mientras que el 'Sueldo básico' es una variable **Personalizada** diferente para cada empleado (su valor se pide en el momento de la operación). 

	Una Variable 'basada en transacciones' es la suma de las operaciones de nómina que se marquen en el momento de su creación.

	Cada variable, sin importar su naturaleza, tiene un identificador con el que podrá crear formulas para los procesos administrativos de nómina.

Crear una variable o constante
==============================

	- Ejecute la opción *Definición de Variables y Constantes de Nómina*
	- En el pie de la ventana haga click en |wznew.bmp| *nuevo*
	- En la ventana emergente, en el campo 'Nombre del parametro' establezca un nombre para su variable
	- En el campo 'Llave del parametro' establezca un identificador que usará a la hora de crear una formula
	- Seleccione si su variable será:
		- **Global:** En este caso, use el campo numérico 'valor del parámetro' para establecer el valor constante de la variable. 
		- **Personalizado:** Una variable personalizada solo tiene un nombre y una llave, su valor es establecido en la pestaña 'Parámetros' de la actualización del empleado. La formula de la variable personalizada debe irvacía.
		- **Basada en transacciones:** Seleccione un 'tipo de transacción' para desplegar la lista de transacciones de nómina. Luego, marque las operaciones de la lista que sumarán para el monto de la variable. 
	- Ha click en |save.bmp| *Guardar*

Modificar una variable
=============================

	- Ejecute la opción *Definición de Variables y Constantes de Nómina*
	- En la grilla haga click sobre la variable a modificar
	- En el pie de la ventana haga click en |wzedit.bmp| *modificar*
	- Modifique lo que considere pertinente
 	- Haga click en |save.bmp| *guardar* o presione la tecla F2
 


Eliminar una variable
============================

	- Ejecute la opción *Definición de Variables y Constantes de Nómina*
	- Seleccione la variable en la grilla, haciendo click sobre ella.
	- En el pie de la ventana haga click en |delete.bmp| *eliminar*
	- Oprima 'Sí' en la ventana de confirmación

.. |export1.gif| image:: /_images/generales/export1.gif
.. |pdf_logo.gif| image:: /_images/generales/pdf_logo.gif
.. |excel.bmp| image:: /_images/generales/excel.bmp
.. |codbar.png| image:: /_images/generales/codbar.png
.. |printer_q.bmp| image:: /_images/generales/printer_q.bmp
.. |calendaricon.gif| image:: /_images/generales/calendaricon.gif
.. |gear.bmp| image:: /_images/generales/gear.bmp
.. |openfolder.bmp| image:: /_images/generales/openfold.bmp
.. |library_listview.bmp| image:: /_images/generales/library_listview.png
.. |plus.bmp| image:: /_images/generales/plus.bmp
.. |wzedit.bmp| image:: /_images/generales/wzedit.bmp
.. |buscar.bmp| image:: /_images/generales/buscar.bmp
.. |delete.bmp| image:: /_images/generales/delete.bmp
.. |btn_ok.bmp| image:: /_images/generales/btn_ok.bmp
.. |refresh.bmp| image:: /_images/generales/refresh.bmp
.. |descartar.bmp| image:: /_images/generales/descartar.bmp
.. |save.bmp| image:: /_images/generales/save.bmp
.. |wznew.bmp| image:: /_images/generales/wznew.bmp
