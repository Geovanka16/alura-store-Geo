## 🛍️ Challenge: Alura Store - By Geo

---

### 🎯 Propósito del Análisis

El objetivo principal de este proyecto es realizar un análisis exhaustivo del rendimiento de **cuatro tiendas** de **Alura Store** para ayudar al Sr. Juan a tomar una decisión estratégica: **determinar cuál de las cuatro tiendas debe vender** para invertir en un nuevo negocio.

El análisis se centra en cinco aspectos clave para identificar la tienda con el menor desempeño y justificar la decisión:

1.  **Facturación Total:** Determinar la tienda con el **mayor y menor ingreso total**.
2.  **Ventas por Categoría:** Identificar los productos y **categorías más vendidas** en cada tienda.
3.  **Evaluación Promedio:** Calcular el **promedio de las evaluaciones** para medir la satisfacción del cliente.
4.  **Productos Vendidos:** Conocer los productos específicos con el **mayor y menor volumen de ventas**.
5.  **Costo Promedio de Envío:** Calcular el **costo promedio del envío** por cada tienda.

---

### 📂 Estructura del Repositorio y Archivos

Este repositorio contiene el código fuente, las versiones de desarrollo y el informe final del proyecto.

* `README.md`
    * Documentación del proyecto (este archivo).
* `AluraStoreLatam (1).ipynb`
    * Versión inicial o borrador del análisis.
* `AluraStoreLatam (2).ipynb`
    * **Notebook principal** con la versión final del análisis, todos los gráficos y el informe ejecutivo.

**Nota sobre los datos:** Los datos de las cuatro tiendas (Tienda 1 a Tienda 4) fueron importados directamente desde las URL públicas de GitHub.

### 📝 Índice del Notebook `AluraStoreLatam (2).ipynb`

El análisis se desarrolla de forma secuencial, siguiendo la estructura del *notebook* final:

| Sección | Descripción |
| :--- | :--- |
| **Importación de datos** | Carga de los DataFrames desde las URLs de GitHub. |
| **1. Análisis de facturación** | Cálculo y presentación del ingreso total de cada tienda. |
| **2. Ventas por categoría** | Conteo de las categorías para obtener el Top 3 de cada tienda. |
| **3. Calificación promedio de la tienda** | Cálculo de la media de la columna `Calificación`. |
| **4. Productos más y menos vendidos** | Identificación del producto que más y menos se vende por volumen. |
| **5. Envío promedio por tienda** | Cálculo del costo promedio de la columna `Costo_Envio`. |
| **6. Visualizaciones Clave** | Generación de al menos tres tipos de gráficos (Barras, Dispersión, Pastel) para los insights más relevantes. |
| **Informe final** | Conclusión ejecutiva, justificación y recomendación de venta al Sr. Juan. |

---

### 📈 Visualizaciones e Insights Destacados

El análisis utiliza tres tipos de gráficos para comunicar los hallazgos:

1.  **Gráfico de Barras:** Muestra la comparación directa de la **Facturación Total** por tienda, destacando visualmente la unidad de menor rendimiento.
2.  **Gráfico de Dispersión (Scatter Plot):** Combina la **Evaluación Promedio** (satisfacción) vs. la **Facturación** para identificar la relación riesgo-rendimiento en cada tienda.
3.  **Gráfico de Pastel (Pie Chart):** Detalla la **Distribución Porcentual de Categorías** de la **Tienda 4** (candidata a la venta), para entender la composición de sus ingresos.

### 💻 Instrucciones para Ejecutar el Análisis

Para revisar o replicar el análisis completo:

1.  **Abrir el Notebook:** Accede al archivo `AluraStoreLatam (2).ipynb`.
2.  **Entorno:** El código está diseñado para ejecutarse completamente en **Google Colab**.
3.  **Ejecución:** Ejecuta las celdas del *notebook* de forma secuencial. La primera sección importa los datos directamente desde las URLs de GitHub, por lo que no es necesario descargar archivos CSV. El *notebook* produce todos los cálculos, gráficos y el **Informe Final** con la recomendación.
