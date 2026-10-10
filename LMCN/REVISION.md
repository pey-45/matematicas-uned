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

# Tema 3 · Relaciones y aplicaciones entre conjuntos

## Fuentes y alcance · 9 de octubre de 2026

- Archivo `cap3-20261009T212743Z-1-001.zip`, carpeta `cap3/`.
- `IMG_5614.HEIC`: apertura del capítulo 3, p. 75; la página izquierda
  está en blanco. `IMG_5615.HEIC`–`IMG_5633.HEIC`: pp. 76–113,
  fotografiadas por parejas en orden continuo.
- `IMG_5634.HEIC`: p. 114 completa, con el final de los comentarios,
  y un fragmento de la p. 115, que comienza «Ejercicios propuestos».
- Se han leído las 21 fotografías completas antes de redactar.
  Las pp. 75–114 contienen toda la teoría del capítulo, son legibles
  y no presentan saltos. No falta material teórico necesario.
  La p. 115 de ejercicios no está completa; se excluye sin reconstruirla.
- Los originales, conversiones y comprobaciones permanecen fuera
  del repositorio, en `Downloads/codex-cap3-20261009/`.

## Selección y redacción

- Tema separado en `temas/tema-03.tex`, incorporado a `main.tex`.
  Se reutilizan la presentación y el preámbulo, añadiendo las macros
  de enteros y racionales. Se actualizan portada, metadatos y README.
- Organización en ocho bloques: propiedades de relaciones; equivalencias
  y cocientes; orden y cotas; aplicaciones; composición e inversas;
  factorización canónica; equipotencia y cardinalidad finita;
  elección y comparación de cardinales.
- Se conservan las cuatro propiedades de relaciones y sus expresiones
  mediante grafos; clases, representantes y correspondencia con particiones;
  construcción por cocientes de enteros y racionales, congruencias y ángulos.
- Se incluyen órdenes total y parcial, estricto asociado, lexicográfico
  y por componentes; intervalos y segmentos, cotas, extremos, supremo
  e ínfimo, buena ordenación, propiedad del supremo y maximales/minimales.
- Se incluyen definición y grafo de aplicación, dominio, conjunto final,
  imagen y fibras; igualdad, casos vacíos, restricciones, identidad,
  constantes, sucesiones y función característica; inyectividad,
  sobreyectividad y biyectividad con sus procedimientos de comprobación.
- Se mantienen composición, asociatividad, identidades e iteración,
  estabilidad de los tipos bajo composición, caracterización y unicidad
  de la inversa, inversas por un lado y factorización mediante cociente,
  biyección sobre la imagen e inclusión.
- Se incluyen equipotencia, identificación mediante correspondencias,
  cardinales finitos, numerabilidad en la convención del libro, continuo,
  recuentos de aplicaciones/inyecciones/biyecciones y restricciones de tamaño.
- De los comentarios se conservan elección y producto de familias,
  buena ordenación, lema de Zorn, orden de cardinales,
  Cantor–Bernstein–Schröder, comparabilidad e hipótesis del continuo.
  Son enunciados breves, sin reconstruir demostraciones no proporcionadas.
- Se omiten ejercicios y soluciones, demostraciones largas, ejemplos
  gráficos desarrollados, factorización detallada del seno e historia.
  Se usa un ejemplo propio de extremos en divisibilidad, con `{3,5}`,
  y otro breve de incomparabilidad en el orden por componentes.
- El documento de estudio contiene únicamente contenido académico.
  La vista previa abierta se actualiza en su archivo existente.

## Precisiones matemáticas del material

- **Congruencias, p. 80.** Se explicita `p ∈ N*` para obtener los
  representantes `0,…,p−1` y exactamente `p` clases.
- **Orden, pp. 82–83.** Se conserva «parcial» para el caso no total,
  según el uso del capítulo; se explicita la falta de comparabilidad.
- **Cotas y extremos, pp. 86–89.** Cotas, supremo e ínfimo se buscan
  en el conjunto ambiente; máximo y mínimo deben pertenecer al subconjunto.
  La propiedad del supremo se formula para subconjuntos no vacíos.
