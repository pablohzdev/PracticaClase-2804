# Práctica Temática: **Diseño de Propuesta de Mini Proyecto de Sistemas**

## 1) Título de la práctica
**Propuesta de Mini Proyecto Temático (Documentación Primero)**

> Ejemplos de enfoque temático que puedes tomar:
> - **Mini Toolkit en ARM64**
> - **Asistente de Estudio en Terminal**
> - **Reporteador de Información del Sistema**
> - **Organizador de Archivos**
> - **Juego de Aprendizaje en Línea de Comandos**

---

## 2) Descripción general
En esta actividad **no se busca desarrollar un sistema grande**, sino diseñar y documentar una propuesta clara de un proyecto pequeño orientado a arquitectura de computadoras y programación de sistemas.

Como estudiante, vas a plantear una práctica temática viable para implementarse en poco tiempo, con herramientas simples y sin dependencias pesadas. Debes elegir **un lenguaje principal** para tu propuesta:

- **ARM64 Assembly**
- **C**
- **Python**
- **Bash**

> **Nota importante:** Si eliges **ARM64 Assembly**, se recomienda que tu programa sea **muy pequeño** (por ejemplo, utilería de consola con pocas funciones), debido al nivel de detalle del lenguaje.

La prioridad de esta actividad es:
1. **Documentar la idea**.
2. **Justificar su utilidad**.
3. **Definir estructura de repositorio**.
4. **Planear pruebas básicas**.

El código puede ser mínimo o incluso quedar como prototipo; lo más importante es la calidad de la propuesta técnica.

---

## 3) Objetivo de aprendizaje
Al finalizar esta práctica, serás capaz de:

- Formular una propuesta técnica pequeña y realista.
- Justificar decisiones de diseño de software en contexto de sistemas.
- Estructurar un repositorio académico de forma ordenada.
- Definir un plan de pruebas básico y medible.

---

## 4) Alcance y restricciones
Tu propuesta debe cumplir con estas restricciones:

- Proyecto **pequeño** y alcanzable.
- Enfocado en **terminal** o ejecución local.
- Sin frameworks grandes.
- Sin APIs pagadas.
- Sin bases de datos complejas.
- Sin servicios de nube.
- Sin contenedores.
- Sin dependencias difíciles de instalar.

La idea es que pueda avanzarse incluso con herramientas gratuitas y con límites de uso de IA.

---

## 5) Entregables del estudiante
Tu repositorio debe incluir, como mínimo:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`
- opcional: `src/`
- opcional: `scripts/`
- opcional: `tests/`

---

## 6) Estructura recomendada del repositorio
Usa esta base mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> Puedes ajustar carpetas opcionales según tu lenguaje, pero debes conservar la parte de documentación.

---

## 7) Instrucciones de contenido por archivo

### `README.md`
Debe incluir:
- Nombre del proyecto.
- Resumen en 5–8 líneas.
- Lenguaje principal elegido.
- Cómo ejecutar (si hay prototipo).
- Estructura general del repo.
- Integrantes (si aplica).

### `docs/propuesta.md`
Debe responder:
1. ¿Qué problema pequeño resuelve tu proyecto?
2. ¿Quién lo usaría?
3. ¿Por qué es viable en esta materia?
4. ¿Qué funcionalidades mínimas tendrá (MVP)?
5. ¿Qué **no** incluirá para mantener el alcance pequeño?

### `docs/caso_de_uso.md`
Incluye:
- Actor principal.
- Escenario de uso paso a paso.
- Entrada esperada.
- Salida esperada.
- Al menos 1 escenario alterno (error o uso inválido).

### `docs/estructura_repositorio.md`
Explica:
- Árbol del repositorio.
- Propósito de cada carpeta/archivo.
- Convención de nombres básica (por ejemplo, `snake_case`, prefijos, etc.).

### `docs/plan_de_pruebas.md`
Define:
- Objetivo de pruebas.
- Casos de prueba mínimos (tabla recomendada).
- Criterios de aceptación.
- Evidencia esperada (capturas, salida de terminal, logs simples).

Tabla sugerida:

| ID | Caso | Entrada | Resultado esperado | Estado |
|----|------|---------|--------------------|--------|
| CP-01 | Flujo normal | ... | ... | Pendiente |
| CP-02 | Entrada inválida | ... | ... | Pendiente |

---

## 8) Guía de tamaño del proyecto (recomendación)

Para mantenerlo pequeño:
- Entre **1 y 3 funcionalidades principales**.
- Entre **1 y 5 archivos de código** máximo al inicio.
- Pruebas manuales simples documentadas.
- Duración estimada de implementación: **4 a 8 horas**.

Ejemplos de alcance correcto:
- Script Bash que organiza archivos por extensión y genera reporte.
- Programa en C que analiza argumentos y muestra métricas simples.
- Script Python de apoyo académico en terminal con menú básico.
- Mini ejercicio ARM64 que lea un valor y despliegue resultado simple.

---

## 9) Criterios de evaluación sugeridos (100%)

- **Claridad de la propuesta** (25%)
- **Coherencia del caso de uso** (20%)
- **Calidad de estructura del repositorio** (20%)
- **Plan de pruebas y criterios de aceptación** (20%)
- **Redacción técnica y orden documental** (15%)

---

## 10) Checklist de entrega (para el estudiante)
Antes de enviar, valida:

- [ ] Elegí un lenguaje principal (ARM64 Assembly, C, Python o Bash).
- [ ] Mi idea es pequeña y realista.
- [ ] Entregué todos los archivos obligatorios en `docs/`.
- [ ] Expliqué claramente el caso de uso.
- [ ] Definí pruebas mínimas y criterios de aceptación.
- [ ] Mi `README.md` permite entender el proyecto sin explicaciones extra.

---

## 11) Formato de entrega
- Entrega mediante el repositorio asignado en GitHub Classroom.
- Asegúrate de que los archivos estén en la rama principal solicitada por el docente.
- Si incluyes código, debe compilar/ejecutar con instrucciones simples en `README.md`.

---

## 12) Nota final del instructor
Piensa como ingeniera/o de sistemas: **primero diseña, luego codifica**. Una propuesta bien documentada evita retrabajos, mejora la calidad del proyecto y facilita la evaluación técnica.
