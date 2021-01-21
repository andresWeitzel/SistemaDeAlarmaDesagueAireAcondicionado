# SistemaDeAlarmaDesagueAireAcondicionado

**Desarrollo de un sistema de alerta para el desague de un Aire Acondicionado Portátil aplicando un placa china A.nano chipset ch340g y sensores**

</br>

## Más Información

<hr>

## Instalación del driver del chipset ch340g conversor Usb.

#### 1)Descargar el driver .exe  en http://www.wch.cn/download/CH341SER_EXE.html (Windows) 
````(IMPORTANTE:Esto es una librería donde incluye el ch340g y todos los tipos, está en chino, traducí la págia y fijate si incluye el tipo de chipset)````

#### 2)Descomprimí el archivo e instalalo..siguiente..siguiente

#### 3)Conectar el Arduino nano.

#### 3)Entrar al ```` "Administrador de Dispositivos" ```` e ir al apartado de  ````"Puertos"````, click derecho sobre este y clickear ````"Buscar cambios de Hardware"````. Se actualizará la lectura de puertos y de esta forma visualizaremos ````"USB-SERIAL CH340(COMX)."````

#### 4)Desde el IDE que se programe seleccionar placa y puerto correspondiente.

#### 5)```Si aún no toma el puerto, seleccioná(dentro del IDE ARDUINO) dentro de la pestaña Herramientas->Procesador->ATmega328P (Old Bootloader)```
