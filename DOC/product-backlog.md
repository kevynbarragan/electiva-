# Product Backlog

## 1. Introducción

El Product Backlog contiene las historias de usuario que deben ser consideradas para el desarrollo del proyecto **Análisis de Intención de Compra en una Tienda Virtual**.

Las historias se encuentran ordenadas de acuerdo con su importancia para el funcionamiento del sistema y considerando las dependencias existentes entre ellas.

---

## 2. Product Backlog

| Orden | ID     | Historia de usuario                     | Prioridad |
| ----: | ------ | --------------------------------------- | --------- |
|     1 | HU-001 | Cargar dataset                          | MUST      |
|     2 | HU-002 | Validar dataset                         | MUST      |
|     3 | HU-003 | Identificar problemas en los datos      | MUST      |
|     4 | HU-004 | Preparar los datos                      | MUST      |
|     5 | HU-005 | Realizar análisis exploratorio          | MUST      |
|     6 | HU-006 | Identificar variables relevantes        | MUST      |
|     7 | HU-007 | Entrenar modelo                         | MUST      |
|     8 | HU-008 | Evaluar modelo                          | MUST      |
|     9 | HU-009 | Clasificar intención de compra          | MUST      |
|    10 | HU-014 | Ejecutar análisis completo              | MUST      |
|    11 | HU-010 | Consultar resultados                    | MUST      |
|    12 | HU-011 | Visualizar resultados mediante tablas   | SHOULD    |
|    13 | HU-012 | Visualizar resultados mediante gráficos | SHOULD    |
|    14 | HU-013 | Recibir información sobre errores       | SHOULD    |

---

## 3. Detalle del backlog

### 1. HU-001 — Cargar dataset

**Prioridad:** MUST

**Objetivo:**

Permitir que el analista cargue los datos necesarios para comenzar el análisis.

---

### 2. HU-002 — Validar dataset

**Prioridad:** MUST

**Objetivo:**

Verificar que el dataset tenga información adecuada para ser procesada.

---

### 3. HU-003 — Identificar problemas en los datos

**Prioridad:** MUST

**Objetivo:**

Identificar valores faltantes, inconsistencias y otros problemas que puedan afectar el análisis.

---

### 4. HU-004 — Preparar los datos

**Prioridad:** MUST

**Objetivo:**

Preparar los datos para que puedan ser utilizados correctamente en el análisis y entrenamiento del modelo.

---

### 5. HU-005 — Realizar análisis exploratorio

**Prioridad:** MUST

**Objetivo:**

Conocer las características y patrones presentes en el dataset.

---

### 6. HU-006 — Identificar variables relevantes

**Prioridad:** MUST

**Objetivo:**

Determinar cuáles variables pueden aportar información relevante para estimar la intención de compra.

---

### 7. HU-007 — Entrenar modelo

**Prioridad:** MUST

**Objetivo:**

Entrenar un modelo de Machine Learning utilizando los datos preparados.

---

### 8. HU-008 — Evaluar modelo

**Prioridad:** MUST

**Objetivo:**

Evaluar el desempeño del modelo mediante métricas adecuadas.

---

### 9. HU-009 — Clasificar intención de compra

**Prioridad:** MUST

**Objetivo:**

Generar la clasificación de intención de compra utilizando el modelo entrenado.

---

### 10. HU-014 — Ejecutar análisis completo

**Prioridad:** MUST

**Objetivo:**

Permitir ejecutar el flujo necesario para obtener los resultados del análisis.

---

### 11. HU-010 — Consultar resultados

**Prioridad:** MUST

**Objetivo:**

Permitir consultar los resultados obtenidos después de ejecutar el análisis.

---

### 12. HU-011 — Visualizar resultados mediante tablas

**Prioridad:** SHOULD

**Objetivo:**

Mostrar los resultados de forma organizada mediante tablas.

---

### 13. HU-012 — Visualizar resultados mediante gráficos

**Prioridad:** SHOULD

**Objetivo:**

Facilitar la interpretación de los resultados mediante representaciones gráficas.

---

### 14. HU-013 — Recibir información sobre errores

**Prioridad:** SHOULD

**Objetivo:**

Informar al usuario cuando se produzcan errores durante el funcionamiento del sistema.

---

## 4. Orden lógico de desarrollo

El backlog sigue principalmente el siguiente flujo:

```text
Cargar datos
     ↓
Validar datos
     ↓
Identificar problemas
     ↓
Preparar datos
     ↓
Analizar datos
     ↓
Identificar variables
     ↓
Entrenar modelo
     ↓
Evaluar modelo
     ↓
Clasificar intención
     ↓
Consultar resultados
     ↓
Visualizar resultados
```

El manejo de errores debe estar presente durante las diferentes etapas del sistema.

---

## 5. Alcance del Product Backlog

El Product Backlog se limita a las funcionalidades necesarias para desarrollar el MVP del proyecto.

No forman parte del backlog inicial:

* Pagos.
* Comercio electrónico completo.
* Recomendaciones personalizadas.
* Aplicación móvil nativa.
* Notificaciones avanzadas.
* Integraciones comerciales externas.

Estas funcionalidades podrían considerarse en versiones futuras, pero no son necesarias para alcanzar el objetivo actual.

---

## 6. Resultado esperado

Al completar las historias MUST, el sistema deberá ser capaz de:

1. Recibir un dataset.
2. Validar y preparar la información.
3. Analizar los datos.
4. Identificar variables relevantes.
5. Entrenar un modelo de Machine Learning.
6. Evaluar el modelo.
7. Clasificar la intención de compra.
8. Permitir consultar los resultados.

Las historias SHOULD permitirán mejorar principalmente la presentación y experiencia de uso de los resultados.

