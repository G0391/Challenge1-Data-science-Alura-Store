# 📊 Reestructuración Estratégica de Alura Store: Identificación de la Tienda de Menor Rendimiento

## 🎯 Objetivo del Proyecto

Este proyecto de **Análisis de Datos y Estrategia de Negocios** tiene como objetivo principal ayudar al Sr. Juan, dueño de la cadena Alura Store, a tomar una decisión crucial de desinversión. Mediante un análisis exhaustivo del rendimiento de las cuatro tiendas de la cadena, identificaremos la tienda menos eficiente para recomendar su venta, permitiendo capitalizar el activo e iniciar un nuevo emprendimiento.

## 📈 Métricas Clave Analizadas

- **Volumen de Ingresos**: Facturación total por tienda
- **Costos Operativos**: Costos promedio de envío
- **Satisfacción del Cliente**: Calificación media de los clientes
- **Desempeño por Categoría**: Ventas por línea de productos
- **Eficiencia Operativa**: Relación ingresos vs costos

## 🏪 Resumen Ejecutivo de Resultados

### 📊 Desempeño Financiero por Tienda

| Tienda | Ingresos Totales | Participación | Costo Envío Promedio | Calificación Clientes |
|--------|------------------|---------------|---------------------|---------------------|
| **Tienda 1** | $1,150,880,400 | 26.13% | $26,018.61 | 3.98 ⭐ |
| **Tienda 2** | $1,116,343,500 | 25.35% | $25,216.24 | 4.04 ⭐ |
| **Tienda 3** | $1,098,019,600 | 24.93% | $24,805.68 | 4.05 ⭐ |
| **Tienda 4** | $1,038,375,700 | 23.58% | $23,459.46 | 4.00 ⭐ |

### 🎯 Hallazgos Principales

1. **Líder en Ingresos**: Tienda 1 ($1,150M - 26.13% participación)
2. **Menor Rendimiento**: Tienda 4 ($1,038M - 23.58% participación)
3. **Mejor Satisfacción**: Tienda 3 (4.05 puntos)
4. **Costos Más Eficientes**: Tienda 4 ($23,459 costo envío promedio)

## 🔍 Metodología de Análisis

### 🧹 Limpieza y Transformación
- Conversión de fechas a formato datetime
- Estandarización de nombres de columnas
- Validación de integridad de datos (sin valores nulos)

### 📊 Análisis Realizados
1. **Análisis de Facturación**: Cálculo de ingresos totales y comparativos
2. **Ventas por Categoría**: Identificación de productos más y menos vendidos
3. **Eficiencia Operativa**: Costos de envío vs ingresos generados
4. **Satisfacción del Cliente**: Análisis de calificaciones promedio
5. **Visualización Comparativa**: Gráficos para análisis multivariable

## 📈 Principales Hallazgos por Categoría

### 🏆 Productos Más Vendidos
- **Todas las tiendas**: "Muebles" como categoría líder
- **Consistencia**: Muebles > Electrónicos > Juguetes (patrón similar)

### 📉 Productos Menos Vendidos
- **Tiendas 1-2**: Artículos para el hogar
- **Tiendas 3-4**: Instrumentos musicales

## 🗺️ Análisis Geográfico y Operativo

### 💰 Relación Ingresos vs Costos
- **Tienda 1**: Alto ingreso pero mayor costo operativo
- **Tienda 4**: Menor ingreso pero costos más eficientes
- **Tienda 3**: Balance óptimo entre ingresos y satisfacción

## 🎨 Visualizaciones Implementadas

1. **Gráficos de Barras Horizontales**: Ventas por categoría por tienda
2. **Gráficos de Torta**: Distribución porcentual de ventas
3. **Gráficos Comparativos**: Ingreso promedio vs costo de envío
4. **Análisis en Escala Logarítmica**: Para mejor visualización de grandes volúmenes

## 💡 Recomendación Estratégica

**Tienda Recomendada para Desinversión: Tienda 4**

### 🔍 Justificación:
- **Menor volumen de ingresos** ($1,038M vs promedio $1,101M)
- **Participación más baja** en ingresos consolidados (23.58%)
- **Aunque tiene costos eficientes**, no compensa el menor rendimiento
- **Calificación media** (4.00) sin destacar significativamente

### 📊 Impacto Esperado:
- Liberación de capital para nuevo emprendimiento
- Enfoque en tiendas con mayor potencial de crecimiento
- Optimización de estructura operativa

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas**: Manipulación y análisis de datos
- **Matplotlib**: Visualizaciones y gráficos
- **Jupyter Notebook**: Entorno de desarrollo
- **Git/GitHub**: Control de versiones

## 👥 Equipo y Colaboración

- **Gestión de Proyecto**: Trello - Metodologías ágiles
- **Almacenamiento**: Google Drive
- **Control de Versiones**: GitHub

---

*Este análisis proporciona una base cuantitativa sólida para la toma de decisiones estratégicas, combinando rigor analítico con visión de negocio.*
