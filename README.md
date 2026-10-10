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

- **LMCN**: Lenguaje matemático, conjuntos y números. Los siete temas completos:
  lógica; conjuntos; relaciones y aplicaciones; operaciones y estructuras
  algebraicas; naturales y enteros; racionales y reales; complejos.
  Los tramos del libro y las decisiones de edición constan en `LMCN/REVISION.md`.
- **AL1**: Álgebra Lineal I. Los cuatro temas del material recibido:
  matrices; sistemas de ecuaciones lineales; espacios vectoriales;
  aplicaciones lineales, hasta el espacio dual. Páginas 1–197 del libro,
  con ejercicios excluidos del resumen. Fuentes y precisiones en `AL1/REVISION.md`.

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
    tema-03.tex
    tema-04.tex
    tema-05.tex
    tema-06.tex
    tema-07.tex
  REVISION.md
AL1/
  main.tex
  preambulo.tex
  temas/
    tema-01.tex
    tema-01-gauss.tex
    tema-02.tex
    tema-03.tex
    tema-04.tex
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
