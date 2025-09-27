# 📊 Proyecto: Sistema de Gestión de Datos con Algoritmos Optimizados

## 📌 Descripción

Este proyecto implementa un sistema en **Python** para el análisis y
comparación de algoritmos de **ordenamiento y búsqueda**. Forma parte
del taller de la asignatura **Diseño Funcional** y tiene como objetivo
aplicar estructuras de datos, medición de rendimiento y visualización de
resultados.

El sistema incluye: - Generación de datasets con diferentes
distribuciones (uniforme, gaussiana y sesgada). - Implementación de
algoritmos de ordenamiento (Insertion Sort, Quick Sort y Merge Sort). -
Búsquedas lineal y binaria. - Análisis comparativo de tiempos de
ejecución. - Visualización de resultados con gráficas. - Exportación de
datasets en formato CSV. - Aplicación práctica a un sistema de **gestión
de inventario**.

---

## ⚙️ Requisitos

- Python 3.8 o superior\

- Librerías necesarias:

  ```bash
  pip install numpy pandas matplotlib seaborn reportlab
  ```

---

## 🚀 Ejecución en Google Colab

1.  Sube el archivo del proyecto a Google Colab.\
2.  Ejecuta cada celda en orden (desde **Módulo 1** hasta el **Módulo
    Extra**).\
3.  Los datasets se guardarán en la carpeta `datasets/`.\
4.  Las gráficas generadas se mostrarán en pantalla y también se pueden
    guardar como PNG.

---

## 📂 Estructura del Proyecto

    proyecto_algoritmos/
    │── datasets/                  # Archivos CSV generados automáticamente
    │── informe_tecnico_algoritmos.pdf   # Informe técnico (2-3 páginas)
    │── analisis_completo.ipynb    # Notebook en Google Colab con todo el código
    │── README.md                  # Este archivo
    │── screenshots/               # Capturas de gráficas y evidencias

---

## 📈 Resultados principales

- **Insertion Sort**: eficiente en datasets pequeños, pero ineficiente
  en grandes.\
- **Quick Sort**: el más rápido en la mayoría de los escenarios.\
- **Merge Sort**: desempeño estable y consistente, aunque ligeramente
  más lento que Quick Sort.

En la aplicación práctica de inventario:\

- Se implementó una clase `Producto` con atributos clave.\
- Se generaron 1000 productos aleatorios.\
- Se realizaron ordenamientos por precio y nombre.\
- Se implementó búsqueda por rango de precios y se extrajo el **Top 10
  de productos más vendidos**.

---

## 📜 Créditos

**Autor:** Ángel Nicolás Riaño Guzmán\ Jhon Alexander Rodriguez Rodriguez
**Asignatura:** Diseño Funcional\
**Proyecto:** Taller de Vectores y Algoritmos de Búsqueda/Ordenamiento
