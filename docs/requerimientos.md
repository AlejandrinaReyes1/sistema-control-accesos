# Requerimientos del sistema

## 1. Descripción

Sistema destinado al monitoreo y registro de aperturas de puertas mediante sensores y cámaras.

## 2. Requerimientos funcionales
**RF-01 – Detección de entrada**
El sistema deberá detectar la entrada mediante un sensor.

**RF-02 – Detección de salida**
El sistema deberá detectar la salida mediante un sensor.

**RF-03 – Notificaciones de acceso**
El sistema deberá enviar una notificación por correo electrónico cuando se detecte una entrada en un sitio cuyo envío de notificaciones se encuentre habilitado. El usuario podrá habilitar o deshabilitar las notificaciones de manera independiente para cada sitio.

**RF-04 – Registro en bitácora**
El sistema deberá registrar en una bitácora la fecha, hora y tipo de evento (entrada o salida) detectado en cada sitio monitoreado.

**RF-05 – Evidencia**
El sistema deberá grabar 5 segundos de video cuando se detecte una apertura.

**RF-06 – Consulta de evidencia**
El sistema deberá permitir consultar las fotografías capturadas y los videos grabados de acuerdo con la fecha seleccionada.

**RF-07 – Inicio de sesión**
El sistema deberá permitir al administrador iniciar sesión mediante las credenciales predeterminadas proporcionadas por el desarrollador.

**RF-08 – Eliminación de evidencia**
El sistema deberá permitir al usuario eliminar las fotografías y videos registrados correspondientes a una o más fechas seleccionadas.

**RF-9 – Descarga de evidencia**
El sistema deberá permitir al usuario descargar las fotografías y videos registrados.

**RF-10 – Disponibilidad de cámara**
El sistema deberá verificar periódicamente la disponibilidad de las cámaras registradas y notificar al usuario cuando una cámara no se encuentre disponible.

**RF-11 – Creación de sitios**
El sistema deberá permitir al usuario agregar un sitio de monitoreo proporcionando un nombre para identificarlo.

**RF-12 – Consulta de sitios**
El sistema deberá permitir al usuario seleccionar un sitio de monitoreo para consultar las cámaras y la bitácora asociadas al sitio.

**RF-13 – Registro de cámaras**
El sistema deberá permitir al usuario agregar una cámara a un sitio de monitoreo proporcionando la información necesaria para establecer su conexión con el sistema.

## 3. Requerimientos no funcionales
**RNF-01 – Seguridad de contraseñas**
La contraseña del usuarios deberá almacenarse utilizando un algoritmo de hash seguro y no deberá almacenarse en texto plano.

**RNF-02 – Usabilidad**
La aplicación deberá contar con una interfaz intuitiva que permita al usuario acceder a las principales funciones del sistema de manera sencilla.

**RNF-03 – Tiempo de respuesta**
El sistema deberá registrar en la bitácora un evento de entrada o salida inmediatamente después de su detección, sin depender del tiempo requerido para capturar la evidencia.

**RNF-04 – Disponibilidad de evidencia**
El sistema deberá poner a disposición del usuario la fotografía o video generado por un evento de apertura una vez finalizada su captura y almacenamiento.

**RNF-05 – Compatibilidad**
El sistema deberá ser compatible con las cámaras seleccionadas para el proyecto y permitir la comunicación necesaria para la captura de evidencias y la verificación de su disponibilidad.

**RNF-06 – Integridad de datos**
El sistema deberá conservar correctamente los registros de entradas, salidas y evidencias almacenados, evitando modificaciones o pérdidas accidentales de información.

**RNF-07 – Disponibilidad**
El sistema deberá estar disponible para su utilización durante el horario de operación establecido para el monitoreo de los sitios.

**RNF-08 – Mantenibilidad**
El sistema deberá estar estructurado de manera que permita realizar modificaciones, correcciones y mantenimiento sin afectar innecesariamente las demás funciones de la aplicación.

**RNF-09 – Almacenamiento**
El sistema deberá contar con un mecanismo de almacenamiento que permita conservar y consultar las fotografías y videos registrados por el tiempo establecido para el proyecto.

