# Plantilla LaTeX de Tesis


Este proyecto LaTeX puede tomarse como plantilla de tesis en ingeniería de la Universidad Nacional de Ingeniería (https://www.uni.edu.pe/). 

Modificado desde https://github.com/KeyvinSV/Plantilla-Tesis-UNI-LaTeX. Además, existe una [versión online en Overleaf](https://www.overleaf.com/latex/templates/tesis-uni-template-universidad-nacional-de-ingenieria/xtqfzxhdfbrt?fbclid=IwAR39xRK0puQSjKE25RWw4VR983R0Y9N2riFbJLUnNXQ6mL1H2n1KWuEauSI)


## Dependencias

Se requiere de una distribución de LaTeX (se recomienda [TeXLive](https://www.tug.org/texlive/)), el software de gestión de referencias BibTeX y una aplicación para edición (se recomienda [TeXstudio](https://www.texstudio.org/)). 

Además, hay gráficos opcionales que se generan con Tikz.


## Estructura

La estructura de ficheros y directorios es la siguiente:

```
PlantillaTesis/
├── 0_0_PREAMBULO
│   └── Preambulo.tex
├── 1_1_PROTOCOLAR
│   ├── Agradecimientos.tex
│   ├── Caratula.tex
│   ├── Dedicatoria.tex
│   └── Licencia.tex
├── 1_2_RESUMEN
│   ├── Abstract.tex
│   └── Resumen.tex
├── 1_3_PROLOGO
│   └── Prologo.tex
├── 1_4_SIMBOLOS
│   ├── Secciones
│   └── Simbolos.tex
├── 2_CAPITULO1
│   ├── Capitulo1.tex
│   └── Secciones
│       ├── 1_Generalidades.tex
│       ├── 2_Descripción del problema.tex
│       ├── 3_Objetivos.tex
│       ├── 4_Hipótesis.tex
│       └── 5_Metodología.tex
├── 2_CAPITULO2
│   ├── Capitulo2.tex
│   └── Secciones
├── 2_CAPITULO3
│   ├── Capitulo3.tex
│   └── Secciones
├── 2_CAPITULO4
│   ├── Capitulo4.tex
│   └── Secciones
├── 3_1_CONCLUSIONES
│   ├── Conclusiones.tex
│   └── Recomendaciones.tex
├── 3_2_BIBLIOGRAFIA
│   ├── Bibliografia.tex
│   └── library.bib
├── 3_3_ANEXOS
│   ├── Anexos.tex
│   └── Secciones    
├── E_IMAGENES
│   ├── 1_Caratula
│   │   └── UNI_LOGO1.pdf
│   ├── 2_Capitulo2
│   ├── 2_Capitulo3
│   ├── 2_Capitulo4
│   └── 3_Anexos
├── T_TABLAS
│   └── 2_Capitulo3
├── .gitignore
├── LICENSE
├── README.md
├── TesisUNI.cls
├── TESIS_UNI_main.pdf
└── TESIS_UNI_main.tex
```


## Uso

La compilación se realiza con el fichero control `TESIS_UNI_main.tex`, previamente debe configurar en su aplicación de edición la compilación con el motor XeLaTeX (el motor PdfLaTeX da error).

La clase de documento LaTeX (documentclass) es una modificación de la clase book, esto corresponde al archivo `TesisUNI.cls` (evite editar dicho archivo).

El esquema de carátula de la tesis queda definida en el fichero `1_0_CARATULA/Caratula.tex` (evite editar dicho archivo), y puede modificarse los datos de la carátula desde el preámbulo en el fichero `0_0_PREAMBULO/Preambulo.tex`.

El resultado de la compilación es un archivo PDF llamado `TESIS_UNI_main.pdf`.


## Recomendaciones

- Usar Detexify/Mathpix para facilitar el manejo de formulas matemáticas.
- Usar aplicaciones online para facilitar el manejo de tablas.
- Usar Mendeley/JabRef para gestionar las referencias bibliograficas.
- Usar Illustrator/Autocad para generar imágenes vectoriales.
- Usar Python/R/Matlab para obtener gráficos vectoriales.


## Contacto

vcamarenap@uni.pe
