# Revisión de LMCN

# Tema 1 · Nociones de lógica

## Fuentes y alcance · 9 de octubre de 2026

- Archivo `drive-download-20261008T225704Z-1-001.zip`.
- `IMG_5516.HEIC`: índice del libro.
- `IMG_5517.HEIC`–`IMG_5544.HEIC`: teoría del capítulo 1, páginas 3–30.
- `IMG_5545.HEIC`–`IMG_5546.HEIC`: ejercicios propuestos, páginas 31–32;
  leídos para comprobar el alcance y excluidos del resumen.
- Se han revisado las 31 fotografías antes de redactar. El resumen
  se limita al capítulo 1.
- Originales, conversiones y archivos de comprobación permanecen fuera
  del repositorio. No hay páginas ilegibles ni cortes pendientes.

## Selección y redacción

- Resumen de conceptos que complementa el libro, conforme a `AGENTS.md`.
- El contenido se reorganiza en cinco bloques: proposiciones y conectivas;
  equivalencias y simplificación; inferencias y comprobación de argumentos;
  forma normal conjuntiva; axiomas y demostraciones.
- Se mantienen los conceptos básicos, las condiciones de validez,
  las leyes centrales, el procedimiento de FNC, los cuatro esquemas de
  axiomas de PM y sus reglas, la terminología de resultados, las condiciones
  necesarias y suficientes y los métodos de demostración.
- Una tabla reúne las cinco conectivas básicas. La cantidad de conectivas
  se explica contando funciones de verdad, sin reproducir las dieciséis
  tablas binarias ni sus códigos.
- Una tabla resume las inferencias principales. La validación se explica
  mediante tablas de verdad, transformaciones y refutación, sin trasladar
  los argumentos extensos del libro.
- Se omiten demostraciones completas, variantes secundarias de identidades,
  ejemplos del libro, ejercicios, soluciones, comentarios históricos y
  anuncios de materia posterior.
- Se incluyen dos ilustraciones breves: un predicado aritmético y una
  conversión a FNC.
- Proyecto directamente en `LMCN/`, con la clase, tipografía, márgenes,
  paquetes y macros comunes. Los ejemplos no llevan numeración.
- El PDF contiene únicamente material académico. Fuentes, incidencias
  y decisiones de edición se registran aquí.

## Precisiones matemáticas del material

- **Equivalencia, pp. 10 y 14.** Coincidir bajo una sola asignación no
  equivale a ser fórmulas equivalentes. En el resumen la equivalencia
  exige coincidencia en todas las asignaciones; la implicación lógica
  expresa que el condicional correspondiente es una tautología.
- **Sustitución en PM, p. 28.** El reemplazo de una variable por una
  fórmula es uniforme, en todas sus apariciones.
- **Métodos de demostración, p. 30.** La remisión impresa a «ejercicio 1.9»
  corresponde al «ejemplo 1.9», sobre irracionalidad. La remisión y
  ese desarrollo no se incluyen en el resumen.

## Verificación final

- Compilación con pdfLaTeX (MiKTeX) en dos pasadas, sin referencias
  indefinidas, advertencias de LaTeX ni desbordamientos.
- PDF de 6 páginas: portada, índice y 4 páginas de contenido.
- Todas las páginas se han renderizado y revisado visualmente;
  tablas, fórmulas, encabezados y márgenes son legibles.
- Comprobación exhaustiva de los valores de la tabla de verdad,
  equivalencias, reglas de inferencia, axiomas de PM y ejemplo de FNC.
  Comprobada también la equivalencia entre recíproca y contraria.
- Vista previa autónoma regenerada desde las fuentes actuales.
  PDF, auxiliares y vista previa permanecen excluidos de Git.
- Sin incidencias pendientes.

# Tema 2 · Conjuntos

## Fuentes y alcance · 9 de octubre de 2026

- Archivo `cap2-20261009T211657Z-1-001.zip`, carpeta `cap2/`.
- `IMG_5595.HEIC`: apertura del capítulo 2 (p. 33, sin número impreso).
  En el margen izquierdo aparece parte de la página anterior, ya cubierta
  por el material del tema 1 y sin contenido nuevo para este resumen.
- `IMG_5596.HEIC`–`IMG_5613.HEIC`: páginas 34–69, fotografiadas por parejas,
  en orden continuo. Incluyen las secciones 2.1–2.5 y los comentarios finales.
- Las 19 fotografías se han leído completas antes de redactar.
  El tramo recibido es legible y no presenta saltos de paginación.
  No falta material necesario para resumir este tramo.
- Los originales, las conversiones y los archivos de comprobación
  permanecen fuera del repositorio, en `Downloads/codex-cap2-20261009/`.

## Selección y redacción

- Tema separado en `temas/tema-02.tex`, incorporado a `main.tex`.
  Se reutilizan el preámbulo, las macros y la presentación existentes.
- Organización en siete bloques: conjuntos e inclusión; naturales,
  inducción y recurrencia; cuantificadores; operaciones y álgebra;
  producto cartesiano; relaciones; límites de la descripción intuitiva.
