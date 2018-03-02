========================================
Actualización de transacciones de nómina
========================================

Ubicación
=========

:Módulo:
 Nómina

:Grupo:
 Parámetros

:Descripción:
  Actualización de transacciones de nómina

Introducción
============

Use **ESC** para salir de las interfaces principales.

Use las transacciones de nómina para especificar, resolver y describir los proceso que lleva a cabo con respecto al pago de los empleados, incluyendo devengaciones y deducciones. En esta interfaz podrá crear 

Crear una Sección de Nómina
===========================

	- Ejecute la opción *Actualización de transacciones de nómina*

		 .. figure:: images/f/0.jpg
		   :align: center
	- Haga click en el botón |wznew.bmp|


		 .. figure:: images/f/1.jpg
		   :align: center

	- En el campo 'Nombre de la transacción' digite un identificador en palabras para la transacción
	- En el panel 'Valores disponibles para la formulación' verá una lista de variables o constantes que puede usar para crear una formula que determine el resultado de esta transacción. Por ejemplo: La transacción 'Subsidio de transporte' usa la constante: @subsidio_transporte y la divide entre 30. Haga la ecuación en el campo formula.
	- En 'tipo de transacción' escoja si el resultado de la formula será una deducción o una devengación.
	- 'Valor editable' y 'cantidad editable' permite hacer edición del valor antes de la liquidación.

		.. NOTE::

			Si la transacción tiene una formula pre-escrita, su valor será el de la formula, sin importar que lo edite. Hay prioridad por los valores calculados.
			
	- 'Transacción activa' le permite desactivar o activar una transacción para su uso.


		 .. figure:: images/f/1a.jpg
		   :align: center

	- Haga click en |save.bmp|

	**Si desea cancelar la operación haga click en el botón |descartar.bmp|**


Modificar una Sección de Nómina
===============================

	- Ejecute la opción *Actualización de transacciones de nómina*
	- Seleccione una Sección de la grilla
	- Haga click en el botón |edit.bmp|


		 .. figure:: images/f/2.jpg
		   :align: center

	- En el campo de texto *Nombre de la sección* digite el nuevo nombre de la sección
	- Haga click en |save.bmp|

	**Si desea cancelar la operación haga click en el botón |descartar.bmp|**

Eliminar una Sección de Nómina
==============================

	- Ejecute la opción *Actualización de secciones de nómina*
	- Seleccione una Sección de la grilla
	- Haga click en el botón |delete.bmp|


		 .. figure:: images/f/3.jpg
		   :align: center

	- En la ventana de confirmación haga click en 'Sí'


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
