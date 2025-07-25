# Análisis Estratégico de Precios para FRESCORP S.A.

Este repositorio contiene un análisis de datos exploratorio para **FRESCORP S.A.**, una cadena de supermercados **ficticia** que busca lanzar una nueva línea de negocio de frutas y hortalizas. El objetivo del proyecto es utilizar datos públicos de precios mayoristas para desarrollar una estrategia de negocio inicial.

<img width="698" height="312" alt="image" src="https://github.com/user-attachments/assets/fc8291fc-8f2d-445f-a4db-a3947996f38e" />


---

**FRESCORP S.A.** es una cadena de supermercados con fuerte presencia en abarrotes y carnes, pero sin experiencia en el volátil mercado de productos frescos. Para lanzar su nueva sección **"FRESCORP Verde"**, la gerencia necesita un plan basado en datos para definir su cartera de productos inicial, establecer una estrategia de precios y optimizar su cadena de suministro, asegurando la rentabilidad y competitividad del proyecto.

---

## Objetivos 

El análisis se centra en responder preguntas críticas de negocio en tres áreas fundamentales:

## Preguntas Clave

####  Cartera de Productos
* ¿Qué productos tienen el menor costo de adquisición promedio?
* ¿Cuáles son los productos más importantes por volumen de comercialización?
* ¿Qué productos ofrecen la mayor diversidad de variedades?

####  Estrategia de Precios y Promociones
* ¿Cuáles son los meses de "temporada baja" para los productos populares?
* ¿Qué productos sufren las mayores alzas de precio?

####  Optimización de la Cadena de Suministro
* ¿Hay días o quincenas con precios consistentemente más bajos?
* ¿En qué mercados es más barato comprar productos clave?

---

## Herramientas y Habilidades

* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn
* **Técnicas:**
    * Limpieza y Preprocesamiento de Datos
    * Ingeniería de Características (Feature Engineering)
    * Análisis Exploratorio de Datos (EDA)
    * Visualización de Datos
    * Análisis de Series de Tiempo

---

## Proceso de Análisis

1.  **Limpieza y Preparación:** Se realizó una limpieza exhaustiva de los datos, incluyendo la conversión de tipos de datos, el renombrado de columnas a formato `snake_case` y el manejo de valores atípicos.
2.  **Estandarización de Unidades:** El paso más crítico fue la estandarización de la columna `unidad_de_comercializacion`. Se crearon las métricas **`precio_por_kg`** y **`precio_por_unidad`** para permitir comparaciones justas entre todos los productos.
3.  **Análisis Exploratorio (EDA):** Se utilizaron diversas técnicas de visualización para responder a cada una de las preguntas de negocio, identificando patrones de estacionalidad, volatilidad y diferencias geográficas en los precios.
4.  **Análisis Combinado:** Finalmente, se creó un **ranking de "productos ideales"**, combinando las métricas de costo, volumen y estabilidad para identificar las mejores opciones para la cartera de productos.

---

## Data set

Kaggle 
https://www.kaggle.com/datasets/ricardourdaneta/precio-mayorista-de-frutas-y-hortalizas-2025
