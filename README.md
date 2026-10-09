# Resúmenes del grado en Matemáticas · UNED

Resúmenes en LaTeX que reúnen en un espacio reducido los conceptos
relevantes de cada asignatura, con explicaciones breves, condiciones de los
resultados y pasos esenciales de los procedimientos.

Complementan el libro: las explicaciones detalladas, demostraciones extensas
y ejercicios se consultan en él. El contenido se selecciona y se redacta
con palabras propias, sin reproducir el texto ni reformularlo frase por frase.
Los ejemplos incluidos son breves y sirven para aclarar conceptos concretos.

Las instrucciones para las sesiones están en [AGENTS.md](AGENTS.md).

## Asignaturas

- **LMCN**: Lenguaje matemático, conjuntos y números. Tema 1: Nociones de lógica;
  tema 2: Conjuntos, páginas 33–69 del libro.
- **AL1**: Álgebra Lineal I. Tema 1: Matrices, secciones 1.1 y 1.2
  (Operaciones con matrices y Método de Gauss), páginas 1–33 del libro.

## Organización

```text
AGENTS.md
README.md
LMCN/
  main.tex
  preambulo.tex
  temas/
    tema-01.tex
    tema-02.tex
  REVISION.md
AL1/
  main.tex
  preambulo.tex
  temas/
    tema-01.tex
    tema-01-gauss.tex
  REVISION.md
```

Cada asignatura constituye un proyecto LaTeX independiente, situado
directamente en su carpeta. No se incluyen documentos de ejercicios.

## Compilación

Desde la carpeta de la asignatura (`AL1/` o `LMCN/`), ejecutar dos pasadas:

```text
pdflatex main.tex
pdflatex main.tex
```

También puede usarse `latexmk -pdf main.tex`.
En Overleaf, importar únicamente las fuentes LaTeX de la asignatura y
seleccionar `main.tex` como principal.
Se utilizan paquetes habituales de TeX Live y MiKTeX.

`main.pdf`, los auxiliares de compilación y las copias autónomas
`vista-previa.tex` / `vista-previa.pdf` están excluidos de Git. Las fuentes de
edición son `temas/`, `main.tex` y el preámbulo de cada asignatura.
Las copias de vista previa se generan para el editor de Codex, cuyo compilador
solo admite un archivo. Cada asignatura documenta fuentes, incidencias y
verificaciones en `REVISION.md`, fuera de los documentos de estudio.
