# USB_UART
UART con raspberry

Module: USB-UART 6-In-1 Multifunctional (USB-TTL/RS485/232,TTL-RS232/485,232 to 485) Serial Adapter, with CP2102

Verificar si esta activa la configuración de Serial de la RPi
> dmesg | grep tty

En caso que no se cuente con el modulo activo, sera necesario realziar cualquiera de las dos opciones:
> a) "menu / preferences / Raspberry Pi configuration" y en el tab seleccionar "Interfaces" activar "Serial"

> b) Desde la terminal ingresar "sudo raspi-config", seleccionar la opcion "Avanced Options" y activar el "Serial"

Volver a verificar y observar que "ttyAMA" y "ttyUSB"
> dmesg | grep tty

## Nota: La configuracion se encuentra en la carpeta de images de este repo.