- **Aplicaciones, pp. 94–95.** `f(x)` es un valor, no un conjunto unitario.
  La notación `f^{-1}(y)` para los originales denota una fibra hasta que
  se haya establecido la existencia de una aplicación inversa.
- **Inversas por un lado, pp. 105–106.** La caracterización de inyectividad
  mediante una inversa por la izquierda necesita dominio no vacío,
  salvo el caso en que ambos conjuntos sean vacíos. La demostración del
  libro elige `x₀ ∈ A` sin enunciar esa condición. Se incluye la hipótesis
  y se explica el caso `A=∅≠B`, que es un contraejemplo al enunciado irrestricto.
  Para la inversa por la derecha de una sobreyección arbitraria se señala
  el uso del axioma de elección, explicado en los comentarios del capítulo.
- **Cardinales, p. 109.** Se expresa la igualdad de cardinales por
  equipotencia, sin presentar como conjunto la colección de todos los
  conjuntos equipotentes a uno dado. Se mantiene «numerable» como
  equipotente a `N`, sin incluir los conjuntos finitos en ese término.
  Los recuentos separan el conjunto final vacío, evitando la ambigüedad
  de `0^0`, y contemplan la única biyección del vacío consigo mismo.
- **Elección y producto, pp. 111–112.** Se presenta la selección en una
  familia mediante sus índices; un elemento del producto es una selección
  para cada índice. La cota de una cadena del lema de Zorn está en el
  conjunto ordenado ambiente, y la conclusión es maximal, no máximo.
- **Hipótesis del continuo, p. 114.** La independencia se enuncia bajo
  la condición de consistencia de ZFC, sin añadir su demostración.

## Verificación del tema 3

- Revisadas las definiciones, sus hipótesis y los casos vacíos. Comprobación
  exhaustiva de las 512 relaciones de un conjunto de tres elementos:
  cinco equivalencias y diecinueve órdenes; contrastadas sus clases,
  propiedades y extremos de los subconjuntos.
- Comprobadas las 60 aplicaciones entre conjuntos de tamaños de cero a tres:
  recuentos, inyectividad, sobreyectividad, inversas por un lado y
  factorización mediante fibras. Verificados los ejemplos propios de orden.
- Siete páginas de contenido, referencias resueltas y revisión visual
  de todas sus páginas en la compilación conjunta definitiva.

# Temas 4–7 · Teoría completa recibida el 9 de octubre de 2026

## Inventario y comprobación de integridad

- Fuente: `LMCN-20261009T213805Z-1-001.zip`, entregado por el usuario.
  Contiene 140 fotografías en las carpetas `LMCN/cap1` a `LMCN/cap7`.
- Las 71 fotografías de los capítulos 1–3 coinciden por SHA-256 con las
  fuentes anteriores, ya leídas íntegramente antes de redactar. Se ha
  contrastado su contenido con los tres resúmenes existentes.
- Se han leído las 69 fotografías nuevas de los capítulos 4–7 antes de
  redactar sus resúmenes, incluidos comentarios y fragmentos de ejercicios
  para delimitar el final de la teoría. Las fotografías son legibles.
- Capítulo 4: `IMG_5635.HEIC`–`IMG_5651.HEIC`, teoría y comentarios,
  páginas 121–153, sin huecos.
- Capítulo 5: `IMG_5652.HEIC`–`IMG_5677.HEIC`, páginas 159–205.
  Teoría y comentarios hasta la página 202; ejercicios finales 203–205
  excluidos. No existen los nombres `IMG_5661` y `IMG_5662`, pero las
  fotografías anterior y posterior muestran 174–175 y 176–177:
  el salto de nombres no supone una pérdida de páginas.
- Capítulo 6: `IMG_5678.HEIC`–`IMG_5692.HEIC`, páginas 207–235,
  incluida toda la construcción por cortaduras de Dedekind.
- Capítulo 7: `IMG_5693.HEIC`–`IMG_5705.HEIC`, páginas 241–264 de teoría
  y comentarios, terminando con el teorema fundamental del álgebra.
  La última imagen muestra además una parte de los ejercicios de la
  página 265, que no se utiliza ni se reconstruye.
