# La migración de sistemas heredados hacia una arquitectura de microservicios mediante el uso de una técnica llamada especificaciones mediante ejemplos (SBE)

Por Carlos Fontela

## Introducción
- Software heredado: 

    Son sistemas que, aunque exitosos, resultan difíciles de mantener debido a la pérdida de conocimiento sobre su funcionamiento.

- SBE: 

    Specification By Example, es  una  práctica  colaborativa de construcción basada en especificaciones mediante ejemplos que sirven como pruebas de aceptación.

- Problemas comunes: 

    Falta de documentación, ausencia de pruebas de aceptación y técnicas, y equipos de desarrollo que ya no están disponibles.


- Microservicios: 

    La arquitectura de microservicios organiza las aplicaciones como un conjunto de componentes autónomos, cada uno en su propio proceso, permitiendo el despliegue independiente y facilitando la adopción de nuevas tecnologías.


## Especificaciones mediante ejemplos (SBE)

- Origen: 

    Esta técnica deriva de la práctica de Extreme Programming de Kent Beck, donde se especifican historias de usuario acompañadas de pruebas.


- Enfoque colaborativo: 

    Se utiliza un enfoque __"de afuera hacia adentro"__, refinando el diseño mediante pruebas unitarias y de aceptación, asegurando que los ejemplos definidos sirvan tanto para probar como para documentar el sistema.


- Beneficios: 

    Los ejemplos permiten una mejor comunicación entre roles (usuarios, analistas, desarrolladores y testers) y funcionan como especificaciones ejecutables que facilitan las pruebas de aceptación.


## Arquitectura de Microservicios

- Características: 

    Despliegue independiente de servicios organizados en torno a capacidades específicas de negocio, utilizando tecnologías y mecanismos de persistencia independientes para cada microservicio.


- Ventajas: 

    Mayor velocidad de liberación, escalabilidad y tolerancia a fallos. Además, permite reemplazar gradualmente partes de un sistema monolítico sin desecharlo por completo.


- Desafíos: 

    Complejidad adicional en sistemas distribuidos, que puede afectar pruebas, seguridad, rendimiento y refactorización.


## Propuesta Metodológica

La metodología propone migrar sistemas heredados a microservicios mediante el uso de ejemplos que sirvan como casos de aceptación.


El proceso es incremental, enfocándose en funcionalidades específicas que se van especificando en talleres multidisciplinarios donde participan todos los interesados.


Se recomienda la automatización de pruebas de aceptación para prevenir regresiones, y el enfoque por demanda, lo que significa que solo se aborda la funcionalidad que requiera ser cambiada.


## Validación

El trabajo se está validando mediante proyectos finales de estudiantes de la Universidad de Buenos Aires, quienes están migrando sistemas heredados a arquitecturas de microservicios. 

Se mencionan varios proyectos, entre ellos la modernización de un sistema de avisos clasificados y la recuperación de conocimiento de un sistema del gobierno federal argentino.


## Conclusiones

La propuesta es una respuesta a la creciente necesidad de liberar incrementos de producto más frecuentes en organizaciones centradas en software.

Se enfatiza que la migración debe ser incremental, manteniendo la funcionalidad no migrada hasta que sea necesario cambiarla, y colaborando estrechamente con los usuarios para definir los casos de prueba y aceptación.

El trabajo presenta un enfoque para modernizar sistemas heredados mediante la migración a microservicios, utilizando especificaciones mediante ejemplos como herramienta central para recuperar el conocimiento perdido y asegurar la calidad del software durante el proceso de transformación.