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
-----------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------
PROMPT 02 — DOCUMENTO DE VISIÓN.


Actúa como analista de sistemas y redactor de documentos de visión de software senior.

CONTEXTO:
Somos un equipo de 3 estudiantes de Ingeniería de Sistemas de UNIMINUTO Ibagué y desarrollaremos un proyecto académico durante 12 semanas efectivas.

IDEA DEL PROYECTO:
Desarrollaremos una aplicación web capaz de analizar la intención de compra de los usuarios de una tienda virtual a partir de su comportamiento de navegación.

El sistema procesará datos como productos visitados, cantidad de clics, tiempo de navegación, productos agregados al carrito y otras variables relevantes.

A partir de estos datos se buscarán patrones de comportamiento y se estimará el nivel de intención de compra de un usuario, clasificándolo como baja, media o alta intención de compra.

MVP:
- Carga o utilización de un conjunto de datos de navegación.
- Procesamiento y preparación de datos.
- Identificación de variables relevantes.
- Modelo de aprendizaje automático.
- Estimación de intención de compra.
- Visualización de resultados mediante una aplicación web.
- Tablas y gráficos básicos.

TAREA:
Genera un documento de visión inicial para nuestro proyecto.

FORMATO:
Utiliza Markdown y organiza el documento exactamente en estas secciones:

# Documento de Visión

## 1. Problema
## 2. Usuarios objetivo
## 3. Necesidad identificada
## 4. Propuesta de valor
## 5. Solución propuesta
## 6. Alcance del MVP
## 7. Fuera del alcance
## 8. Beneficios esperados
## 9. Supuestos
## 10. Preguntas abiertas

En "Preguntas abiertas", incluye máximo 5 preguntas cuya respuesta pueda cambiar decisiones importantes del proyecto.

RESTRICCIONES:
- No inventes información que no esté en el contexto.
- Si necesitas realizar una suposición, márcala explícitamente como [SUPUESTO].
- No agregues pagos, recomendaciones personalizadas, aplicaciones móviles, chat, notificaciones ni funcionalidades de IA innecesarias.
- No conviertas el documento en un plan de marketing.
- No inventes estadísticas sobre usuarios o tiendas virtuales.
- Mantén el alcance realista para un equipo de 3 estudiantes y 12 semanas.
- El documento debe servir como base para posteriores requisitos de software.

EJEMPLO DEL NIVEL ESPERADO:

## 1. Problema
Los datos generados durante la navegación de una tienda virtual pueden contener señales relacionadas con el comportamiento de compra, pero esas señales no siempre se analizan de manera estructurada para estimar la intención de compra.

## 4. Propuesta de valor
[Redactar una propuesta concreta basada únicamente en el contexto proporcionado.]

No copies literalmente los ejemplos; utilízalos únicamente como referencia de estructura y nivel de precisión.
-----------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------
Evaluación del Prompt 2
1. Resumen de la evaluación

El prompt está muy bien construido: define una estructura exacta de 10 secciones, restricciones claras sobre alcance y honestidad epistémica (uso de [SUPUESTO]), y limita el número de preguntas abiertas. La respuesta de la IA siguió correctamente la estructura, marcó apropiadamente las suposiciones, respetó el alcance del MVP y no inventó estadísticas externas. Sin embargo, comparando ambos documentos se detecta un incumplimiento verificable de una restricción explícita: la sección "1. Problema" reproduce casi literalmente la oración de ejemplo del prompt, pese a la instrucción de no copiar los ejemplos textualmente.

