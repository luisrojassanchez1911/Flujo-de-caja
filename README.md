# Flujo-de-caja
📈 Automatización y Análisis de Flujo de Caja con Python para Contadores
## Visión General del Proyecto

Este proyecto demuestra cómo se puede apalancar Python, la librería Pandas y herramientas de visualización de datos para automatizar el procesamiento de transacciones financieras y generar un informe de flujo de caja mensual claro y conciso, junto con visualizaciones intuitivas. Está diseñado para profesionales de la contabilidad y finanzas que buscan mejorar la eficiencia y obtener insights más rápidos de sus datos transaccionales.

## Problema Resuelto

En muchas organizaciones, la preparación de informes financieros como el flujo de caja puede ser un proceso manual, propenso a errores y que consume mucho tiempo, especialmente cuando se manejan grandes volúmenes de transacciones. Este script automatiza este proceso, transformando datos brutos de transacciones en un informe estructurado y visualizaciones que facilitan la toma de decisiones financieras.

## Habilidades Demostradas

-   **Análisis de Datos con Pandas:** Lectura, limpieza, transformación (conversión de tipos de datos, extracción de año/mes) y agregación de datos (`groupby`, `merge`).
-   **Generación de Informes:** Creación de tablas de resumen financiero.
-   **Visualización de Datos:** Uso de Matplotlib y Seaborn para crear gráficos significativos (flujo de caja neto, ingresos vs. egresos).
-   **Automatización de Tareas:** Exportación de resultados a archivos Excel.
-   **Gestión de Errores Básica:** Uso de bloques `try-except` para una ejecución robusta.

## Cómo Usar el Proyecto

1.  **Clonar el Repositorio:**
    ```bash
    
    ```
2.  **Instalar Dependencias:**
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  **Colocar Datos:** Asegúrate de que tu archivo `transacciones.csv` (con el formato esperado: `Fecha,Descripcion,Monto,Tipo_Transaccion,Categoria`) se encuentre en la raíz de la carpeta del proyecto.
4.  **Ejecutar el Script:**
    ```bash
    python analisis_contable.py
    ```
    Esto generará el `Informe_Flujo_Caja_Mensual.xlsx` y mostrará los gráficos de forma interactiva.

## Resultados del Proyecto

### Informe de Flujo de Caja Mensual (Ejemplo de Output en Consola)
