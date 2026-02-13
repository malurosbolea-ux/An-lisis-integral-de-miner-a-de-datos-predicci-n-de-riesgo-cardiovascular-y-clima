# Análisis integral de minería de datos: predicción de riesgo cardiovascular y clima

¡Hola! Soy María Luisa Ros Bolea. He desarrollado este proyecto completo de *Data Science* para abarcar el ciclo de vida íntegro del dato: desde la extracción en crudo hasta la visualización estratégica para la toma de decisiones. 

En este repositorio muestro cómo traduzco problemas complejos en soluciones técnicas y, finalmente, en *insights* de negocio. Para este caso, he trabajado con datos de salud (riesgo de infarto) y meteorología, aplicando técnicas de ingeniería de datos, limpieza, modelado y *Business Intelligence*. Y sí, con mi toque personal en los diseños analíticos (¡el rosa no podía faltar!).

## Archivos del repositorio

He estructurado todo paso a paso para que puedas seguir mi proceso de trabajo de forma clara y sin perderte ningún detalle:

* **[Notebook principal de Python (Jupyter)](./Mineríadedatos_PRACTICA_FINAL-3.ipynb)**: Aquí está el corazón del código. Realizo la extracción de datos mediante la API de AEMET y *Web Scraping*. Luego aplico técnicas de limpieza, *Feature Engineering* y el paso clave: el balanceo de datos médicos usando **SMOTE** para que el modelo predictivo sea realmente útil detectando el riesgo, y no se quede en un "modelo tonto".
* **[Dashboard interactivo en Power BI](./practicafinal_mineriadedatos.pbix)**: El archivo fuente donde he modelado y visualizado el impacto económico y clínico de los datos de los pacientes.
* **[Exportación del dashboard en PDF](./practicafinal_mineriadedatos.pdf)**: Por si quieres echarle un vistazo rápido a las visualizaciones de Power BI (como el mapa clínico de Edad vs Colesterol o el impacto del sedentarismo) sin necesidad de abrir el programa.
* **[Dashboard web analítico (HTML)](./dashboard_mineria_de_datos_preciosol.html)**: Una versión web interactiva (*Pink Edition*) programada con Plotly donde muestro KPIs, gráficos de dispersión y la matriz de correlación de forma muy visual y accesible.
* **[Presentación interactiva estratégica](./presentacion_mineria_PFINAL.html)**: Un formato web dinámico que he creado para presentar los resultados y la estrategia de negocio de forma muy clara a *stakeholders* que no tienen por qué tener una base técnica.
* **[Memoria técnica y de negocio](./Memoria_Proyecto_Mineria_Datos_Maria_Luisa_Ros.docx)**: El documento donde detallo de forma exhaustiva cada fase del proyecto, mis reflexiones, las decisiones metodológicas, la gestión de *outliers* y la conclusión estratégica final.

## Las tres misiones del proyecto

Me gusta hacer las cosas con sentido e ir paso por paso. Por eso, dividí este reto en tres fases estratégicas:

1.  **La caza del dato (Extracción)**: No me conformé con descargar un dataset estático. Me conecté a la API de la AEMET para obtener predicciones del tiempo reales en Madrid y construí un *scraper* robusto para lidiar con tablas HTML complejas.
2.  **Puliendo el diamante (Preprocesamiento)**: Los datos del mundo real vienen sucios. Imputé valores nulos con la mediana para evitar sesgos, separé variables críticas (como la tensión arterial sistólica y diastólica) y logré el hito más importante: balancear las clases al 50/50 con SMOTE para que la predicción de infartos fuese precisa y matemática.
3.  **Visualización y negocio (Business Intelligence)**: Los datos no sirven de nada si no se entienden. Pasé de las métricas puras a las conclusiones estratégicas, diseñando cuadros de mando enfocados a la acción.

## Sobre mí y contacto

Combino la Comunicación Digital con el Big Data y la Inteligencia Artificial. Mi especialidad es moverme en la intersección del análisis de datos y la creación de estrategias digitales efectivas, traduciendo los aspectos técnicos a planes de negocio ejecutables. Soy una persona muy sociable, cercana y me encanta hablar, por lo que siempre busco que los datos cuenten una historia comprensible para cualquier tipo de individuo.

Si quieres conocer más sobre mi trabajo, necesitas a alguien que te dé las cosas bien hechas y revisadas desde el principio, o simplemente quieres charlar sobre proyectos de datos y estrategia, ¡conecta conmigo!

* **Portfolio estratégico**: [Mi sitio web](https://malurosbolea-ux.github.io/digital-strategy-portfolio/)
* **LinkedIn**: [María Luisa Ros Bolea](https://www.linkedin.com/in/mar%C3%ADa-luisa-ros-bolea-400780160/)
* **Instagram**: [@malu_menolu](https://www.instagram.com/malu_menolu/)
* **Email**: [malurosbolea@gmail.com](mailto:malurosbolea@gmail.com)
* **Teléfono**: +34 692 892 183
* **Ubicación base**: Madrid / Murcia

¡Espero que disfrutes explorando este proyecto tanto como yo lo hice creándolo!
