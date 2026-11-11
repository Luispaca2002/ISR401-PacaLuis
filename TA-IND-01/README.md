# TA-TAR-01 - Trabajo Individual: IEEE 29148 y App Tuenti

**Autor:** Luis Alberto Paca Pilataza  
**Asignatura:** Ingeniería de Requerimientos (ISR-401)  
**Sistema Seleccionado:** App Móvil Tuenti Ecuador (iOS)  

## Descripción del Proyecto
Este directorio contiene la especificación académica de requisitos para la aplicación móvil Tuenti Ecuador, aplicando estrictamente las directrices de la norma **ISO/IEC/IEEE 29148:2018** y los umbrales de calidad de la norma **ISO/IEC 25010:2023**.

### Contenido del Documento (`main.pdf`)
1. **Resumen Analítico:** Características de un requisito bien formado y del conjunto de requisitos.
2. **Glosario:** 10 términos de la cláusula 3 de la norma aplicados a Tuenti.
3. **Matriz de Requisitos:** 15 requisitos propuestos (Funcionales, No Funcionales y Restricciones) con criterios de aceptación GWT.
4. **Autoevaluación y Reflexión:** Corrección de ambigüedades en los borradores iniciales.
5. **Anexos:** Evidencia fotográfica del sistema.

## Instrucciones de Compilación (LaTeX)
Para compilar el código fuente y generar el PDF final con las referencias cruzadas y la bibliografía, ejecute los siguientes comandos en la terminal estando dentro de este directorio:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

> **Nota:** Las imágenes requeridas para la compilación se encuentran en el directorio `/Figuras` y la bibliografía en `Referencias.bib`.
