# Priorización MoSCoW

## 1. Introducción

La priorización MoSCoW permite determinar cuáles historias de usuario son indispensables para el funcionamiento del proyecto y cuáles pueden tener una prioridad menor.

Las categorías utilizadas son:

* **MUST:** Debe realizarse.
* **SHOULD:** Debería realizarse.
* **COULD:** Podría realizarse.
* **WON'T:** No se realizará en esta versión.

---

## 2. Historias MUST

### HU-001 — Cargar dataset

**Prioridad:** MUST

**Justificación:**

Es indispensable disponer de los datos para iniciar el proceso de análisis.

---

### HU-002 — Validar dataset

**Prioridad:** MUST

**Justificación:**

Los datos deben ser revisados antes de utilizarlos para evitar problemas durante el procesamiento.

---

### HU-003 — Identificar problemas en los datos

**Prioridad:** MUST

**Justificación:**

Es necesario conocer los problemas existentes en el dataset para poder tratarlos antes del análisis.

---

### HU-004 — Preparar los datos

**Prioridad:** MUST

**Justificación:**

El modelo requiere datos preparados correctamente para producir resultados adecuados.

---

### HU-005 — Realizar análisis exploratorio

**Prioridad:** MUST

**Justificación:**

El análisis exploratorio permite comprender los datos y encontrar patrones relevantes para el proyecto.

---

### HU-006 — Identificar variables relevantes

**Prioridad:** MUST

**Justificación:**

La selección de variables relevantes es necesaria para desarrollar un modelo adecuado.

---

### HU-007 — Entrenar modelo

**Prioridad:** MUST

**Justificación:**

El proyecto requiere un modelo de Machine Learning para realizar la estimación de intención de compra.

---

### HU-008 — Evaluar modelo

**Prioridad:** MUST

**Justificación:**

Es necesario evaluar el modelo para conocer la calidad de sus resultados.

---

### HU-009 — Clasificar intención de compra

**Prioridad:** MUST

**Justificación:**

Es el resultado principal que busca obtener el proyecto.

---

### HU-010 — Consultar resultados

**Prioridad:** MUST

**Justificación:**

Los resultados deben estar disponibles para que el usuario pueda consultarlos.

---

### HU-014 — Ejecutar análisis completo

**Prioridad:** MUST

**Justificación:**

El sistema debe permitir ejecutar el flujo necesario para obtener los resultados finales.

---

## 3. Historias SHOULD

### HU-011 — Visualizar resultados mediante tablas

**Prioridad:** SHOULD

**Justificación:**

Las tablas facilitan la consulta de los resultados, aunque el objetivo principal puede cumplirse sin una visualización avanzada.

---

### HU-012 — Visualizar resultados mediante gráficos

**Prioridad:** SHOULD

**Justificación:**

Los gráficos facilitan la interpretación de los resultados y mejoran la experiencia del usuario.

---

### HU-013 — Recibir información sobre errores

**Prioridad:** SHOULD

**Justificación:**

El manejo claro de errores es importante para la usabilidad y confiabilidad del sistema.

---

## 4. Historias COULD

Actualmente no se consideran historias adicionales como COULD debido a que el alcance inicial se encuentra enfocado en las funcionalidades necesarias para cumplir el objetivo principal.

En caso de contar con tiempo adicional, podrían incorporarse mejoras visuales o funcionalidades adicionales previamente aprobadas.

---

## 5. Historias WON'T

Las siguientes funcionalidades se consideran fuera del alcance de la versión inicial:

* Sistema de pagos.
* Implementación de una tienda virtual completa.
* Recomendaciones personalizadas.
* Aplicación móvil nativa.
* Notificaciones avanzadas.
* Integración con sistemas comerciales externos.

Estas funcionalidades podrían evaluarse en versiones futuras, pero no son necesarias para cumplir el objetivo actual.

---

## 6. Resumen

| Categoría | Historias                                                                              |
| --------- | -------------------------------------------------------------------------------------- |
| MUST      | HU-001, HU-002, HU-003, HU-004, HU-005, HU-006, HU-007, HU-008, HU-009, HU-010, HU-014 |
| SHOULD    | HU-011, HU-012, HU-013                                                                 |
| COULD     | Ninguna actualmente                                                                    |
| WON'T     | Funcionalidades fuera del alcance inicial                                              |

## 7. Conclusión

La priorización establece que el núcleo del proyecto está compuesto por la carga y preparación de datos, el análisis, el desarrollo y evaluación del modelo y la clasificación de intención de compra.

Las funcionalidades de visualización y manejo de errores tienen una prioridad SHOULD porque complementan el sistema, pero pueden desarrollarse después de garantizar el funcionamiento del núcleo principal.

