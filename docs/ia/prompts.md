PROMPT 01 — ANÁLISIS COMPETITIVO.

Actúa como analista de negocios y analista de productos digitales senior, especializado en aplicaciones web y comercio electrónico.

CONTEXTO:
Somos un equipo de 3 estudiantes de Ingeniería de Sistemas de UNIMINUTO Ibagué. Tenemos 12 semanas efectivas para desarrollar un proyecto académico.

Nuestro proyecto consiste en desarrollar una aplicación web capaz de analizar la intención de compra de los usuarios de una tienda virtual a partir de su comportamiento de navegación.

La aplicación analizará variables como productos visitados, cantidad de clics, tiempo de navegación, productos agregados al carrito y otras variables disponibles en los datos. El objetivo es identificar patrones y estimar si un usuario presenta una intención de compra baja, media o alta.

El MVP contempla:
- Cargar o utilizar datos de comportamiento de navegación.
- Procesar y preparar los datos.
- Identificar variables relevantes.
- Utilizar un modelo de aprendizaje automático.
- Estimar el nivel de intención de compra.
- Mostrar los resultados en una interfaz web mediante tablas y gráficos.

TAREA:
Realiza un análisis competitivo de 3 soluciones, aplicaciones, plataformas o proyectos existentes que tengan relación directa con el análisis del comportamiento de usuarios, analítica de comercio electrónico, predicción de compras o intención de compra mediante datos.

FORMATO:
Entrega una tabla Markdown con las siguientes columnas:

| Competidor/Solución | Qué hace | Relación con nuestro proyecto | Tecnologías o enfoque conocido | Fortalezas | Limitaciones | Qué podemos aprender |

Después de la tabla, agrega:
1. Principales diferencias entre esas soluciones y nuestro proyecto.
2. Tres oportunidades de diferenciación técnica para nuestro MVP.
3. Tres riesgos que debemos considerar al comparar nuestro proyecto con estas soluciones.

RESTRICCIONES:
- Prioriza soluciones reales y verificables.
- No inventes nombres, funcionalidades, tecnologías ni datos.
- Si tienes acceso a búsqueda web, utiliza fuentes verificables y proporciona los enlaces o referencias utilizadas.
- Si no puedes verificar un dato, indícalo como "No verificado".
- No incluyas análisis de marketing, precios, ventas o rentabilidad.
- Enfócate exclusivamente en aspectos funcionales y técnicos relacionados con nuestro proyecto.
- No propongas funcionalidades fuera del alcance del MVP.
- Diferencia claramente entre información verificada y conclusiones propias.

EJEMPLO DEL NIVEL ESPERADO:

| Competidor/Solución | Qué hace | Relación con nuestro proyecto |
|---|---|---|
| Ejemplo verificable | Describe brevemente su función | Explica qué relación tiene con el análisis de comportamiento |

No utilices este ejemplo como un competidor real; solo úsalo para entender el formato y nivel de detalle esperado.


-----------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------
Evaluación del Prompt 1
1. Resumen de la evaluación

El prompt está bien construido, con rol, contexto y tarea claros, y con restricciones explícitas sobre verificación y alcance. La respuesta de la IA identificó tres competidores reales y verificables (Google Analytics 4 – Métricas Predictivas, el dataset UCI Online Shoppers Purchasing Intention y Nosto), respetó el formato de tabla solicitado y se mantuvo dentro del alcance del MVP. Sin embargo, incumplió una restricción explícita del prompt (no incluyó enlaces ni referencias verificables) y presentó dos cifras específicas sobre Nosto que no logré confirmar con fuentes actuales — una de ellas contradice la información disponible hoy — sin marcarlas como "No verificado", lo que constituye un fallo de control de alucinaciones.

