# 📊 Informe de Análisis - Alura Store Latam

Este proyecto presenta un análisis detallado del desempeño de las cuatro tiendas de la cadena **Alura Store**, con el propósito de identificar cuál tienda debería ser vendida para liberar recursos destinados a un nuevo emprendimiento. Incluye indicadores clave como **facturación, ventas por categoría, calificaciones de clientes y costos logísticos**, respaldados por visualizaciones claras y concisas.

---

## 📌 Tabla de Contenidos
1. [Descripción](#descripción)
2. [Características](#características)
3. [Tecnologías Utilizadas](#tecnologías-utilizadas)
4. [Instalación](#instalación)
5. [Uso](#uso)
6. [Estructura del Proyecto](#estructura-del-proyecto)
7. [Análisis Detallado](#análisis-detallado)
8. [Conclusión y Recomendación](#conclusión-y-recomendación)
9. [Contacto](#contacto)

---

## Descripción
El objetivo de este análisis es evaluar el desempeño de las tiendas de **Alura Store** para ayudar a mi cliente el **Sr. Juan** a decidir cuál tienda vender y destinar los recursos hacia un nuevo emprendimiento. El enfoque incluye:
- Comparación de indicadores clave como facturación, volumen de ventas y satisfacción del cliente.
- Uso de gráficos y visualizaciones para identificar patrones y tomar decisiones fundamentadas.

---

## Características
- 🔻 **Identificación de la tienda menos eficiente.**
- 📊 **Visualización de datos** con gráficos claros y llamativos.
- 🛍️ **Comparación por categoría de productos.**
- ⭐ **Análisis de satisfacción del cliente.**
- 🚚 **Evaluación de costos logísticos.**

---

## Tecnologías Utilizadas
- **Python 3.x**  
- **Pandas:** Para manipulación y análisis de datos.  
- **Matplotlib:** Creación de gráficos claros y funcionales.  
- **Seaborn:** Visualizaciones avanzadas para análisis estadístico.

---

## Instalación
Sigue estos pasos para ejecutar el proyecto en tu entorno:

1. Clona este repositorio:  
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
   ```
2. Crea y activa un entorno virtual (opcional):  
   ```bash
   python -m venv env
   source env/bin/activate  # En Linux/Mac
   env\Scripts\activate  # En Windows
   ```
3. Instala las dependencias necesarias:  
   ```bash
   pip install -r requirements.txt
   ```

---

## Uso
1. Ejecuta el análisis principal:  
   ```bash
   python main.py
   ```
2. Revisa las visualizaciones generadas en la carpeta `output/`.
3. Consulta los gráficos y tablas en los notebooks de la carpeta `notebooks/`.

---

## Estructura del Proyecto
```
AluraStoreLatam/
├── data/            # Datos en bruto y procesados
├── notebooks/       # Jupyter Notebooks con análisis detallado
├── src/             # Scripts del proyecto
│   ├── data_processing.py  # Limpieza y preprocesamiento de datos
│   ├── visualization.py    # Gráficos y visualizaciones
├── README.md        # Documentación del proyecto
├── requirements.txt # Dependencias del proyecto
├── main.py          # Script principal para ejecutar el análisis
```

---

## Análisis Detallado

### 💰 Facturación Total (USD)  
| 🏆 Tienda       | 💵 Facturación       | 📉 Diferencia vs Tienda 1   |
|-----------------|---------------------|----------------------------|
| 🥇 **Tienda 1** | $1,150,880,400.00   | -                          |
| 🥈 **Tienda 2** | $1,116,343,500.00   | -$34.5 millones            |
| 🥉 **Tienda 3** | $1,098,019,600.00   | -$52.8 millones            |
| ❌ **Tienda 4** | $1,038,375,700.00   | -$112.5 millones           |

📌 **Observación:** La **Tienda 4 genera 9.8% menos ingresos** que la Tienda 1, siendo la menos rentable.

### 🛍️ Ventas por Categoría  
**Categoría más vendida en todas las tiendas:** 🪑 **Muebles**

| 🛒 **Tienda**   | 📦 **Unidades Vendidas** |
|-----------------|--------------------------|
| 🥇 **Tienda 3** | 499 unidades (mejor desempeño) |
| ❌ **Tienda 4** | 480 unidades             |

**Categoría más débil en Tienda 4:** 🎵 **Instrumentos Musicales**: solo **170 unidades vendidas**.

### ⭐ Calificación Promedio de Clientes  
| 🏆 **Tienda**   | ⭐ **Calificación Promedio** |
|-----------------|-----------------------------|
| 🥇 **Tienda 3** | 4.05                        |
| 🥈 **Tienda 2** | 4.04                        |
| ❌ **Tienda 4** | 4.00                        |
| 🥉 **Tienda 1** | 3.98                        |

### 🚚 Costo Promedio de Envío (USD)  
| 🏆 **Tienda**   | 🚛 **Costo Promedio**       |
|-----------------|----------------------------|
| 🥇 **Tienda 4** | $23,459.46 (el más bajo)   |
| 🥈 **Tienda 3** | $24,805.68                 |
| 🥉 **Tienda 2** | $25,216.24                 |
| ❌ **Tienda 1** | $26,018.61                 |

---

## ✅ Conclusión y Recomendación Final  

- Proceder con la **venta de la Tienda 4**.  
- Liberar recursos para invertir en las tiendas más eficientes o iniciar un nuevo proyecto empresarial.  
- Las Tiendas 1, 2 y 3 tienen mejor desempeño y potencial de crecimiento.

---

## Contacto  
- **Autor:** Danny Gonzalez
- **Email:** dannyg260580@hotmail.com  
- **Linkedin:** https://www.linkedin.com/in/danny-gonz%C3%A1lez-352744244/  