- Se conservan extensión y comprensión, universo y propiedad
  característica, igualdad, vacío, unitarios y conjunto potencia;
  los cinco axiomas informales de Peano, inducción ordinaria desde cero
  o desde otro natural, inducción completa y valores iniciales de recurrencias.
- Se incluyen significado y negación de cuantificadores, contraejemplos,
  dependencia de variables y negación con varios cuantificadores;
  complementario, unión, intersección, conjuntos disjuntos, diferencias, leyes
  fundamentales y familias con índice no vacío.
- Se incluyen pares y n-uplas, condiciones y distributividad del producto;
  predicado y grafo de una relación, inversa, conjuntos inicial/final,
  original/imagen de la relación y de cada elemento, y composición.
- Se mantiene la idea de la paradoja de Russell y el papel de la
  axiomatización y de la comprensión restringida. La exposición formal
  de ZF, presentada como comentario ilustrativo en pp. 67–68, no se
  reproduce ni se reconstruye: se retienen extensionalidad y especificación,
  directamente ligadas a las construcciones usadas en el tema.
- Se omiten ejercicios y soluciones, ejemplos extensos del libro,
  demostraciones desarrolladas, historia y la analogía del barbero.
  Los resultados básicos que el texto formula dentro de ejercicios
  (número de subconjuntos y caracterización de inclusión por operaciones)
  se enuncian sin trasladar los ejercicios ni sus soluciones.
- Se usan dos ejemplos propios: dependencia del testigo existencial
  respecto de una variable universal, y originales e imágenes en una
  relación finita. El factorial y las progresiones se conservan como
  definiciones recurrentes básicas, sin los desarrollos del libro.
- Los documentos de estudio contienen únicamente contenido académico;
  fuentes, decisiones e incidencias se registran aquí.

## Precisiones matemáticas del material

- **Inclusión, p. 35.** El libro usa `\subset` admitiendo igualdad.
  El resumen usa `\subseteq` para esa inclusión y `\subsetneq` para
  inclusión estricta, distinguiendo ambas de pertenencia.
- **Ejemplo 2.2, p. 35.** La afirmación de que las potencias de 2 están
  incluidas en los naturales pares necesita excluir `2^0=1`.
  Ese ejemplo no se reproduce.
- **Familias, p. 51.** Se mantiene la hipótesis de conjunto de índices
  no vacío; no se añaden convenciones para familias vacías.
- **Producto, p. 57.** La no conmutatividad se formula «en general»:
  factores distintos pueden dar productos iguales si uno es vacío.
  No se afirma que todo par de factores distintos dé productos distintos.
- **Relaciones, pp. 60–61.** Los conjuntos inicial y final pueden ser
  mayores que los conjuntos original e imagen. La imagen de un elemento
  es un conjunto, sin exigir existencia o unicidad de pareja.
- **Cuantificadores, pp. 64–65.** Cambiar cuantificadores distintos
  puede alterar el valor de verdad; no se afirma que lo altere siempre.
  Se mantienen sus universos y se niegan sin cambiar el orden.
- **ZF, p. 68.** La presentación del «axioma de sustitución» no exige
  que la fórmula determine un único valor y deja ambiguo el conjunto
  `B` dependiente de `x`; no constituye una formulación precisa del
  esquema. No se transcribe ni se completa con materia externa.

## Verificación final

- Compilación final con pdfLaTeX (MiKTeX) en dos pasadas, sin referencias
  indefinidas, advertencias de LaTeX ni desbordamientos.
  MiKTeX emite únicamente un aviso administrativo sobre comprobar
  actualizaciones; no afecta a la compilación.
- PDF conjunto de 12 páginas: portada, índice, 4 páginas del tema 1
  y 6 del tema 2. Se revisaron todas las páginas renderizadas,
  incluidas las versiones finales tras ajustar los saltos.
- Se mantienen juntas las listas iniciales y las parejas de definiciones
  de originales e imágenes; la tabla de leyes conserva su introducción.
  Márgenes, fórmulas, tablas, encabezados e índice son legibles.
- Comprobación matemática de hipótesis y definiciones frente al tramo
  recibido. Verificados los dos ejemplos, la interpretación de los
  cuantificadores, los pasos de inducción y los datos iniciales de recurrencias.
- Comprobación exhaustiva en un universo de tres elementos de las leyes
  de operaciones, diferencias, caracterizaciones de inclusión y
  distributividad del producto (512 ternas de subconjuntos); comprobación
  de 64 tablas de verdad para la negación con dos cuantificadores.
  Estas comprobaciones apoyan la revisión y no sustituyen la justificación
  general por pertenencia.
- Verificadas la unicidad de las 11 etiquetas y las 6 referencias internas
  del documento conjunto. README y portada actualizados al alcance actual.
- Vista previa autónoma regenerada desde las fuentes finales.
  El compilador interno de Codex no pudo preparar su entorno
  (`windows sandbox: helper_unknown_error`). La fuente se conserva y
  se ha compilado también con MiKTeX en dos pasadas como alternativa
  local, generando `vista-previa.pdf` sin errores de LaTeX.
  PDF, auxiliares y vista previa permanecen excluidos de Git.
- Sin incidencias académicas ni material ilegible pendiente.
