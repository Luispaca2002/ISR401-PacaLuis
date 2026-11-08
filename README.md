# Repositorio ISR401-PacaLuis

**Estudiante:** Luis Alberto Paca Pilataza  
**Asignatura:** Ingeniería de Requerimientos (ISR-401)  
**Nivel y Paralelo:** 4.º Nivel de Software  
**Docente:** Gleiston Cicerón Guerrero Ulloa, PhD  
**Institución:** Universidad Técnica Estatal de Quevedo (UTEQ)  

---

## Actividad Formativa: FORM-TL-01 (Taller de tipos de requisitos)

Este repositorio contiene la solución completa de la actividad formativa **FORM-TL-01**, aplicada al caso práctico del *Policlínico Ribera del Quevedo*.

### Contenido del proyecto
* `main.tex`: Documento fuente en \LaTeX\ que incluye:
  1. Tabla de clasificación de los 20 enunciados (E01 a E20) evaluados en tres dimensiones con justificación directa.
  2. Cuantificación de los 5 requisitos de calidad ambiguos (RNF-01 a RNF-05) con métricas, umbrales y métodos de verificación basados en el caso.
  3. Discusión y resolución técnica de discrepancias con un compañero (enunciados E02 y E10).
  4. Declaración de uso ético de Inteligencia Artificial (Norma 8).
  5. Referencias bibliográficas en formato IEEE.
* `main.pdf`: Documento final compilado.
* `referencias.bib`: Archivo de bibliografía en formato BibTeX.
* `README.md`: Guía de reproducibilidad y parámetros de compilación.

---

## Instrucciones de Compilación (Condición de Entrega P2)

El documento ha sido preparado para garantizar su reproducibilidad exacta al clonar el repositorio:

* **Compilador requerido:** `pdfLaTeX` (distribución TeX Live o MiKTeX).
* **Archivo principal:** `main.tex`.
* **Paquetes y dependencias de \LaTeX:**
  * `article` (clase base)
  * `inputenc` (codificación UTF-8)
  * `babel` (soporte de idioma español)
  * `geometry` (márgenes de página)
  * `xltabular` y `booktabs` (tablas multipágina con autoajuste de columnas)
  * `hyperref` y `url` (enlaces interactivos y referencias)
  * `microtype` (optimización tipográfica)

### Orden de comandos para compilación
Abra una terminal en la carpeta del proyecto y ejecute:

```bash
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
```
*(Se ejecuta dos veces para resolver adecuadamente la paginación de las tablas y las referencias cruzadas).*
