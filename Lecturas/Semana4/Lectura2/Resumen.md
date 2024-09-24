# Stop Promising Miracles

El documento "Stop Promising Miracles" de __Karl E. Wiegers__, publicado originalmente en Software Development en el año 2000, aborda la problemática de las estimaciones en proyectos de software y propone soluciones mediante el uso de técnicas estructuradas, como __Delphi__ y __Wideband Delphi__.


## Contexto y Problema:

El autor comienza identificando un problema común en el mundo del desarrollo de software: __la dificultad de realizar estimaciones precisas__. 

Explica que muchos profesionales de software no están bien capacitados en técnicas de estimación, lo que conduce a un optimismo excesivo. Esto se agrava por varios factores:

- __Memoria corta__: 

    No se aprenden lecciones de proyectos anteriores que han excedido sus tiempos o costos.
- __Falta de buffers__: 

    No se incorporan márgenes de contingencia para manejar riesgos o imprevistos.
- __Omisión de tareas__: 

    Se tienden a pasar por alto actividades clave, como control de calidad, gestión de configuraciones o tareas de soporte. Esto provoca que, cuando estas tareas finalmente se abordan, se excedan los plazos o se comprometa la calidad.


## Soluciones Propuestas:

Wiegers propone diversas soluciones para mejorar el proceso de estimación en los proyectos de software:

1. __Registro de estimaciones y resultados__: 

    Llevar un control detallado de las estimaciones previas, los procesos utilizados y los resultados obtenidos para retroalimentar futuras estimaciones.
2. __Uso de plantillas y procedimientos__: 

    Esto ayuda a desglosar el trabajo en partes más pequeñas y menos propensas a ser olvidadas.


## Método Delphi
El autor introduce el método Delphi, desarrollado por la _Rand Corporation en 1948_, y describe su evolución para proyectos de software, donde Barry Boehm y su equipo lo adaptaron a lo que conocemos como _Wideband Delphi_. Este método implica la participación de varios estimadores que:

- Producen estimaciones individuales de manera anónima.

- Llegan a un consenso a través de múltiples iteraciones, discutiendo sus suposiciones y ajustando sus estimaciones en consecuencia.


El método __Wideband Delphi__ agrega interacción entre los miembros del equipo y es ideal para desglosar tareas en proyectos grandes o complejos, eliminando sesgos y permitiendo una mayor precisión al agregar diferentes perspectivas.

## Proceso de Wideband Delphi:
1. __Planificación__:
    
    - __Definición del problema__: Se detalla el alcance del problema que se va a estimar.
    - __Selección de participantes__: Se elige un moderador, que también puede actuar como estimador, y un grupo de 2 a 4 estimadores con experiencia en el proyecto. El moderador debe ser imparcial y no influir en los resultados.

2. __Kickoff Meeting__:

    En esta reunión inicial, se presenta el problema, las restricciones del proyecto y las unidades de estimación (horas-hombre, líneas de código, etc.). Todos los participantes deben comprender el problema antes de proceder.

3. __Preparación Individual__:
    
    Cada participante elabora de forma independiente una lista de tareas necesarias para cumplir con el objetivo del proyecto. 
    
    Se estima el esfuerzo para cada tarea, desglosando las actividades en unidades pequeñas (por ejemplo, tareas que no excedan las 20 horas de trabajo). 
    
    También se deben registrar las __asunciones__ sobre las que se basa cada estimación, ya que diferentes __asunciones__ pueden llevar a grandes variaciones entre las estimaciones de los participantes.


4. __Reunión de Estimación__:
    
    En esta etapa, el moderador recopila las estimaciones individuales y muestra una distribución gráfica de los resultados (sin identificar quién realizó cada estimación). 
    
    Las diferencias entre las estimaciones iniciales suelen ser significativas, lo que resalta la importancia de obtener múltiples opiniones.

    Se discuten las tareas y los supuestos para identificar discrepancias. 
    
    Los participantes ajustan sus estimaciones basándose en la nueva información compartida.


    Este ciclo de revisión y ajuste de estimaciones se repite hasta que:

    - Las estimaciones convergen dentro de un rango aceptable.

    - Se agota el tiempo disponible.

    - Los participantes no están dispuestos a ajustar más sus estimaciones.


5. __Revisión de Resultados__:


    El moderador o gerente de proyecto reúne todas las listas de tareas y las estima, eliminando duplicados y resolviendo las discrepancias. 
    
    Es esencial entender y documentar por qué hubo diferencias significativas en algunas estimaciones.
    
    Se lleva a cabo una reunión de revisión final para garantizar que la lista de tareas sea lo más completa posible y que los estimadores estén de acuerdo con el resultado final.

## Criterios de Salida:

El proceso de estimación se considera completado cuando se cumplen ciertos criterios, como:

- Se ha creado una lista de tareas detallada.
- Se han documentado las asunciones de las estimaciones.
- Se ha alcanzado un consenso en las estimaciones dentro de un rango aceptable.


## Tratamiento de los Resultados:

Wiegers sugiere que no se debe confiar únicamente en el promedio de las estimaciones, ya que esto tiende a subestimar el esfuerzo real. En su lugar, recomienda presentar tres valores:

1. __Caso promedio__: El valor medio de las estimaciones.
2. __Caso mejor__: El valor más bajo.
3. __Caso peor__: El valor más alto. También se puede utilizar la simulación de __Monte Carlo__ para obtener una distribución probabilística de las posibles estimaciones.

---
Wiegers concluye que el método __Wideband Delphi__ es una herramienta valiosa para realizar estimaciones más precisas y realistas. Al incorporar múltiples perspectivas, reducir el sesgo y permitir iteraciones basadas en la discusión, se obtiene un rango de estimaciones más confiable. 

Aunque ningún método de estimación es perfecto, el __Wideband Delphi__ ayuda a minimizar errores y gestionar la incertidumbre inherente al proceso de estimación de proyectos.

Este enfoque no solo mejora la precisión, sino que también genera compromiso y confianza entre los miembros del equipo, permitiendo una planificación de proyectos más efectiva.