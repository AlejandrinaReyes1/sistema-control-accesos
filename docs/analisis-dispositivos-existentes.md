## Descripción de la situación 

Actualmente hay cámaras en los sites y departamento de informática. Sin embargo, se me indico que para el sistema yo recomendaría otro tipo de cámaras por lo que las cámaras actuales no serán utilizadas en la implementación de la propuesta.
La entrada al sistema de informática es mediante un timbre. La persona a ingresar lo presiona y una persona desde el interior permite el acceso al presionar otro botón. Además, cuenta con un sistema que permite a determinadas personas ingresar mediante un lector de tarjeta.
Para salir del departamento de informática, se presiona un botón que permite desbloquear la puerta.
Los sites no cuentan con este mecanismo, por lo que su ingreso es mediante llave.
Se me indico que para el proyecto yo recomendaría un mecanismo para detectar la apertura de la puerta, y a partir de esto registrar los eventos de entrada y salida sin modificar el mecanismo actual de acceso.

## Dispositivos y mecanismos identificados
| Ubicación | Dispositivo/mecanismo | Función actual | Uso en el proyecto |
|---|---|---|---|
| Departamento de Informática | Cámara | Videovigilancia | No se utilizará |
| Departamento de Informática | Timbre | Solicitar acceso | No se modificará |
| Departamento de Informática | Botón de apertura | Permitir entrada/salida | No se modificará |
| Departamento de Informática | Lector de tarjetas | Controlar el acceso de determinadas personas | No se modificará |
| Sites | Cámara | Videovigilancia | No se utilizará |
| Sites | Cerradura con llave | Permitir el acceso | Se mantendrá el mecanismo actual |
## Análisis 
Con el análisis hecho de los mecanismos actuales, se identificó que el departamento de informatica y sistes utilizan diferentes mecanismos para controlar el acceso.
El sistema propuesto no tendrá como función permitir o denegar accesos, solo detectar y registrar los eventos de entrada y salida.

## Necesidades detectadas
Implementar un mecanismo de detección de apertura que permita registrar los eventos de entrada y salida.
Seleccionar cámaras compatibles con el sistema para obtener la evidencia de los eventos detectados.
Determinar cómo se comunicarán esos dispositivos con el software.

## Conclusión
A partir del análisis realizado, se identificó que los mecanismos actuales permiten controlar la apertura de las puertas, pero no proporcionan directamente al sistema información sobre los eventos de apertura. Asimismo, las cámaras existentes no serán consideradas para la implementación propuesta. Estos aspectos deberán ser considerados en las etapas posteriores del diseño del sistema.
