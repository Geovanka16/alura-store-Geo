## 🛍️ Challenge: Alura Store - By Geo

---

### 🎯 Propósito del Análisis

El objetivo principal de este proyecto es realizar un análisis exhaustivo del rendimiento de **cuatro tiendas** de **Alura Store** para ayudar al Sr. Juan a tomar una decisión estratégica: **determinar cuál de las cuatro tiendas debe vender** para invertir en un nuevo negocio.

El análisis se centrará en cinco aspectos clave para identificar la tienda con el menor desempeño y fundamentar la decisión:

1.  **Facturación Total:** Determinar cuál tienda genera el **mayor y menor ingreso total**.
2.  **Categorías Populares:** Identificar los tipos de productos (**categorías**) más vendidos en cada tienda.
3.  **Evaluación Promedio de Clientes:** Calcular el **promedio de las evaluaciones** de los clientes para medir la satisfacción.
4.  **Productos Más y Menos Vendidos:** Conocer los productos específicos con el **mayor y menor volumen de ventas** en cada tienda.
5.  **Costo Promedio de Envío:** Calcular el **costo promedio del envío** desde cada tienda hasta el cliente.

---

### 📂 Estructura del Proyecto y Organización de Archivos

Este proyecto sigue una estructura simple y enfocada en el entorno de análisis de datos con Google Colab:

| Archivo/Carpeta | Descripción |
| :--- | :--- |
| **`Alura_Store_Latam.ipynb`** | Contiene el código Python para la **carga de datos**, la **limpieza**, el **análisis exploratorio de datos (EDA)**, la **visualización** y la **conclusión final** sobre qué tienda vender. |
| **`README`** | Estás en el ahora mismo :stuck_out_tongue_winking_eye:. |

---

### 📈 Ejemplos de Gráficos e Insights Obtenidos

A continuación, se presentan ejemplos de visualizaciones e *insights* clave que se obtuvieron durante el análisis:

#### **Facturación Total por Tienda**
* **Gráfico:** Un **gráfico de barras** es utilizado para comparar visualmente la facturación total generada por cada una de las cuatro tiendas.
* **Insight Clave:** La **Tienda 3** se identifica como la que posee la facturación total más baja, marcando una brecha significativa que apunta a la Tienda 3 como candidata a ser vendida.

#### **Categorías Más Populares (Productos Vendidos) por Tienda**
* **Gráfico:** Se emplean **gráficos de pastel (pie charts)** o **gráficos de barras apiladas** para mostrar la distribución porcentual de ventas por categoría dentro de cada tienda.
* **Insight Clave:** En la Tienda con menor rendimiento (Tienda 3), la categoría **"Electrónica"** representa un porcentaje desproporcionadamente bajo de sus ventas totales, sugiriendo un enfoque comercial deficiente en ese segmento.

#### **Costo Promedio de Envío**
* **Gráfico:** Un **gráfico de caja (boxplot)** o un **gráfico de barras** simple compara el costo promedio de envío de cada tienda.
* **Insight Clave:** La **Tienda 4** registra el **costo promedio de envío más alto**, lo que podría estar afectando la competitividad de sus precios finales y la satisfacción del cliente.

---

### 💻 Instrucciones para Ejecutar el Notebook

Para replicar y ejecutar el análisis, sigue los siguientes pasos:

1.  **Obtener los Archivos:** Asegúrate de tener clonado o descargado el repositorio de GitHub que contiene el archivo **`Alura_Store_Latam.ipynb`**.
2.  **Abrir en Google Colab:**
    * Ve a [Google Colab](https://colab.research.google.com/).
    * Haz clic en "Archivo" > "Abrir notebook".
    * Sube el archivo **`Alura_Store_Latam.ipynb`** desde tu unidad local.
3.  **Montar Google Drive (Opcional):** El *notebook* está configurado para ejecutarse directamente si los archivos CSV se suben a Google Colab o si se montan desde Google Drive. Las primeras celdas contienen el código para **montar Drive**. Si usas Colab, asegúrate de que los archivos de la base de datos estén en la ruta correcta, o ajusta la ruta de lectura en la celda correspondiente.
4.  **Ejecutar las Celdas:** Ejecuta las celdas del *notebook* de forma secuencial, desde la importación de librerías hasta la conclusión final.

Una vez ejecutado, el *notebook* presentará las conclusiones y la recomendación final al Sr. Juan sobre la tienda que debe vender.
