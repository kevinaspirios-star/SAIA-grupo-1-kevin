# Sistema de apoyo para la inocuidad alimentaria

### Descripción
El proyecto se enmarca en el desarrollo de un sistema de apoyo a la inocuidad alimentaria, con el objetivo de permitir la visualización de indicadores de gestión de la misma, a partir de la administración de diferentes instrumentos de relevamiento de Buenas Prácticas de Manufactura (BPM) y Procedimientos Operativos Estandarizados (POES), como protocolos, muestreos, puntos de control, entre otros.

### Integrantes:
* Kevin Aspi Ríos

Saque el nombre de los demas integrantes para mantener su privacidad.

Yo trabaje en la parte de registro de equipos , plan de limpieza , plan de calibracion y tareas. Tambien trabaje en la creacion de una vista publica exclusiva para el cliente ajeno a la empresa, esta vista puede desactivarse como activarse y tiene un switch para decidir si mostrar un grafico o no en la vista publica, el metedo de acceso es mediante el scaneo de un qr que se genera cuando activamos la vista publica.

en el archivo HabilitarVista.tsx hay una constante Payload en el que cargo los datos del qr junto con una url el cual contiene mi ip de red, recomiendo cambiar esa ip por su propio ip de red para poder probar el programa, mas especificamente para poder probar la vista publica exclusiva para el cliente ajeno a la empresa.

ejemplo de como tieneq quedar la la url del payload.

http://ip_PropiaDeRed:5173/vista-publica?verGrafico=${config.verGrafico}


este proyecto sigue en etapa de desarrollo asi que no esta terminado.
