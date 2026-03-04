# 🏪 Alura Store LATAM - Análisis Estratégico de Tiendas

## 📌 Propósito del Proyecto

Este proyecto tiene como objetivo realizar un análisis exploratorio y
estratégico de datos de cuatro tiendas pertenecientes a Alura Store
LATAM.

El análisis fue desarrollado para apoyar la toma de decisiones
estratégicas, identificando cuál tienda presenta menor desempeño
financiero y operativo.

Se analizaron cinco aspectos clave:

1.  📊 Facturación total por tienda\
2.  🛍️ Categorías más populares\
3.  ⭐ Promedio de evaluación de clientes\
4.  📦 Productos más y menos vendidos\
5.  🚚 Costo promedio de envío

------------------------------------------------------------------------

## 📂 Estructura del Proyecto

alura-store-analisis/ │ ├── README.md ├── AluraStore_Analisis.ipynb ├──
data/ │ ├── tienda_1.csv │ ├── tienda_2.csv │ ├── tienda_3.csv │ └──
tienda_4.csv └── img/ ├── facturacion.png ├── evaluaciones.png └──
envio.png

------------------------------------------------------------------------

## 📊 Principales Insights

### 1️⃣ Facturación Total

Se identificó la tienda con mayor y menor generación de ingresos
mediante el cálculo: Precio × Cantidad.

Insight: La tienda con menor facturación representa el primer indicador
de bajo desempeño financiero.

### 2️⃣ Categorías Más Populares

Se agruparon las ventas por categoría y se sumaron las cantidades
vendidas.

Insight: Algunas tiendas dependen de pocas categorías, lo que puede
representar riesgo comercial.

### 3️⃣ Evaluación Promedio

Se calculó la media de las evaluaciones de clientes.

Insight: Existe relación entre satisfacción del cliente y desempeño
comercial.

### 4️⃣ Productos Más y Menos Vendidos

Se identificaron los productos con mayor y menor rotación.

Insight: Los productos de baja rotación pueden afectar la rentabilidad.

### 5️⃣ Costo Promedio de Envío

Se calculó el promedio de costo logístico por tienda.

Insight: Costos logísticos elevados pueden reducir competitividad y
margen.

------------------------------------------------------------------------

## 🎯 Conclusión Estratégica

El análisis integral permite recomendar la venta o reestructuración de
la tienda con menor eficiencia global, considerando facturación,
evaluación, logística y rotación de productos.

------------------------------------------------------------------------

## ⚙️ Instrucciones de Ejecución

### Google Colab

1.  Subir el notebook AluraStore_Analisis.ipynb a Colab.
2.  Verificar rutas de archivos CSV.
3.  Ejecutar todas las celdas en orden.

### Entorno Local

1.  Clonar repositorio.
2.  Instalar dependencias:

pip install pandas matplotlib

3.  Ejecutar:

jupyter notebook

------------------------------------------------------------------------

## 🛠️ Tecnologías Utilizadas

-   Python 3
-   Pandas
-   Matplotlib
-   Google Colab
-   GitHub

------------------------------------------------------------------------

Proyecto desarrollado como parte del Challenge de Data Science LATAM.
