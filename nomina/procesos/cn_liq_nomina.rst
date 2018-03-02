=====================================
Registro de novedades de Nómina
=====================================

Ubicación
=========

:Módulo:
 Nómina

:Grupo:
 Procesos

:Descripción:
  Registro de novedades de Nómina

Introducción
============

 Use esta interfaz para realizar la liquidación de nómina para una quincena (o un mes), una sección, y un centro de costo en específico. La liquidación consiste en el registro en el sistema del pago de nómina, aportes, devengaciones y deducciones.

 La pre-nómina se refiere a todos los parámetros establecidos antes de llegar a esta interfaz que se mantienen constantes en el tiempo.

 Usted puede cambiar, en su mayor parte, los montos que rigen la nómina. Algunos montos, como los que son calculados a través de una formula, no se pueden cambiar desde esta interfaz.

Liquidar Nómina
===============

	- Ejecute la opción *Novedades y liquidación de nómina*

		 .. figure:: images/n/0.jpg
		   :align: center

	- Seleccione un centro de costo en la lista 'Centro de costo'
	- Seleccione la Sección de nómina. La sección debe tener empleados agregados.
	- Marque la opción **Liquidar nómina** en el panel 'qué proceso desea realizar'
	- Solo podrá liquidar el último periodo pendiente. Es decir, si su última liquidación fue del 15-30 de enero de 2018, su actual liquidación será 1-15 de febrero de 2018. 
	- Presione |btn_ok.bmp| para realizar la liquidación. Ahora la nómina ha sido calculada y puede observar el detalle por empleado y hacer cambios en los montos.
		 .. figure:: images/m/1.jpg
		   :align: center
	- Presione |save.bmp| para cerrar la operación. 
		 .. figure:: images/m/2.jpg
		   :align: center

	.. NOTE:

	No podrá realizar la operación si los empleados no tienen transacciones agregadas o si sus parámetros están en blanco.


Consultar Nómina
================

	Para consultar un proceso de nómina hecho anterior mente, debe haber sido liquidado y cerrado.

	- Ejecute la opción *Novedades y liquidación de nómina*
	- Seleccione un centro de costo en la lista 'Centro de costo'
	- Seleccione la Sección de nómina. La sección debe tener empleados agregados.
	- Marque la opción **Consultar nómina** en el panel 'qué proceso desea realizar' 
	- En la segunda línea de opciones encontrará: **sección de nómina**|**año**|**Periodo a Consultar**| - Elija en cada lista los identificadores de la nómina que desea consultar, ejemplo:

		**| Administrativo | 2018 | 1 - 15 de enero de 2018|**

	- Presione |btn_ok.bmp|
	
		 .. figure:: images/m/1.jpg
		   :align: center

Consultar detalle de nómina por empleado
========================================

Una liquidación pasada:

	- Siga los pasos de `Consultar Nómina`_
	- Busque en la grilla al empleado que desea consultar, para ver en detalles las transacciones que se harán en la liquidación por ejecutar, presione el signo |+| a la izquierda del nombre.
	- Allí verá todas las transacciones relacionadas al empleado

Una liquidación actual (aún no cerrada):

	- Ejecute la opción *Novedades y liquidación de nómina*
	- Seleccione un centro de costo en la lista 'Centro de costo'
	- Marque la opción **Liquidar nómina** en el panel 'qué proceso desea realizar'
	- Solo podrá liquidar el último periodo pendiente. Es decir, si su última liquidación fue del 15-30 de enero de 2018, su actual liquidación será 1-15 de febrero de 2018. 
	- Presione |btn_ok.bmp| para realizar la liquidación
	- Busque en la grilla al empleado que desea consultar, para ver en detalles las transacciones que se harán en la liquidación por ejecutar, presione el signo |+| a la izquierda del nombre.
	- Allí verá todas las transacciones relacionadas al empleado
	
Imprimir un comprobante de pago de empleado
============================================

		- Siga los pasos de `Consultar Nómina`_
		- Busque en la grilla al empleado, a la izquierda de la fila, haga click en |export1.gif|
		- Haga click en |export1.gif|
		- Seleccione en el menú emergente "Imprimir comprobante de pago"



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
