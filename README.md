# Segmentación de clientes con RFM y clustering

Este proyecto de análisis de datos tiene como objetivo segmentar a los clientes de un negocio de retail en línea utilizando técnicas de aprendizaje no supervisado. Se emplea el enfoque RFM (Recency, Frequency, Monetary) para agrupar a los clientes según su comportamiento de compra histórico, lo cual permite generar estrategias de marketing más efectivas y personalizadas.

---

## 📊 Descripción del Proyecto

A partir del conjunto de datos **Online Retail Dataset** de transacciones reales de un e-commerce del Reino Unido entre 2010 y 2011, se desarrolló un proceso detallado que incluyó:

- Limpieza y preprocesamiento de datos (eliminación de valores nulos, transacciones no representativas como `POST`, `BANK CHARGES`, `C2`, etc.).
- Cálculo de métricas RFM por cliente:
  - **Recency**: días desde la última compra.
  - **Frequency**: número total de compras realizadas.
  - **Monetary**: monto total gastado.
- Estandarización de los valores RFM.
- Aplicación de algoritmos de clustering (K-Means).
- Evaluación de los clusters mediante **Silhouette Score** y análisis visual (gráficos 2D y 3D).
- Análisis e interpretación del comportamiento de los diferentes grupos de clientes.
- Generación de insights para la toma de decisiones orientadas a la retención y fidelización de clientes.

Este enfoque permitió clasificar a los clientes en segmentos como compradores frecuentes y valiosos, clientes inactivos, o clientes con potencial de crecimiento, lo cual facilita la creación de campañas dirigidas basadas en sus patrones de compra.

---

## 🧠 Principales Hallazgos

- El análisis RFM facilita entender qué segmentos deben ser priorizados para retención, reactivación o promoción.
- Los resultados pueden ser utilizados para personalizar estrategias de CRM, email marketing, ofertas exclusivas y asignación de recursos.

---

## 📈 Visualización y Evaluación

- Se utilizó el **Silhouette Score** para determinar la calidad de la segmentación.
- Se crearon gráficos de dispersión 2D y 3D para visualizar la distribución de clientes por clústeres.
- Los segmentos fueron interpretados con base en su posición en el espacio RFM.

---

## 🚀 Posibilidades Futuras

- Aplicar técnicas avanzadas de segmentación como DBSCAN o clustering jerárquico.
- Integrar variables adicionales como país, categoría de producto o frecuencia mensual.
- Implementar recomendaciones personalizadas y A/B testing en campañas reales.
- Conectar con herramientas de automatización de marketing (ej. Mailchimp) para acciones dirigidas.

---

## ⚙️ Tecnologías utilizadas

- Python (Pandas, NumPy, Scikit-Learn)
- Matplotlib / Seaborn / Plotly para visualizaciones
- Jupyter Notebook para desarrollo interactivo

---

## 📫 Contacto

**Cesar Eduardo Cruz Cabrera**  
📧 cesareduardocruzcabrera@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/cesar-eduardo-cruz-cabrera)

