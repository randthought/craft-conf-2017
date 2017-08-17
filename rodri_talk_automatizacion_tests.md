Automatización de test contra ApiS
=================================

- No tenemos requisitos en este caso. Por eso hacemos testing exploratorio
- Robustez de datos
- Request(parametros, operacion, cabeceras...)
- Casos límite = comprobar inconsistencias, que no haya nada y deje eliminar, ...
- Lógica funcional = Seguir la logica sobre el funcionamiento de algo y preguntar o proponer una mejora para un mejor funcionamiento
- Persona que lo realiza = Si es desarollador o externo al proyecto

Testlink
-------------

- Requisistos


Jmeter
-----------

- Objetos (config elements) = Headers, default value to http request, se pueden parametrizar valores
- Objetos II (Samplers) = Body, host or ip,
- Objetos III(Beanshell) = conexión a base de datos directa y ejecucion para añadir datos, añadir checks logicos
- Objetos IV (Listeners) = Check responses
- Desarollo de escenarios = Generar data request parameters (vars)
