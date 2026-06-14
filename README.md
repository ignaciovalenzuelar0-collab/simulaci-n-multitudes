#Simulación de Multitudes y Cuellos de BotellaDescripción
Este repositorio contiene una simulación completa de un problema  de movimiento de multitudes para videojuegos mediante un modelo basado en agentes. El objetivo es evaluar cómo la alteración del radio de separación personal afecta el flujo y el tiempo de cruce de los NPCs a través de un obstáculo.  Requisitos y Entorno
* Software necesario: NetLogo (versión 6.4.x). * No se requieren librerías externas, todo el entorno está autocontenido en el archivo del modelo.   Instrucciones de Ejecución y Reproducibilidad
1. Descargar el archivo .nlogo de este repositorio. 
2. Abrir el archivo utilizando NetLogo.
3. En la interfaz principal, presionar setup para generar el entorno y los agentes, y luego go para iniciar el movimiento.
4. Para garantizar la reproducibilidad exacta de la simulación, se configuraron versiones de librerías nativas y se puede fijar una semilla aleatoria (random-seed) en el código. 
5. Para replicar la recolección de datos, abrir Tools > BehaviorSpace y ejecutar el experimento preconfigurado Prueba_Separacion.  Datos y Resultados
El repositorio incluye el archivo .csv con los datos en crudo extraídos de los experimentos. Estos datos reflejan los barridos de parámetros y fueron utilizados para el análisis de sensibilidad documentado en el informe final.
