# Revisión del tema 1 · Matrices

## Fuentes y alcance · 9 de octubre de 2026

- Archivo `drive-download-20261008T225704Z-1-001.zip`.
- Las 17 fotografías `IMG_5549.HEIC`–`IMG_5565.HEIC` contienen las
  páginas 1–33: introducción a las matrices, sección 1.1 «Operaciones con
  matrices» y sección 1.2 «Método de Gauss», hasta el Teorema 1.40.
- Se han revisado todas las páginas antes de redactar.
- Las fotografías son legibles y continuas. Originales, conversiones y
  archivos de comprobación permanecen fuera del repositorio.

## Selección y redacción

- Resumen de conceptos que complementa el libro, conforme a `AGENTS.md`.
- Se conservan las dos secciones del temario, reorganizando el contenido
  en bloques de estudio sin copiar la numeración de resultados y ejemplos.
- Operaciones: notación y tipos de matrices; suma y escalares; producto,
  tamaños y precauciones; bloques, potencias y clases de matrices;
  trasposición, parte simétrica y antisimétrica, y traza.
- Gauss: combinaciones e independencia de filas; operaciones elementales
  y su reversibilidad; equivalencia y matrices elementales; formas
  escalonadas; pasos de Gauss y Gauss–Jordan; unicidad de la forma reducida;
  precauciones con parámetros; columnas y equivalencia general.
- Las demostraciones extensas se omiten. Se mantienen ideas breves que
  explican las leyes entrada a entrada, la igualdad de trazas, la
  reversibilidad, la conservación de ceros y la unicidad.
- Se incluyen dos ejemplos breves: uno
  ilustra producto no conmutativo, producto nulo y fallo de cancelación;
  el otro muestra Gauss y Gauss–Jordan con una columna sin pivote.
- Se omiten ejercicios y soluciones, tablas repetitivas, cálculos
  intermedios largos, notas históricas y referencias a materia posterior.
- Proyecto directamente en `AL1/`, con la clase, tipografía, márgenes,
  paquetes y macros comunes. Los ejemplos no llevan numeración.
- El PDF contiene únicamente material académico. Fuentes, incidencias
  y decisiones de edición se registran aquí.

## Precisiones matemáticas del material

- **Definición 1.18, p. 20.** La condición impresa exige que las entradas de
  una columna con pivote sean cero sin excluir al propio pivote.
  Se utiliza la condición correcta: el pivote vale 1 y todas las demás
  entradas de su columna son cero.
- En las operaciones de suma de filas o columnas los índices son
  distintos; para multiplicar una fila o columna el escalar es no nulo.
- La suma exige igual orden; el producto exige dimensiones compatibles;
  la fórmula binomial exige matrices cuadradas del mismo orden que conmuten.
- La traza de una matriz requiere que sea cuadrada, pero la igualdad
  `tr(AB) = tr(BA)` admite factores rectangulares compatibles.
- Los algoritmos incluyen la matriz nula y la separación de casos antes
  de dividir por una expresión que pueda anularse.
- La justificación completa de maximalidad anunciada en la p. 17 no está
  en el tramo recibido y no se reconstruye. El resumen conserva el
  criterio de selección y su efecto, sin añadir esa demostración.

## Verificación final

- Compilación con pdfLaTeX (MiKTeX) en dos pasadas, sin referencias
  indefinidas, advertencias de LaTeX ni desbordamientos.
- PDF de 7 páginas: portada, índice y 5 páginas de contenido.
- Todas las páginas se han renderizado y revisado visualmente;
  tablas, fórmulas, encabezados y márgenes son legibles.
- Comprobación con aritmética exacta de ambos ejemplos, las operaciones
  de Gauss y la forma reducida, las identidades de trasposición y traza
  y el desarrollo binomial para matrices que conmutan.
- Vista previa autónoma regenerada desde las fuentes actuales.
  PDF, auxiliares y vista previa permanecen excluidos de Git.
- Sin incidencias pendientes.
