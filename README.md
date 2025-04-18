# Análisis de Datos de Tiendas

## Propósito del Análisis

Este proyecto tiene como objetivo analizar los datos de ventas de cuatro tiendas para extraer insights comerciales valiosos que puedan ayudar a mejorar el rendimiento, la satisfacción del cliente y la rentabilidad. A través de múltiples análisis específicos, buscamos entender patrones de venta, preferencias de los clientes, rentabilidad de productos y eficiencia logística.

## Estructura del Proyecto

```
├── data/                    # Archivos de datos
│   ├── tienda.csv           # Datos de la primera tienda
│   ├── tienda2.csv          # Datos de la segunda tienda
│   ├── tienda3.csv          # Datos de la tercera tienda
│   └── tienda4.csv          # Datos de la cuarta tienda
├── notebooks/               # Jupyter notebooks con análisis
│   └── analisis_tiendas.ipynb  # Notebook principal con todos los análisis
├
└── README.md                # Este archivo
```

## Análisis Realizados

El proyecto incluye cinco análisis clave:

### 1. Análisis de Ingresos Totales

Calcula el ingreso total generado por cada tienda, permitiendo identificar cuáles son las más rentables y establecer comparativas de desempeño financiero.

### 2. Análisis de Productos por Categoría

Identifica qué categorías de productos son más populares en cada tienda, lo que facilita decisiones sobre inventario y marketing específico por ubicación.

### 3. Análisis de Satisfacción del Cliente

Evalúa las calificaciones promedio de los clientes por tienda y por categoría de producto, proporcionando insights sobre la percepción de calidad y servicio.

### 4. Análisis de Productos Más y Menos Vendidos

Identifica los productos específicos con mejor y peor desempeño en cada tienda, ayudando a optimizar el inventario y las estrategias de promoción.

### 5. Análisis de Costos de Envío

Calcula el costo de envío promedio para cada tienda, permitiendo evaluar la eficiencia logística y oportunidades de optimización de costos.

## Ejemplos de Visualizaciones e Insights

### Ingreso Total por Tienda


*Ejemplo de insight: La Tienda 1 genera ingresos significativamente mayores que las demás, lo que podría deberse a su ubicación estratégica o a una mayor variedad de productos premium.*

### Categorías Más Populares por Tienda


*Ejemplo de insight: Todas las tiendas muestran un patrón consistente en las categorías más vendidas, siguiendo este orden de popularidad: Muebles, Electrónicos, Juguetes, Electrodomésticos, y Deportes y diversión. Esta uniformidad sugiere una demanda estable de estas categorías independientemente de la ubicación de la tienda.*

### Satisfacción del Cliente


*Ejemplo de insight: Las Tiendas 3 y 4 mantienen las calificaciones más altas, lo que indica una posible ventaja en servicio al cliente o calidad de productos en estas ubicaciones. Esto podría servir como modelo para mejorar la experiencia del cliente en las otras tiendas.*

## Instrucciones para Ejecutar el Análisis

### Prerrequisitos

- Python 3.8 o superior
- Pandas
- Matplotlib
- Seaborn

### Instalación

1. Clone este repositorio:
   ```
   git clone https://github.com/hernanschimpf/challenge1-data-science-latam-main.git
   cd challenge1-data-science-latam-main
   -para ver los graficos:
   cd challenge1-data-science-latam-main\visualizaciones
   ```

2. Instale las dependencias:
   ```
   pip install pandas matplotlib seaborn numpy
   ```

### Ejecución

1. Para ejecutar todos los análisis desde el notebook principal:
   ```
   jupyter notebook notebooks/analisis_tiendas.ipynb
   ```