2. Evaluación de los 6 componentes
Componente	Puntuación	Evaluación
Role	1/1	"Analista de sistemas y redactor de documentos de visión de software senior" es un rol específico y directamente aplicable a la tarea.
Context	1/1	Incluye equipo, tiempo disponible, idea del proyecto y MVP resumido; suficiente para redactar el documento sin ambigüedad sobre el objetivo del sistema.
Task	1/1	"Genera un documento de visión inicial" es una tarea clara, y la instrucción adicional sobre el límite de preguntas en la sección 10 la hace aún más precisa.
Format	1/1	Especifica exactamente las 10 secciones y su encabezado Markdown, sin dejar ambigüedad sobre la estructura esperada.
Constraints	0.5/1	Son extensas y pertinentes (no inventar información, marcar supuestos, no ampliar alcance, no estadísticas, no marketing), pero la instrucción contra copiar el ejemplo ("no copies literalmente") resultó insuficiente en la práctica: la respuesta la incumplió de forma verificable, lo que sugiere que debería reforzarse (p. ej. "no reproduzcas ninguna oración del ejemplo, ni siquiera parcialmente").
Examples	0.5/1	El ejemplo aclara el nivel de precisión esperado, pero al usar contenido temáticamente casi idéntico al problema real (mismo dominio, misma redacción posible), incrementa el riesgo de copia textual, como efectivamente ocurrió. Un ejemplo de otro dominio habría cumplido la misma función de referencia estructural con menos riesgo.
TOTAL	5/6	Prompt muy sólido; el margen de mejora está en constraints (prohibición de copia más explícita) y en el diseño del ejemplo (usar un dominio distinto).
3. Evaluación de la respuesta generada
Cumplimientos
Siguió exactamente las 10 secciones solicitadas, en el orden y con los encabezados pedidos.
Usó la etiqueta [SUPUESTO] de forma consistente y justificada en los puntos donde el contexto no ofrecía información (usuarios objetivo, origen de los datos, conocimientos del equipo, tipo de evaluación del proyecto, alcance de integración en tiempo real).
La sección "10. Preguntas abiertas" contiene exactamente 5 preguntas (el máximo permitido), y todas están relacionadas con decisiones que efectivamente podrían cambiar el rumbo del proyecto (origen de los datos, variables disponibles, existencia de ground truth para entrenamiento supervisado, carga dinámica de datos, nivel de precisión aceptable).
No se agregaron funcionalidades fuera del MVP: la sección "7. Fuera del alcance" excluye explícitamente pagos, recomendaciones personalizadas, apps móviles, chat y notificaciones, tal como exigía el prompt.
No se inventaron estadísticas sobre usuarios o tiendas virtuales en ninguna sección.
El documento mantiene un alcance realista para un equipo de 3 estudiantes en 12 semanas, y lo declara explícitamente como supuesto en la sección 9.
Problemas encontrados
Incumplimiento verificable de una restricción explícita: la primera oración de la sección "1. Problema" del documento generado ("Los datos generados durante la navegación de una tienda virtual pueden contener señales relacionadas con el comportamiento de compra, pero esas señales no siempre se analizan de manera estructurada para estimar la intención de compra") es prácticamente idéntica, palabra por palabra, al texto de ejemplo incluido en el prompt para la misma sección. El prompt indicaba explícitamente "No copies literalmente los ejemplos; utilízalos únicamente como referencia de estructura y nivel de precisión", instrucción que no se respetó en este punto.
No se detectaron otros incumplimientos de formato, alcance o restricciones.
Información que requiere verificación

Este documento no contiene afirmaciones externas verificables (no hay cifras, nombres de empresas ni datos de terceros), por lo que no aplica el uso de "No verificado" salvo en el punto de copia textual detectado, que es un hecho comprobable directamente comparando los dos textos, no una incertidumbre externa.

Posibles alucinaciones

No se detectaron posibles alucinaciones con la información disponible. El problema identificado es de reproducción textual de una fuente proporcionada por el propio prompt (el ejemplo), no de invención de datos falsos.

4. ¿Qué funcionó?
El uso de [SUPUESTO] fue preciso y se limitó a los puntos donde realmente faltaba información en el contexto (por ejemplo, en "Usuarios objetivo" se señaló correctamente que no hay una definición precisa de quién usará el sistema), lo cual demuestra que la IA distinguió bien entre lo dado y lo inferido.
El límite de 5 preguntas abiertas se cumplió exactamente, y las preguntas elegidas tienen relevancia real para el proyecto (ground truth para entrenamiento supervisado, origen de los datos), no son preguntas genéricas de relleno.
El documento respetó rigurosamente el alcance fuera del MVP definido en el prompt, sin agregar ninguna funcionalidad no solicitada (ni siquiera sugerencias veladas de recomendaciones o pagos).
No hay señales de invención de estadísticas o datos de mercado, cumpliendo una restricción que suele ser fuente común de alucinaciones en este tipo de documentos.
5. ¿Qué no funcionó?
La sección "Problema" copió casi literalmente la redacción del ejemplo del prompt, en lugar de usarla solo como referencia de estructura y nivel de precisión, tal como se pedía explícitamente.
El riesgo de esta copia se vio favorecido por el diseño del propio ejemplo (mismo dominio y fraseo natural para el tema), lo que facilitó que la IA lo reutilizara en vez de generar una redacción propia.
6. Correcciones realizadas o recomendadas
Problema	Corrección
La respuesta copió casi literalmente la oración de ejemplo en la sección "Problema", pese a la restricción explícita contra esto.	Reforzar la restricción con una frase más estricta: "No reproduzcas ninguna oración del ejemplo, ni siquiera parcialmente; redacta cada sección completamente con palabras propias, aunque el contenido temático sea similar."
El ejemplo proporcionado usaba el mismo dominio y fraseo del proyecto real, lo que facilitó la copia.	Sustituir el ejemplo de la sección "Problema" por uno de un dominio distinto (por ejemplo, un sistema de gestión de inventario en lugar de e-commerce), manteniendo el mismo nivel de precisión pero eliminando el riesgo de copia literal.

