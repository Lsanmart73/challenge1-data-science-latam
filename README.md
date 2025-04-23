#  Análisis de Rendimiento de Tiendas

Este proyecto presenta un análisis de datos de las cuatro tiendas de Alura Store con el objetivo de comprender su desempeño en términos de ventas, satisfacción del cliente, costos de envío y productos vendidos. A través de gráficos, métricas y recomendaciones, se determina qué tienda presenta el rendimiento más bajo y podría considerarse para cierre.

---

## Propósito del Análisis

El análisis busca:

- Explorar los datos de ventas, calificaciones, costos logísticos y productos vendidos.
- Visualizar y comparar métricas clave por tienda.
- Identificar fortalezas y debilidades de cada punto de venta.
- Entregar una **recomendación basada en datos** sobre qué tienda cerrar.

---

## Estructura del Proyecto

```
alura-store/
│
├── data/
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
│
├── notebooks/
│   └── alura_store_analysis.ipynb        # Notebook principal con análisis completo
│
├── output/
│   └── Informe_Tiendas_Recomendacion_Cierre.docx  # Informe final en Word
│
└── README.md                             # Documentación del proyecto
```

---

##  Ejemplos de Gráficos e Insights

### Ventas por Categoría (Tienda 1)
Muestra qué tipo de productos tienen mayor rotación, lo cual permite orientar estrategias de stock.

### Calificación Promedio por Tienda
Permite evaluar la experiencia del cliente. La Tienda 1 presenta la mejor calificación, mientras que la Tienda 4 muestra una calificación baja que debe ser analizada.

### Envío Promedio por Tienda
Comparativa del costo logístico entre tiendas. Tienda 4 es la que presenta mayor costo en promedio.

### Producto Más y Menos Vendido
Visualización de los productos con mejor y peor desempeño en ventas por tienda.

 **Recomendación Final:** Cerrar la Tienda 4, ya que presenta bajos ingresos, calificaciones negativas y altos costos logísticos.

---

##  Instrucciones para Ejecutar el Notebook

### Requisitos:
- Python 3.8 o superior
- Jupyter Notebook o JupyterLab

### Instalación de librerías necesarias:
```bash
pip install pandas matplotlib seaborn
```

### Ejecutar el notebook:
```bash
jupyter notebook notebooks/alura_store_analysis.ipynb
```

---