- Los siete tramos teóricos son completos: 3–30, 33–69, 75–114,
  121–153, 159–202, 207–235 y 241–264. Los intervalos entre capítulos
  corresponden al material de ejercicios y separación del libro.
- Originales, conversiones, inventario con hashes y comprobaciones
  permanecen fuera del repositorio, en el directorio de trabajo de Descargas.
  Los documentos adjuntos se usan como fuente académica, no como
  instrucciones para ejecutar acciones.

## Selección del tema 4 · Operaciones y estructuras algebraicas

- Operación interna, asociatividad, conmutatividad, neutro y simétricos;
  grupos, cancelación, ecuaciones, inverso de un producto y criterio de
  subgrupo; clases por un subgrupo abeliano y divisibilidad de cardinales
  en el caso finito tratado por el material.
- Anillos y sus convenciones, distributividad, reglas de signos, binomio
  de Newton, divisores de cero, subanillos e ideales; cuerpos y subcuerpos.
- Compatibilidad de operaciones y orden, cono no negativo, valor absoluto
  y reglas para invertir desigualdades; homomorfismos, isomorfismos,
  núcleo, imagen y subgrupo generado; suma y producto de cardinales.
- Se reúnen definiciones y criterios sin repetir largas verificaciones
  de axiomas. Los ejemplos de estructuras se limitan a distinguir las
  propiedades; las clases módulo 3 y 4 ilustran cuerpo frente a divisor
  de cero, sin añadir teoría general de cuerpos finitos.

### Precisiones del tema 4

- **Matrices y permutaciones.** La no conmutatividad requiere condiciones
  sobre el tamaño. Para matrices cuadradas se explicita `n ≥ 2`; no se
  generaliza la afirmación a todos los tamaños.
- **Anillos, pp. 132–139.** Se conserva la convención del libro: anillo
  no presupone unidad ni conmutatividad; unidad distinta de cero; cuerpo
  con producto conmutativo. «Íntegro» se usa para ausencia de divisores
  de cero, sin añadir unidad o conmutatividad implícitas.
- **Newton, p. 134.** La fórmula compacta con exponentes cero se presenta
  en un anillo conmutativo unitario. Para el no unitario se separan los
  extremos y se indican únicamente potencias positivas.
- **Ideal principal, p. 138.** La denominación «generado por a» para `aA`
  necesita unidad para asegurar `a ∈ aA`. Se explicita esa hipótesis;
  en un anillo sin unidad `aA` puede no contener a `a`.
- **Orden, pp. 141–145.** El cono incluye al cero. Las propiedades de
  cuadrados, valor absoluto e inversos se enuncian con orden total y
  con las condiciones de signo que correspondan.
- **Homomorfismos, pp. 149–150.** Se conserva la definición que exige
  preservar suma y producto sin imponer adicionalmente la unidad. No se
  afirma que cualquier homomorfismo entre cuerpos sea inyectivo.
- **Isomorfismo de orden, p. 150.** Una biyección monótona entre órdenes
  parciales no basta para que su inversa sea monótona. Se exige conservación
  en ambos sentidos; la condición de biyección monótona basta para órdenes
  totales. El enunciado general del libro omite esta distinción.

## Selección del tema 5 · Naturales y enteros

- Recurrencias de suma y producto, potencias, cancelación y orden de los
  naturales; finitud y recuentos, variaciones, permutaciones y combinaciones.
  Se remite a los axiomas de Peano y a los recuentos ya explicados.
- Infinitud, diagonal de Cantor, conjuntos de partes, numerabilidad de
  subconjuntos, productos finitos, uniones numerables, enteros, racionales
  y partes finitas de los naturales.
- Construcción de los enteros con sus operaciones y orden; división con
  resto, clasificación de subgrupos e ideales de los enteros; divisibilidad,
  máximo común divisor, mínimo común múltiplo, Bézout, Euclides y Gauss.
- Se añade únicamente la idea de los argumentos que explica una propiedad
  o un procedimiento. No se trasladan problemas de recuento ni soluciones
  de ecuaciones diofánticas. Ejemplo propio de división con dividendo negativo.

### Precisiones del tema 5

- **Potencias y recuentos.** Se distinguen las potencias aritméticas de
  base cero y los casos de aplicaciones con conjunto final vacío.
  Se usa `0! = 1`, sin asignar indiscriminadamente un valor a `0^0`.
