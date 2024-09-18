# "¿Quality Control = Project Control? Indicadores Objetivos para Control de Proyectos de Desarrollo de Software"

Escrito por __Juan Pablo Pussacq Laborde__, se centra en los problemas típicos de la gestión de proyectos de software, particularmente los desvíos en __costo__ y __tiempo__, y propone soluciones mediante el uso de indicadores objetivos.

## Problemas Identificados:

- __Desvíos en Costo y Tiempo__: Los proyectos suelen desviarse de lo planificado por falta de buenas herramientas de control.

- __Información Subjetiva__: Muchas veces el avance del proyecto se mide de manera subjetiva, lo que lleva al __síndrome del 90%__, donde se informa que el proyecto está casi terminado cuando no es así.

- __Errores al Medir el Avance__: Los métodos tradicionales, como medir el avance por calendario o por código completo, no son confiables.


## Soluciones Propuestas:

- __Control de Proyectos Basado en Control de Calidad__: La calidad del software se utiliza como indicador del avance. 

    El avance solo cuenta cuando el producto está desarrollado, probado y estabilizado.

- __Indicador de Funcionalidad Completa__: Este indicador mide el avance cuando una funcionalidad está completamente desarrollada, probada y libre de defectos críticos. 

    Para ello, se divide el producto en funcionalidades y se les asigna un peso basado en su complejidad.

    - __Proceso para crear el indicador__:

        - Identificar las funcionalidades del proyecto.

        - Asignar un peso a cada funcionalidad __(simple, mediana o compleja)__.

        - Estimar y registrar fechas de finalización para cada funcionalidad.


- __Indicador de Nivel de Calidad__: Este mide el avance a través de varios estados intermedios de cada funcionalidad, desde __"No iniciado"__ hasta __"Aprobado por usuario"__.
 
    Esto permite un mayor control sobre la calidad a lo largo del ciclo de vida del producto.

- __Indicador de Evolución de la Prueba__: Este indicador sigue la cantidad de defectos encontrados y cerrados durante el proceso de pruebas, lo que ayuda a predecir cuánto tiempo llevará estabilizar el producto.

- __Indicador de Earned Value__: Utilizando el concepto de valor ganado, este indicador mide el progreso financiero del proyecto en función del avance de las funcionalidades completas.

## Consideraciones Finales:

Los indicadores ayudan a mejorar la toma de decisiones al ofrecer datos objetivos y fáciles de interpretar.

Es crucial equilibrar la exactitud de los indicadores con la carga administrativa que su implementación puede generar.


No todos los proyectos requieren el uso de todos los indicadores, pero como mínimo se recomienda usar el de __Funcionalidad Completa__ y el de __Evolución de la Prueba__.

El autor destaca la importancia de utilizar __herramientas objetivas__ para controlar proyectos de software, evitando caer en la subjetividad y mejorando la capacidad de predecir desvíos y tiempos de finalización.