# CS-305-Seguridad-del-software-
Repositorio de la clase de seguridad del software.
Descripción del proyecto
 
Artemis Financial es una compañía que presta servicios financieros, que quería proteger su aplicación y la información que gestionaba. Yo estaba trabajando como desarrollador de software para Global Rain y mi propósito era examinar las vulnerabilidades que presentaba la aplicación, detectar posibles riesgos y aplicar prácticas de codificación segura para mejorar la protección de la información e incrementar la seguridad de las comunicaciones.

1. Cliente y requisitos del software

Mi cliente fue Artemis Financial, una empresa que ofrece servicios de planificación financiera personalizados, incluido un plan de ahorro, otra jubilación, un plan de inversiones y los seguros. Necesitaban que su aplicación protegiera la información financiera de sus clientes, que mantuviera la integridad de los datos y que facilitara una comunicación segura; por ello, era necesario que evaluáramos las dependencias del proyecto, que identificásemos vulnerabilidades y que definimos la aplicación de medidas de seguridad apropiadas.

2. Seguridad de las decisiones y su importancia

Una de las decisiones que tomé y que considero muy importante fue la de hacer uso de herramientas de análisis de vulnerabilidades para saber qué riesgos tenía en todas las dependencias del proyecto. Además, para el propio análisis de las bibliotecas que se usan, revisé la configuración de Maven, y luego utilicé OWASP Dependency-Check para analizar las bibliotecas y sus vulnerabilidades conocidas. También configuré un archivo de supresión, con el propósito de gestionar los hallazgos que consideré falsos positivos, cuando contaba con una justificación que me permitía realizar esta acción. Desarrollar código seguro es importante (porque ayuda a prevenir los accesos no autorizados) y porque ayuda a mantener información confidencial y a reducir el riesgo de incidentes. Por otro lado, la seguridad también ayuda a mejorar la confianza de los clientes, ayuda a la continuidad de la operación e implica (incluso) menor costo derivado de posibles fallos.

3. La parte más complicada o máspreciada de la evaluación

La parte más complicada fue configurar OWASP Dependency-Check y solventar los problemas relacionados al hecho de que no se podía descargar la información de las vulnerabilidades de la base de datos de la National Vulnerability Database (NVD). Esto me permitió entender que las herramientas de seguridad iban de la mano de una buena configuración y de fuentes de información actualizadas. La parte más despreciada fue el hacer el ejercicio de entender qué significaban los resultados del análisis, distinguir las "cosas que requerían que las tuviera en cuenta" de los falsos positivos o "falsos positivos" y el documentar las decisiones relativas al análisis en sí.

4. Refuerzo de las capas de seguridad

Reforcé la seguridad mediante el análisis de dependencias, la revisión de la configuración del proyecto y la aplicación de medidas de mitigación apropiadas. También comprendí la importancia de proteger las comunicaciones mediante HTTPS y certificados digitales cuando corresponde. En futuros proyectos utilizaría recursos como OWASP Dependency-Check, la documentación de OWASP, la base de datos NVD y las recomendaciones de seguridad de Spring para identificar vulnerabilidades y seleccionar soluciones basadas en evidencia. Asimismo, mantendría las dependencias actualizadas y realizaría análisis periódicos.7

5. Verificación de la funcionalidad y la seguridad

Para poder comprobar si los cambios no afectaban la funcionalidad de la aplicación, utilicé las pruebas disponibles en el proyecto y comprobé la correcta finalización de la compilación. También ejecuté el análisis de dependencias tras haber hecho un ajuste en la configuración y comprobé el informe HTML para obtener información sobre los resultados. La comparación en los resultados de antes y después de los cambios, dado que se tienen ambos informes, permite comprobar si las vulnerabilidades se han solucionado o si los hallazgos fueron tratados correctamente. Este proceso también me enseña que la refactorización debe ir acompañada de pruebas funcionales y de análisis de seguridad, no presupuesto que una compilación que finaliza correctamente sea suficiente para garantizar por sí sola que el software es seguro.

6. Recursos, herramientas y prácticas útiles 

Las herramientas y prácticas más útiles resultaron ser Java, Spring Boot, Maven, OWASP Dependency-Check, el archivo pom.xml y la configuración de relajar hallazgos mediante suppression.xml. También adquirí un conocimiento importante en la consulta de fuentes fiables de vulnerabilidades, en la documentación de los cambios, en la revisión de las dependencias y en la ejecución de pruebas tras modificar el código. Estos conocimientos me servirán para proyectos futuros de desarrollo, mantenimiento y análisis de la seguridad de aplicaciones.

7. Evidencia para futuros empleadores

Este proyecto constituye una evidencia práctica de mi capacidad para analizar riesgos de seguridad, utilizar herramientas de análisis de dependencias, configurar un proyecto Java con Maven y documentar medidas de mitigación. En mi portafolio puedo presentar el informe de evaluación de vulnerabilidades, los archivos de configuración pertinentes y los resultados del análisis. Este trabajo demuestra que puedo seguir un proceso de evaluación, investigar problemas técnicos y tomar decisiones orientadas a mejorar la seguridad y la calidad del software.
Herramientas utilizadas

-Java y Spring Boot
-Maven
-OWASP Dependency-Check
-National Vulnerability Database (NVD)
-Informes HTML de análisis de dependencias
-Archivos de configuración pom.xml y suppression.xml, cuando corresponda

Propósito del portafolio

Este artefacto demuestra mi aprendizaje en evaluación de vulnerabilidades y codificación segura. Representa una experiencia práctica que puedo utilizar para seguir desarrollando mis habilidades en análisis de riesgos, protección de aplicaciones y desarrollo de software seguro.