- **Numerabilidad, pp. 181–186.** «Numerable» significa equipotente a los
  naturales, excluidos los finitos. La estabilidad por producto se limita
  a uno o más factores en número finito, como permite el argumento del
  libro. Se señala la elección simultánea de enumeraciones en familias
  numerables bajo el axioma de elección.
- **División, p. 192.** Se mantiene `0 ≤ r < |b|`, también para números
  negativos; no se confunde con truncar un cociente hacia cero.
- **Gauss, teorema 5.52, p. 199.** La hipótesis impresa «a divide a ab»
  es una errata. Debe ser «a divide a bc», como muestra la demostración
  inmediatamente posterior mediante `bc = ak`. Se conserva el resultado
  correcto y su breve justificación por Bézout.

## Selección del tema 6 · Racionales y reales

- Clases de fracciones, reducción, operaciones, cuerpo y orden racional;
  decimales finitos, criterio del denominador y división decimal periódica.
- Insuficiencia de los racionales, axioma del supremo, ínfimo, raíz
  cuadrada, definición de e, parte entera y aproximaciones, propiedad
  arquimediana, densidad de racionales e irracionales.
- Intervalos, intervalos encajados, significado de desarrollos decimales,
  fracción generatriz y no numerabilidad de los reales.
- Unicidad del cuerpo ordenado completo salvo isomorfismo; idea del modelo
  por sucesiones de Cauchy y construcción por cortaduras derechas: condiciones,
  inclusión racional, orden, suma, opuesto, producto e inverso positivo.
  Breve relación entre racionalidad y conmensurabilidad.
- Se omiten historia, ejercicios y sus soluciones, pruebas largas del
  axioma del supremo en los modelos y desarrollos geométricos secundarios.
  Ejemplos propios de parte entera negativa y fracción generatriz.

### Precisiones del tema 6

- **Fracciones, pp. 208–209.** La representación irreducible única se
  normaliza con denominador positivo; se trata el cero como `0/1`.
- **Decimales, pp. 211–212.** El criterio de factores 2 y 5 se aplica al
  denominador positivo de una fracción irreducible, no a uno cualquiera.
- **Completitud y aproximaciones, pp. 213–227.** Se conserva la condición
  de conjunto no vacío en supremo e ínfimo; los símbolos infinitos no son
  reales. La raíz cuadrada designa la raíz no negativa. La parte entera
  redondea hacia abajo, incluidos los negativos. Los intervalos encajados
  son cerrados, acotados y no vacíos; la unicidad exige longitudes tendiendo
  a cero. Se advierte la doble representación decimal por ceros y nueves.
- **Cortaduras, pp. 232–235.** Se conserva la convención de cortaduras
  derechas del libro, con orden por inclusión inversa. En opuesto e inverso
  se excluye el máximo del complementario cuando existe. El producto de
  elementos se utiliza directamente solo para cortaduras no negativas,
  y el inverso indicado requiere cortadura estrictamente positiva.

## Selección del tema 7 · Complejos

- Construcción por pares reales, forma binómica, operaciones, inverso,
  partes real e imaginaria, potencias de i; conjugación, módulo e
  interpretación del plano complejo.
- Argumento módulo una vuelta, formas trigonométrica, polar y exponencial;
  productos, cocientes, potencias, De Moivre y fórmulas de Euler.
- Todas las raíces n-ésimas y raíces de la unidad, procedimiento para
  raíces cuadradas binómicas y ecuaciones cuadráticas complejas.
- Afijos de vectores, distancias, puntos medios y ángulos; alineación,
  perpendicularidad, traslaciones, rotaciones, homotecias y simetrías.
- Imposibilidad de un orden total compatible con las operaciones;
  teorema fundamental del álgebra y factorización contando multiplicidades.
- Se reúnen procedimientos y relaciones, sin reproducir ejercicios,
  ejemplos resueltos, cálculos trigonométricos largos, figuras ni historia.

### Precisiones del tema 7

- **Módulo y argumento, pp. 248–251.** El módulo es no negativo, y es
  positivo únicamente fuera del cero. El argumento no se define para cero
  ni se trata como un único real sin elección de representante. Al convertir
  la forma binómica se conserva el cuadrante.