PROMT FINAL SUGERIDO:
PROMPT 02 — DOCUMENTO DE VISIÓN.
Actúa como analista de sistemas y redactor de documentos de visión de software senior.

CONTEXTO: Somos un equipo de 3 estudiantes de Ingeniería de Sistemas de UNIMINUTO Ibagué y desarrollaremos un proyecto académico durante 12 semanas efectivas.

IDEA DEL PROYECTO: Desarrollaremos una aplicación web capaz de analizar la intención de compra de los usuarios de una tienda virtual a partir de su comportamiento de navegación.
El sistema procesará datos como productos visitados, cantidad de clics, tiempo de navegación, productos agregados al carrito y otras variables relevantes.
A partir de estos datos se buscarán patrones de comportamiento y se estimará el nivel de intención de compra de un usuario, clasificándolo como baja, media o alta intención de compra.

MVP: - Carga o utilización de un conjunto de datos de navegación. - Procesamiento y preparación de datos. - Identificación de variables relevantes. - Modelo de aprendizaje automático. - Estimación de intención de compra. - Visualización de resultados mediante una aplicación web. - Tablas y gráficos básicos.

TAREA: Genera un documento de visión inicial para nuestro proyecto.

FORMATO: Utiliza Markdown y organiza el documento exactamente en estas secciones:
# Documento de Visión
## 1. Problema ## 2. Usuarios objetivo ## 3. Necesidad identificada ## 4. Propuesta de valor ## 5. Solución propuesta ## 6. Alcance del MVP ## 7. Fuera del alcance ## 8. Beneficios esperados ## 9. Supuestos ## 10. Preguntas abiertas

En "Preguntas abiertas", incluye máximo 5 preguntas cuya respuesta pueda cambiar decisiones importantes del proyecto.

RESTRICCIONES:
- No inventes información que no esté en el contexto.
- Si necesitas realizar una suposición, márcala explícitamente como [SUPUESTO].
- No agregues pagos, recomendaciones personalizadas, aplicaciones móviles, chat, notificaciones ni funcionalidades de IA innecesarias.
- No conviertas el documento en un plan de marketing.
- No inventes estadísticas sobre usuarios o tiendas virtuales.
- Mantén el alcance realista para un equipo de 3 estudiantes y 12 semanas.
- El documento debe servir como base para posteriores requisitos de software.
- No reproduzcas ninguna oración del ejemplo siguiente, ni siquiera parcialmente; úsalo únicamente como referencia de estructura y nivel de precisión, y redacta cada sección completamente con tus propias palabras.

EJEMPLO DEL NIVEL ESPERADO (de un dominio distinto, solo como referencia de estructura, NO copiar frases):
## 1. Problema
Un sistema de gestión de inventario en una bodega puede generar registros de entradas y salidas de productos, pero sin un mecanismo de análisis estructurado, esos registros no se traducen en alertas claras sobre quiebres de stock.
## 4. Propuesta de valor
[Redactar una propuesta concreta basada únicamente en el contexto proporcionado, con redacción original.]

-----------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------
PROMPT 03 — EVALUACIÓN Y MEJORA DEL PROMPT

Actúa como experto en Prompt Engineering para proyectos de software.

CONTEXTO:
Estamos desarrollando un proyecto académico de Ingeniería de Sistemas en UNIMINUTO Ibagué.

Nuestro proyecto es una aplicación web que analiza la intención de compra en una tienda virtual a partir del comportamiento de navegación de los usuarios.

El prompt que vas a evaluar será utilizado para obtener resultados relacionados con este proyecto.

TAREA:
Evalúa el prompt delimitado entre ### utilizando exactamente los 6 componentes de un prompt profesional:

1. Rol
2. Contexto
3. Tarea
4. Formato
5. Restricciones
6. Ejemplos

CALIFICA cada componente con:
- 0 = ausente o inútil
- 1 = presente y útil

FORMATO:
Entrega:

### Evaluación

| Componente | Puntuación (0-1) | ¿Está bien definido? | Mejora necesaria |
|---|---:|---|---|

**Puntuación total:** X/6

### Problemas principales
Máximo 5 puntos.

### Prompt mejorado
Devuelve el prompt completo, listo para copiar y pegar.

### Cambios realizados
Máximo 3 líneas.

RESTRICCIONES:
- No ejecutes el prompt original.
- No cambies el objetivo de la tarea.
- No agregues funcionalidades que no pertenezcan al proyecto.
- No hagas el prompt innecesariamente largo.
- Mantén el contexto suficiente para que otra IA pueda ejecutarlo correctamente.
- Si un componente ya está bien construido, consérvalo.
- Prioriza claridad y precisión sobre longitud.

EJEMPLO DE CRITERIO:
Un prompt que diga solamente "analiza mi proyecto" tendría una puntuación baja porque no define claramente rol, tarea, formato ni restricciones.

###
[PEGAR AQUÍ EL PROMPT A EVALUAR]
###
