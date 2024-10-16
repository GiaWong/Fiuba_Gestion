# How the Boeing737 Max DisasterLooks to aSoftwareDeveloper

El artículo cuenta cómo el desastre del Boeing 737 Max se ve desde la perspectiva de un desarrollador de software. El autor, __Gregory Travis__, explica que el problema principal del 737 Max no fue solo un fallo de hardware, sino también uno de software, específicamente en el sistema __MCAS__, que fue diseñado para corregir un defecto en la aeronave, destacando cómo las decisiones de diseño influenciadas por el ahorro de costos llevaron a fallas catastróficas.

## ¿Cuál fue el contexto del problema?
 
El 737 Max fue diseñado como una actualización del Boeing 737, un avión clásico de los años 60. Debido a la competencia y las presiones del mercado, Boeing decidió instalar motores más grandes y eficientes en el 737 Max para reducir costos operativos. 

Sin embargo, estos motores alteraron la aerodinámica del avión, especialmente al aumentar la tendencia de la nariz a levantarse durante ciertas maniobras, lo que aumentaba el riesgo de una pérdida aerodinámica.

## ¿Qué solución optaron?
Para solucionar esta inestabilidad sin rediseñar el avión por completo (lo que hubiera sido costoso y prolongado), Boeing implementó el __software MCAS (Maneuvering Characteristics Augmentation System)__. Este sistema estaba destinado a corregir automáticamente el ángulo de ataque del avión, empujando la nariz hacia abajo cuando los sensores detectaban que estaba demasiado inclinada hacia arriba.


## ¿Qué problemas tuvo el MCAS?
El MCAS dependía de un único sensor de ángulo de ataque. Si ese sensor fallaba, el sistema podía interpretar que el avión estaba en peligro de entrar en pérdida, lo que provocaba que empujara la nariz del avión hacia abajo repetidamente, incluso si los pilotos trataban de corregir el error. 

Esto ocurrió en los accidentes fatales de Lion Air y Ethiopian Airlines, en los que los pilotos no pudieron desactivar el sistema a tiempo para evitar la catástrofe.

## ¿Cuál fue el impacto del ahorro de costos?
Boeing __eligió utilizar el MCAS en lugar de rediseñar la estructura del avión__ porque quería evitar que el 737 Max fuera clasificado como un avión completamente nuevo, lo que habría requerido recertificación y entrenamiento adicional para los pilotos, lo cual es costoso para las aerolíneas. 

En su lugar, presentaron el 737 Max como una actualización del modelo anterior, minimizando las diferencias para que los pilotos ya certificados en versiones anteriores pudieran volarlo sin entrenamiento extenso.


## Crítica a la implementación del software

El autor, __Gregory Travis__, destaca que la __solución de software no fue bien diseñada__. El hecho de que el MCAS no tomara en cuenta información redundante de otros sensores fue un error grave, ya que los aviones modernos tienen múltiples sensores para verificar datos críticos como el ángulo de ataque. 

Esto muestra una falta de comprensión y experiencia por parte de los desarrolladores de software en el ámbito de la aviación.

Travis compara el __sistema MCAS__ con el de su propio Cessna 172, que tiene redundancia en los sistemas y permite que los pilotos tengan el control en todo momento. 

Señala que, en el 737 Max, el MCAS podía ejercer tanta fuerza en los controles que los pilotos se veían incapacitados para contrarrestarlo, lo cual fue un diseño peligroso. Este fallo muestra un cambio en la filosofía de diseño de Boeing, que solía priorizar que los pilotos tuvieran el control total sobre el avión.

## Errores culturales y organizacionales 

El artículo también critica el proceso de certificación de Boeing y la FAA (Administración Federal de Aviación). Con el paso del tiempo, la FAA delegó muchas de sus funciones a ingenieros que trabajaban directamente para Boeing, lo que generó un conflicto de intereses. 

Este sistema de certificación “interno” permitió que fallas graves, como la dependencia de un solo sensor en el MCAS, no fueran detectadas ni corregidas.

Tras los accidentes, Boeing lanzó actualizaciones de software para el MCAS, agregando medidas de redundancia que deberían haber estado presentes desde el principio. Sin embargo, Travis advierte que esto no resuelve el problema de fondo, que es la complejidad innecesaria y la dependencia excesiva del software para corregir errores de hardware. 

El autor sostiene que la solución debería haber sido eliminar el MCAS por completo y rediseñar el avión para que sea aerodinámicamente estable.

---
El desastre del 737 Max es un ejemplo de cómo las presiones comerciales y la falta de rigurosidad en el diseño llevaron a que un defecto de software (MCAS) ocultara un problema de hardware, resultando en dos tragedias que costaron la vida de cientos de personas.