# Diagnóstico estratégico integral para plataforma de suscripción y delivery (2026) Académico
La suscripción Plus es un servicio dentro del ecosistema de la plataforma de delivery diseñado para aumentar la frecuencia de compra y el valor generado por usuario. Sin embargo, el equipo de negocio no tiene claro si el servicio está cumpliendo su objetivo. Existen dudas clave:
¿Los usuarios realmente compran más?
¿El modelo está generando ganancias?
¿Se están perdiendo oportunidades en el proceso de compra?
Además, 

**Objetivo:** Realizar un diagnóstico integral para la plataforma respondiendo a las dudas clave.

# Herramientas
🛠 Python | Numpy | Matplotlib | Seaborn | Jupyter Notebook | SQL | Power Bi | Tableau

# Preguntas Clave
1. ¿Estamos ganando dinero?
2. ¿Dónde se pierden los usuarios? ¿Los usuarios regresan?
3. ¿Los cambios generan impacto?

# Metodología
- Primero en Python se evaluó la calidad de los datos, se detectaron inconsistencias. Luego, se procede a limpiar y estructurar los datasets y así, generar un dataset listo para análisis.
- Análisis de rentabilidad del negocio, se calcularon KPIs (ingresos/revenue, costos, ganancias, entre otros) y se realiza la identificación de segmentos rentables.
- Luego, se construyé el funnel en SQL para analizar el comportamiento de los usuarios. Después, se calculó la tasa de conversión entre cada paso del funnel y se identifica en qué etapa se pierde la mayor cantidad de usuarios.
- Analizamos la retención de usuarios para entender si regresan después de registrarse, construyendo cohortes.
- Por último, se construye un dashboard con KPIs comunicando insights.

# Hallazgos y recomendaciones
- Los indicadores clave indican que el necogio es rentable.
- Se encuentra que, la mayor pérdida de usuarios se produce entre begin_checkout y add_payment_info hay una caída del 13.29% (86.71% de conversión), esta es la etapa más crítica del funnel. Además, del total de visitantes, 80.04% completan la compra (6,240/7,796).
- La retención general estable: La mayoría de cohortes mantienen ~41-43% de retención.
- Después de ver que el resultado no es estadísticamente significativo la recomendación de negocio es no implementar el cambio, ya que no demostró un impacto. Explorar algún análisis adicional, por segmentación para ver si hay diferencias en subgrupos específicos.
