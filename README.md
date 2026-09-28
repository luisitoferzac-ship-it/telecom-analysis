# telecom-analysis
Análisis Ejecutivo: Optimización de Clientes y Consumo en ConnectaTel
Resumen del Proyecto:
Se realizó un análisis de datos utilizando Python (Jupyter Notebook) sobre la base de datos de clientes de ConnectaTel. El objetivo principal fue limpiar la información, identificar segmentos clave por edad/uso y detectar patrones atípicos para proponer mejoras en la oferta comercial de planes de telefonía.
1. Calidad y Limpieza de Datos:
•	Desafío: Se detectó la presencia de valores atípicos (outliers) en múltiples columnas de consumo.
•	Solución: Al representar un porcentaje mínimo del total de los datos, se aplicaron técnicas de imputación y corrección, asegurando la integridad del modelo sin sesgar la información.
2. Segmentación de Clientes y Valor Comercial:
•	A través del cruce de variables de edad y nivel de uso, se identificaron 3 segmentos de clientes claros, destacando un comportamiento de uso alto en la mayoría de ellos.
•	El segmento más valioso para la compañía es el de adultos. Este grupo demográfico representa el mayor volumen de usuarios activos y la principal fuente de ingresos para ConnectaTel.
•	Patrón de Uso Extremo: La variable con mayor presencia de outliers fue la cantidad de minutos por llamada.
•	Impacto de Negocio: Este comportamiento implica una fuga potencial de ingresos o riesgo de insatisfacción si el usuario no tiene la tarifa correcta.
3. Recomendaciones Estratégicas para el Negocio:
•	Lanzamiento de un Plan Intermedio ("Plan Medio"): Actualmente la oferta puede ser muy drástica entre planes bajos y altos. Se sugiere crear un plan medio para alinear de forma justa la tarifa con el nivel de uso real detectado.
•	Estrategia de Up-selling para Usuarios Extremos: Desarrollar una campaña comercial dirigida exclusivamente a los clientes identificados con consumo extremo de minutos, ofreciéndoles una migración a planes Premium o ilimitados, aumentando así el ingreso por usuario.