2. Evaluación de los 6 componentes
Componente	Puntuación	Evaluación
Role	1/1	Rol específico y coherente con la tarea ("analista de negocios y de productos digitales senior, especializado en apps web y e-commerce"). No requiere ajustes.
Context	1/1	Contexto completo: equipo, tiempo disponible, objetivo del proyecto, MVP y alcance fuera del MVP. Permite a la IA entender qué tipo de competidores son relevantes.
Task	1/1	La tarea es concreta y acotada: análisis competitivo de exactamente 3 soluciones relacionadas con comportamiento de usuario/intención de compra.
Format	1/1	Especifica columnas exactas de la tabla y tres secciones posteriores obligatorias. La respuesta siguió esta estructura de forma literal.
Constraints	0.5/1	Las restricciones son numerosas y relevantes (verificabilidad, no inventar datos, marcar "No verificado", excluir marketing/precios), pero no exige explícitamente citar la fuente de cada dato ni indicar la fecha de consulta de cifras dinámicas (ej. número de clientes de una empresa), lo cual habría evitado el problema principal detectado en la respuesta.
Examples	0.5/1	El ejemplo aclara el nivel de detalle esperado, pero solo muestra 3 de las 7 columnas solicitadas, dejando parcialmente indefinido cómo debían verse columnas como "Fortalezas" o "Qué podemos aprender".
TOTAL	5/6	Prompt sólido y bien estructurado; el margen de mejora está en constraints (citación de fuentes) y examples (cobertura completa de columnas).
3. Evaluación de la respuesta generada
Cumplimientos
Los tres competidores elegidos son reales y verificables: confirmé mediante búsqueda web que GA4 sí ofrece métricas predictivas de probabilidad de compra/abandono con el umbral de 1.000 usuarios positivos y 1.000 negativos en 28 días exactamente como se describe, que el dataset UCI "Online Shoppers Purchasing Intention" tiene efectivamente 12.330 sesiones, 10 atributos numéricos y 8 categóricos con "Revenue" como etiqueta (autoría de Sakar, Kastro et al.), y que Nosto es una plataforma real de personalización con su producto "experience.AI".
Respetó exactamente la estructura de tabla de 7 columnas solicitada.
Incluyó las tres secciones adicionales pedidas (diferencias, oportunidades de diferenciación, riesgos), cada una con exactamente el número de elementos pedido (3).
Se mantuvo dentro del alcance técnico/funcional: no incluyó precios, marketing ni rentabilidad, cumpliendo esa restricción.
Usó correctamente la etiqueta "No verificado" al menos una vez (detalle de la licencia CC BY 4.0 del dataset UCI), mostrando que sí aplicó parcialmente la instrucción de marcar información no confirmable.
Problemas encontrados
Incumplimiento de una restricción explícita: el prompt exige "si tienes acceso a búsqueda web, utiliza fuentes verificables y proporciona los enlaces o referencias utilizadas". La respuesta no incluye ningún enlace ni bibliografía, en ninguna parte del documento.
Cifras no marcadas como "No verificado" que deberían haberlo sido: la fila de Nosto afirma "más de 2.500 minoristas en más de 100 países" y que la plataforma "procesa más de 1.100 millones de recomendaciones diarias", presentadas como hechos sin matiz alguno.
Información que requiere verificación
La cifra "más de 1.100 millones de recomendaciones diarias" de Nosto: NO VERIFICADO — no encontré ninguna fuente actual que respalde este dato específico.
El número "más de 2.500 minoristas" de Nosto: al buscarlo, las fuentes oficiales de Nosto (blog corporativo, LinkedIn, G2, comunicados de 2025-2026) indican consistentemente que Nosto da soporte a más de 1.500 marcas en más de 100 países, no 2.500. Esto es una discrepancia significativa, no solo un dato "no verificado" sino aparentemente incorrecto frente a la evidencia disponible. 
Nosto launches AI-powered Post-Purchase Upsell for Shopify +3

Posibles alucinaciones

Sí se detectó una probable alucinación o dato desactualizado/inventado: la cifra de "2.500 minoristas" para Nosto contradice directamente lo que reportan múltiples fuentes actuales e independientes (sitio oficial de Nosto, LinkedIn, G2), que coinciden en ~1.500 marcas. La cifra de "1.100 millones de recomendaciones diarias" tampoco pudo confirmarse en ninguna fuente consultada. Ambas cifras se presentaron como hechos verificados, sin la etiqueta "No verificado" que el prompt exigía para este tipo de casos.