- **Raíces, pp. 254–257.** Para número no nulo y `n ≥ 1` se dan los n
  valores distintos, con índices de cero a n−1; el cero tiene una sola raíz.
  La descripción como polígono regular se limita a `n ≥ 3`. En raíces
  cuadradas binómicas los signos deben satisfacer el producto `2xy = v`.
  En la ecuación cuadrática se exige coeficiente principal no nulo y se
  distingue discriminante cero (raíz doble).
- **Geometría, pp. 258–263.** Para un ángulo se exigen vectores no nulos;
  el cociente usado para comparar direcciones debe tener denominador no
  nulo. Las homotecias llevan razón real no nula. La simetría de dirección
  alfa utiliza conjugación y el factor de ángulo doble.
- **Comentarios, pp. 263–264.** Se distingue orden algebraico de módulo;
  no se extiende la regla de raíz de un producto de reales no negativos
  a raíces complejas elegidas. La factorización incluye multiplicidades.

## Verificación conjunta definitiva

- Proyecto con siete archivos de tema, preámbulo compartido, entradas en
  `main.tex` y README actualizado. La vista previa abierta se ha regenerado
  en su mismo archivo, sin abrir otro documento ni sustituir el editor.
- PDF de 36 páginas: portada, dos páginas de índice y 33 de contenido
  (4, 6, 7, 4, 4, 4 y 4 páginas por tema). Revisión visual de las 36
  páginas; comprobadas fórmulas, tablas, encabezados, márgenes y saltos.
  Corregido un separador de espaciado mal escrito en la fórmula binómica/polar.
- Compilación final del archivo existente `vista-previa.tex` con pdfLaTeX
  (MiKTeX), dos pasadas, sin errores, referencias indefinidas, advertencias
  de LaTeX ni cajas desbordadas. Los 47 identificadores son únicos y las
  15 referencias internas tienen destino.
- Durante la elaboración, el compilador integrado del editor falló al preparar su entorno de
  Windows (`helper_unknown_error: setup refresh had errors`), antes de
  compilar las fuentes. El PDF validado se ha generado localmente desde
  el mismo archivo de vista previa; no es un PDF de otro documento.
- Comprobaciones aritméticas: 2020 divisiones enteras con resto y unicidad;
  1600 pares para Euclides y Bézout; Gauss para los enteros entre −10 y 10;
  1764 cuaternas de representantes para suma y producto racionales;
  criterio decimal para denominadores de 1 a 100, fracción generatriz y
  recuentos de variaciones/coeficientes binomiales en tamaños pequeños.
- Comprobados 2401 productos complejos y los cocientes con denominador
  no nulo, desigualdad triangular, raíces de órdenes 1–8 de los números
  no nulos considerados, conservación de distancias por rotación e
  involución de la simetría axial. Revisión algebraica de las restantes
  fórmulas e hipótesis; las comprobaciones finitas no sustituyen sus
  justificaciones matemáticas.
- Los temas 1–2 conservan sus fuentes y verificaciones anteriores. No hay
  materia teórica faltante ni ilegible pendiente de incorporar.
- PDF, auxiliares y vistas previas siguen excluidos de Git. No se han
  añadido ejercicios ni documentos sobre el proceso al material de estudio.

## Revisión previa al commit · 10 de octubre de 2026

- Releídos los siete temas y revisadas las hipótesis, excepciones,
  definiciones y fórmulas; no se han detectado errores matemáticos ni
  conceptos esenciales pendientes respecto del material proporcionado.
- Repetidas las comprobaciones de lógica, división entera, Bézout,
  operaciones racionales y complejas, desigualdad triangular y raíces.
- Confirmada la correspondencia de la vista previa con las fuentes,
  salvo líneas en blanco de separación; 47 etiquetas únicas y 15
  referencias resueltas. Compilación local en dos pasadas: 36 páginas,
  sin errores ni avisos de LaTeX o problemas de cajas.
- En esta revisión también ha compilado correctamente el archivo abierto
  con el compilador integrado del editor; la incidencia de preparación
  del entorno registrada durante la elaboración no se ha reproducido.
