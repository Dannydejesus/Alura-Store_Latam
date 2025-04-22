# 📊 Análisis de Datos: Alura Store Latam

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-blueviolet)
![License](https://img.shields.io/badge/License-MIT-green)

Análisis completo de datos de ventas para Alura Store en Latinoamérica, incluyendo facturación por tienda, categorías de productos, calificaciones y costos de envío.

## 📌 Tabla de Contenidos
- [Objetivo](#-objetivo)
- [Datos](#-datos)
- [Análisis Realizados](#-análisis-realizados)
- [Resultados Clave](#-resultados-clave)
- [Visualizaciones](#-visualizaciones)
- [Requisitos](#-requisitos)
- [Instalación](#-instalación)
- [Uso](#-uso)
- [Licencia](#-licencia)

## 🎯 Objetivo
Analizar el desempeño de 4 tiendas de Alura Store en Latinoamérica para identificar:
- Facturación por tienda
- Categorías de productos más populares
- Calificaciones promedio
- Costos de envío
- Productos más y menos vendidos

## 📂 Datos
Los datos se obtuvieron de 4 archivos CSV públicos:
```python
tienda_1.csv
tienda_2.csv
tienda_3.csv
tienda_4.csv
```

Contienen información sobre:
- Productos y categorías
- Precios y costos de envío
- Fechas de compra
- Vendedores
- Ubicaciones (lat/lon)
- Métodos de pago
- Calificaciones

## 🔍 Análisis Realizados
1. **Facturación por tienda**
   - Cálculo del ingreso total por tienda
   - Identificación de la tienda con mayor facturación

2. **Ventas por categoría**
   - Conteo de productos vendidos por categoría
   - Identificación de categorías más populares

3. **Calificaciones promedio**
   - Cálculo del promedio de satisfacción del cliente

4. **Productos más/menos valorados**
   - Identificación de categorías con mayor/menor volumen de ventas

5. **Costos de envío**
   - Cálculo del costo promedio de envío por tienda

6. **Visualizaciones**
   - Gráficos de barras para facturación
   - Gráficos horizontales por categoría
   - Gráficos de pastel para calificaciones

## 📊 Resultados Clave
### Facturación Total
| Tienda | Facturación |
|--------|-------------|
| Tienda 1 | $1,150,880,400.00 |
| Tienda 2 | $1,116,343,500.00 |
| Tienda 3 | $1,098,019,600.00 |
| Tienda 4 | $1,038,375,700.00 |

**La tienda con mayor facturación fue Tienda 1**

### Categorías Más Populares
En todas las tiendas, **Muebles** fue la categoría más vendida:
- Tienda 1: 465 ventas
- Tienda 2: 442 ventas
- Tienda 3: 499 ventas
- Tienda 4: 480 ventas

### Calificaciones Promedio
| Tienda | Calificación Promedio |
|--------|-----------------------|
| Tienda 1 | 3.98 |
| Tienda 2 | 4.04 |
| Tienda 3 | 4.05 |
| Tienda 4 | 4.00 |

**Tienda 3 obtuvo la mejor calificación promedio (4.05)**

## 📈 Visualizaciones
El proyecto incluye visualizaciones interactivas con Matplotlib:
1. Facturación total por tienda (gráfico de barras)
2. Distribución de categorías por tienda (gráficos horizontales)
3. Costo promedio de envío (gráfico de barras horizontales)
4. Calificaciones promedio (gráfico de pastel)

## ⚙️ Requisitos
- Python 3.8+
- Pandas 1.3+
- Matplotlib 3.5+
- Jupyter Notebook (opcional)

## 💻 Instalación
```bash
git clone https://github.com/tu-usuario/alura-store-analysis.git
cd alura-store-analysis
pip install -r requirements.txt
```

## 🚀 Uso
Ejecutar en Jupyter Notebook o directamente con Python:
```python
python alura_store_analysis.py
```

## 📜 Licencia
Este proyecto está bajo la licencia MIT. Ver [LICENSE](LICENSE) para más detalles.

## 📧 Contacto
Para preguntas o colaboraciones:
- Email: tu-email@dominio.com
- LinkedIn: [Tu Nombre](https://linkedin.com/in/tu-perfil)