4. ¿Qué funcionó?
El rol y el contexto fueron suficientemente específicos como para que la IA seleccionara competidores realmente pertinentes (no genéricos): un producto de analítica con ML real (GA4), un dataset académico casi idéntico al problema planteado (UCI) y un SaaS comercial de personalización (Nosto), cubriendo tres ángulos distintos (analítica nativa, dataset académico, producto comercial).
La respuesta respetó fielmente la estructura de tabla y las tres secciones adicionales solicitadas, sin omitir ni agregar apartados.
Se mantuvo dentro del alcance del MVP: no propuso funcionalidades fuera de alcance (recomendación avanzada, pagos, apps móviles), y de hecho advirtió explícitamente sobre riesgos de comparar el MVP con productos maduros como GA4 o Nosto, lo cual es coherente con el contexto de un proyecto académico de 12 semanas.
Usó al menos una vez la etiqueta "No verificado" tal como exigía el prompt, demostrando que la instrucción fue comprendida, aunque no se aplicó de forma consistente en todos los casos que lo requerían.
5. ¿Qué no funcionó?
No se proporcionó ningún enlace ni referencia, pese a que el prompt lo exige explícitamente cuando hay acceso a búsqueda web.
Se presentaron cifras estadísticas específicas y potencialmente desactualizadas o incorrectas (número de minoristas de Nosto, volumen de recomendaciones diarias) sin la etiqueta "No verificado", lo que es justamente el tipo de error que la restricción del prompt buscaba prevenir.
El ejemplo de formato incluido en el prompt original no cubría las 7 columnas, lo que pudo dejar ambigüedad sobre el nivel de detalle esperado en columnas como "Tecnologías o enfoque conocido".
6. Correcciones realizadas o recomendadas
Problema	Corrección
No se incluyeron enlaces ni referencias pese a exigirlo el prompt.	Mover la exigencia de citar fuentes del bloque de RESTRICCIONES al bloque de FORMATO, indicando explícitamente: "Agrega una columna o sección de 'Fuente' con el enlace verificable de cada competidor."
Se presentaron cifras concretas (número de clientes, volumen de uso) como hechos sin marcarlas como "No verificado", y al menos una de ellas no coincide con la evidencia disponible.	Añadir una restricción explícita: "Toda cifra estadística específica (número de usuarios, clientes, volumen de datos, porcentajes) debe ir acompañada de su fuente y fecha de publicación. Si no puedes confirmar la cifra con una fuente verificable, indícala como 'No verificado' en lugar de presentarla como un hecho."
El ejemplo de formato solo mostraba 3 de las 7 columnas solicitadas.	Ampliar el ejemplo para incluir las 7 columnas completas, aunque sea con contenido breve, para fijar el nivel de detalle esperado en cada una.
No se exige indicar la fecha de la información recuperada por búsqueda web, relevante para datos que cambian con el tiempo (ej. número de clientes de una empresa).
-----------------------------------------------------------------------------------------------------------------------------
PROMT SUGERIDO O MEJORADO:
-----------------------------------------------------------------------------------------------------------------------------
Actúa como analista de negocios y analista de productos digitales senior, especializado en aplicaciones web y comercio electrónico.

CONTEXTO:
Somos un equipo de 3 estudiantes de Ingeniería de Sistemas de UNIMINUTO Ibagué. Tenemos 12 semanas efectivas para desarrollar un proyecto académico.

Nuestro proyecto consiste en desarrollar una aplicación web capaz de analizar la intención de compra de los usuarios de una tienda virtual a partir de su comportamiento de navegación (productos visitados, clics, tiempo de navegación, productos agregados al carrito y otras variables disponibles en los datos), clasificando la intención en baja, media o alta.

El MVP contempla: cargar/usar datos de comportamiento, procesarlos, identificar variables relevantes, implementar un modelo de Machine Learning, estimar el nivel de intención de compra por usuario, y mostrar resultados en una interfaz web con tablas y gráficos básicos.

TAREA:
Realiza un análisis competitivo de 3 soluciones, aplicaciones, datasets o plataformas existentes y reales relacionadas con análisis de comportamiento de usuarios, analítica de e-commerce o predicción/estimación de intención de compra.

FORMATO:
Entrega una tabla Markdown con las columnas:
| Competidor/Solución | Qué hace | Relación con nuestro proyecto | Tecnologías o enfoque conocido | Fortalezas | Limitaciones | Qué podemos aprender | Fuente (enlace o referencia) |

Después de la tabla, agrega:
1. Principales diferencias entre esas soluciones y nuestro proyecto.
2. Tres oportunidades de diferenciación técnica para nuestro MVP.
3. Tres riesgos que debemos considerar al comparar nuestro proyecto con estas soluciones.

RESTRICCIONES:
- Prioriza soluciones reales y verificables; no inventes nombres, funcionalidades, tecnologías ni cifras.
- Toda cifra estadística concreta (usuarios, clientes, volumen de datos, porcentajes, etc.) debe incluir su fuente y, si es relevante, la fecha aproximada del dato. Si no puedes confirmarla con una fuente verificable, escribe "No verificado" en lugar de presentarla como hecho.
- Incluye siempre el enlace o referencia usada para cada competidor en la columna "Fuente".
- No incluyas análisis de marketing, precios, ventas o rentabilidad.
- Enfócate exclusivamente en aspectos funcionales y técnicos relacionados con nuestro proyecto.
- No propongas funcionalidades fuera del alcance del MVP.
- Diferencia claramente entre información verificada y conclusiones propias.

EJEMPLO DEL NIVEL ESPERADO (no usar como competidor real, solo como referencia de formato):
| Competidor/Solución | Qué hace | Relación con nuestro proyecto | Tecnologías o enfoque conocido | Fortalezas | Limitaciones | Qué podemos aprender | Fuente |
|---|---|---|---|---|---|---|---|
| Ejemplo verificable | Describe brevemente su función | Explica la relación con el análisis de comportamiento | Enfoque técnico conocido | Puntos fuertes reales | Limitaciones reales | Aprendizaje aplicable al MVP | Enlace o referencia consultada |
