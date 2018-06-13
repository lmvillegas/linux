Grub
************

Cambio de skin  
==============

Para poder cambiar el skin que viene por defecto de fedora es necesario editar el archivo ``/etc/default/grub`` de la siguiente manera

.. code-block:: console
.. _gnu-screen:

GRUB_TIMEOUT=5

las dos ultimas lineas son las afectadas durante esta edicion, debido a que la linea GRUB_TERMINAL_OUTPUT es comentada
para que permita la visualizacion del skin.
y se agrega o cambia la linea GRUB_THEME con la direccion del nuevo tema por lo general el tema puede ser copiado en 
``/boot/grub2/themes/`` o ``/usr/share/grub/``:



