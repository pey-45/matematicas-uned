# Revisión de Álgebra Lineal I

## Fuentes y lectura · 10 de octubre de 2026

- Archivo recibido: `AL1-20261010T122956Z-1-001.zip`.
- Contiene 99 fotografías, `IMG_5712.HEIC`–`IMG_5810.HEIC`.
  Se han leído todas antes de ampliar los resúmenes, incluidas las
  páginas de ejercicios para delimitar el contenido.
- La primera imagen incluye una página del índice y la página 1;
  las siguientes contienen las parejas 2–3, 4–5, …, 196–197.
  La numeración es continua y el contenido académico es legible.
- Originales, conversiones para lectura e inventario con hashes están
  fuera del repositorio, en `Downloads/codex-AL1-20261010/`.
- El material recibido contiene los cuatro capítulos indicados abajo.
  Las menciones a capítulos posteriores del libro en el índice no se
  incorporan como teoría no proporcionada.

| Tema | Teoría | Páginas finales excluidas |
| --- | --- | --- |
| 1. Matrices | 1–71, secciones 1.1–1.5 | Ejercicios 72–74 |
| 2. Sistemas de ecuaciones lineales | 75–96, secciones 2.1–2.3 | Ejercicios 97–98 |
| 3. Espacios vectoriales | 99–152, secciones 3.1–3.9 | Ejercicios 153–155; p. 156 en blanco |
| 4. Aplicaciones lineales | 157–195, secciones 4.1–4.6 | Ejercicios 196–197 |

## Organización y decisiones de edición

- Se siguen las instrucciones de `AGENTS.md`: redacción propia, breve y
  rigurosa, que complementa el libro; no se transcriben sus resultados
  ni se conserva automáticamente su numeración y todas sus subdivisiones.
- Un capítulo por tema en `temas/tema-01.tex`–`tema-04.tex`.
  Se conserva `tema-01-gauss.tex`, incluido desde el primer tema,
  para reutilizar la sección existente sin duplicarla.
- Se mantienen la clase, tipografía, márgenes y macros del proyecto.
  Se añaden operadores para rango, adjunta, núcleo, imagen y grupo general
  lineal, y una notación explícita de coordenadas por columnas.
- Tema 1: operaciones, Gauss y Gauss–Jordan, equivalencias, rango,
  inversas ordinarias y laterales, congruencia y semejanza,
  determinantes, cofactores y menores.
- Tema 2: equivalencia de sistemas, compatibilidad, variables libres,
  Rouché–Frobenius, Cramer y factorización LU con permutaciones.
- Tema 3: axiomas, independencia, generación, bases, dimensión,
  coordenadas, rango de familias, cambios de base, subespacios y sus
  ecuaciones, intersecciones, sumas directas, suplementos y cocientes.
- Tema 4: linealidad y operaciones, imágenes y preimágenes de subespacios,
  núcleo, imagen, fórmula de dimensiones, tipos de aplicaciones,
  primer teorema de isomorfía, representación matricial y cambio de bases,
  endomorfismos, automorfismos, proyecciones, simetrías y dual.
- Se incluyen ideas breves de pruebas cuando explican una condición o un
  procedimiento. Se omiten demostraciones extensas, ejercicios y sus
  soluciones, historia, repeticiones y cálculos largos de los ejemplos.
- Los siete ejemplos breves son propios: precauciones con el producto,
  Gauss–Jordan, reutilización de LU, dirección de cambio de base,
  clases del cociente, proyección con dirección dada y cálculo de una base dual.
- Los documentos académicos no contienen información sobre fuentes,
  autoría, peticiones o proceso de elaboración; esa información se registra aquí.

## Precisiones y posibles errores del material

- **Definición 1.18, p. 20.** La columna de un pivote reducido tiene ceros
  salvo en el propio pivote, que vale 1. Se explicita la excepción omitida.
- **Adjunta, pp. 65–66.** Se respeta la convención del libro:
  `Adj(A)` es la matriz de cofactores sin trasponer; la inversa utiliza
  `Adj(A)^t / det(A)`. Se distingue el caso de orden 1 para no requerir
  un determinante de orden cero no definido en el texto.
- **Menores principales, p. 67.** `Delta_k` designa aquí el bloque de las
  primeras k filas y columnas. Se explica esta elección porque la
  condición de LU usa todos esos menores, no cualquier menor principal.
- **Proposición 2.14 y texto previo, p. 88.** La equivalencia de sistemas
  se define por igualdad de conjuntos de soluciones. La afirmación de que
  sistemas equivalentes tienen el mismo sistema reducido requiere restringirse
  a sistemas compatibles, con las mismas incógnitas y sin filas triviales.
  Por ejemplo, `x=0, 0=1` y `0=1, 0=0` tienen ambos solución vacía,
  pero matrices ampliadas reducidas distintas. El resumen explicita
  esta excepción y mantiene la unicidad de la reducción de cada matriz.
- **Proposición 3.66, p. 146.** Decir que dos conjuntos independientes son
  distintos no impide que compartan vectores: `{e1}` y `{e1,e2}` tienen
  unión base de R², pero sus espacios generados no son suplementarios.
  Se formula el criterio mediante la concatenación de las bases,
  conservando cualquier repetición como dependencia.
- **Observación, p. 151.** La afirmación de que cualquier subespacio tiene
  infinitos suplementos requiere excluir el subespacio nulo y el total.
  Se conserva la existencia y la posible falta de unicidad, sin esa
  afirmación universal.
- **Grupo general lineal, p. 185.** La no conmutatividad no se afirma para
  toda dimensión: en dimensión 1 el grupo de matrices invertibles es
  el grupo multiplicativo del cuerpo, conmutativo.
- **Formas e hiperplanos, p. 192.** El núcleo es un hiperplano únicamente
  para formas no nulas. La forma nula tiene núcleo igual a todo el espacio.
- Las operaciones elementales exigen índices distintos y escalares de
  multiplicación no nulos; la cancelación y las inversas bilaterales se
  aplican con las dimensiones necesarias. La fórmula binomial requiere
  conmutatividad. Se separan casos antes de dividir por parámetros.
- En la extracción de bases se distingue entre filas transformadas y
  columnas originales con pivote. En las fórmulas de cambio de base se
  indica siempre qué coordenadas transforma cada factor.
- Las dimensiones de soluciones homogéneas usan el rango de las ecuaciones,
  no su número total si hay redundancias. Los criterios de suma directa
  para varias familias usan la suma de los otros subespacios.
- En la revisión previa al commit se explicita que la selección de un
  menor para Cramer requiere rango positivo; en rango cero compatible,
  todas las incógnitas son libres. Para obtener una base de una suma se
  exige una familia independiente máxima entre los generadores.

## Antecedente

La primera versión de operaciones y Gauss se elaboró el 9 de octubre con
`drive-download-20261008T225704Z-1-001.zip`, fotografías
`IMG_5549.HEIC`–`IMG_5565.HEIC`, páginas 1–33. Se revisó de nuevo contra
el archivo completo actual. El desarrollo posterior sobre rango está
ahora disponible; ya no queda pendiente por falta de páginas.

## Verificación

- Inventario y lectura completos de las 99 fotografías: páginas 1–197,
  sin saltos ni partes de teoría ilegibles. Los cuatro tramos teóricos
  están cubiertos; no queda contenido esencial pendiente del material recibido.
- Revisión matemática de hipótesis, dimensiones, casos nulos, parámetros,
  inversas laterales, menores de LU, redundancia de ecuaciones, suma directa,
  cocientes y convenciones de coordenadas y cofactores.
- Los siete ejemplos se han comprobado con aritmética exacta. También se
  han comprobado la identidad de cofactores y el orden de composición
  de matrices de cambio de base.
- Etiquetas únicas y todas las referencias internas resueltas.
- Compilación de la vista previa con el compilador del editor: correcta.
  Compilación de `main.tex` y de la vista previa con pdfLaTeX en dos pasadas:
  sin advertencias de LaTeX, referencias indefinidas ni cajas desbordadas.
- PDF final de 24 páginas: portada, índice y 22 páginas de contenido.
  Todas las páginas se han renderizado y revisado visualmente; se ajustó
  el salto de página de la lista de condiciones de LU para mantenerla
  junto a su encabezado. Las páginas afectadas se comprobaron de nuevo.
- Vista previa autónoma regenerada desde las fuentes; el contenido de
  ambos PDF coincide. PDF, auxiliares y vista previa siguen excluidos de Git.
- Sin incidencias pendientes. Las precisiones detectadas se han aplicado
  al resumen y documentado arriba.
