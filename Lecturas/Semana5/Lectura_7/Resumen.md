# "Modern Software Engineering", chapter 3

"Fundamentals of an Engineering Approach" (Fundamentos de un Enfoque de Ingeniería), se centra en la idea de aplicar principios de ingeniería en el desarrollo de software. 

1. **Cambio en la industria del software**: Aunque la industria del software se caracteriza por cambios rápidos, muchos de estos cambios no contribuyen significativamente al progreso en el desarrollo. Farley critica la adopción de nuevas tecnologías que, en ocasiones, no mejoran los procesos, e incluso pueden empeorar las cosas. Sin embargo, menciona que ha habido avances significativos, como el paso de lenguajes de bajo nivel (como Assembler) a lenguajes más abstractos como C, o de paradigmas procedurales a orientados a objetos, que aumentaron la complejidad que los desarrolladores podían manejar.

2. **Importancia de la medición**: Farley resalta que una de las razones por las que se cometen errores en el desarrollo de software es la falta de medición efectiva. Muchas métricas comunes, como la velocidad (velocity) o las líneas de código, no son útiles. Propone que las medidas más relevantes son la **estabilidad** y el **rendimiento** (throughput), basándose en los estudios del libro *Accelerate* de Nicole Forsgren, Jez Humble y Gene Kim. Estos estudios correlacionan equipos de alto rendimiento con prácticas como la automatización de pruebas, desarrollo basado en trunk (trunk-based development) y la entrega continua (continuous delivery).

3. **Estabilidad y rendimiento**: Estos dos conceptos se miden con:
   - **Estabilidad**: Medida por la tasa de fallos (Change Failure Rate) y el tiempo de recuperación ante fallos (Recovery Failure Time).
   - **Rendimiento**: Medido por el tiempo que tarda una idea en convertirse en software funcional (Lead Time) y la frecuencia de despliegue de cambios (Deployment Frequency).

4. **Modelo predictivo**: Farley enfatiza que estas medidas pueden predecir el éxito de los equipos en términos de calidad del software y rendimiento organizacional. Además, refuerza la idea de que la velocidad y la calidad no son mutuamente excluyentes, como a veces se cree, sino que están correlacionadas positivamente según los datos.

----