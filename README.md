# Plantilla de Memoria en LaTeX (A4) - HU Virgen del Rocío

Esta es una plantilla profesional en LaTeX adaptada para la redacción de memorias técnicas, especialmente configurada para el ámbito del proyecto de adecuación de cafeterías y vending del **Hospital Universitario Virgen del Rocío** y el **Hospital de San Lázaro**.

La plantilla está optimizada para su uso directo en **Overleaf**.

## Estructura del Proyecto

```text
├── main.tex                    # Fichero principal (configuraciones, márgenes, paquetes)
├── portada.tex                 # Portada estilizada e institucional del proyecto
├── referencias.bib             # Base de datos bibliográfica (BibTeX)
├── .gitignore                  # Exclusión de archivos de compilación de LaTeX
└── secciones/                  # Capítulos/secciones de la memoria
    ├── 01_introduccion.tex     # Introducción, objeto y antecedentes
    ├── 02_descripcion.tex      # Descripción de servicios y calidad (APPCC)
    └── 03_adecuacion.tex       # Reformas físicas y tablas de equipamiento
```

## Características Técnicas de la Plantilla
- **Papel:** A4 con márgenes optimizados de $2.5\text{cm}$ laterales y $3\text{cm}$ superior/inferior.
- **Tipografía:** Latin Modern (lmodern) con tamaño de fuente base de $12\text{pt}$ para una excelente legibilidad en impresión.
- **Idioma:** Configurada en español con soporte para nombres de tablas correctos e índices generados automáticamente.
- **Diseño visual:** Cabeceras y pies de página elegantes mediante `fancyhdr` con los colores corporativos azulados del proyecto. Enlaces dinámicos limpios y sin recuadros de colores molestos.

## ¿Cómo importarlo en Overleaf?

Puedes importar esta plantilla a Overleaf de dos formas sencillas:

### Opción 1: Importar desde GitHub (Recomendado)
1. En tu panel de control de Overleaf, haz clic en **New Project** (Nuevo proyecto).
2. Selecciona **Import from GitHub** (Importar desde GitHub).
3. Conecta tu cuenta de GitHub (si no lo has hecho ya) y selecciona este repositorio.
4. Overleaf creará el proyecto vinculándolo automáticamente a tu rama principal.

### Opción 2: Subir como archivo ZIP
1. Descarga este repositorio desde GitHub como archivo ZIP (`Code` -> `Download ZIP`).
2. En Overleaf, haz clic en **New Project** -> **Upload Project** (Subir proyecto).
3. Sube el archivo ZIP descargado y Overleaf lo extraerá por ti.

---
*Plantilla generada con cariño y adaptada a tus necesidades técnicas de proyecto.*
