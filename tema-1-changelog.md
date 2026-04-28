# Tema 1 — Changelog

> **Título oficial**: La Constitución Española (I): Estructura y contenido. Derechos y deberes fundamentales. Su garantía y suspensión.

---

## v2.0 — 2026-04-28 — Ampliación en profundidad de derechos y deberes

**Estado**: pendiente de validación por María y Ana.

**Motivo**: feedback tras revisión de María/Ana de la v1.0 — falta profundidad en la parte de derechos y deberes fundamentales, su garantía y suspensión. Hay que pedir más profundidad en los contenidos para que el material aprueble en una sola iteración.

### Resumen de cambios v2.0

| Aspecto | v1.0 | v2.0 | Δ |
|---|---|---|---|
| Palabras | ~4.600 | ~11.000 | +139% |
| Detalle por artículo (5.2 arts. 14-29) | 1 frase por artículo (16 artículos) | Cuasi-literal BOE + apartados internos + LO desarrollo + doctrina TC | +3.000 palabras |
| Detalle por artículo (5.3 arts. 30-38) | 1 frase por artículo (9 artículos) | Cuasi-literal BOE + apartados + ley de desarrollo | +1.500 palabras |
| Detalle por artículo (5.4 arts. 39-52) | 1 frase por artículo (14 artículos) | Cuasi-literal BOE + apartados + ley desarrollo + ejemplo Ayto Madrid | +2.000 palabras |
| Fuentes añadidas | 4 | 33 (+29: 22 leyes orgánicas/ordinarias de desarrollo + 7 sentencias TC clave) | +29 |
| Reglamento (UE) 2016/679 (RGPD) | mencionado | conectado al art. 18.4 CE | nueva referencia |

### Cambios v2.0 por sección

**Sección 5.2 — Derechos fundamentales y libertades públicas (arts. 14-29)**:
- Cada artículo ahora tiene su propio bloque con:
  - Cita literal o cuasi-literal del BOE entre comillas dobles, con referencia `[CE, art. X]`.
  - Apartados internos (.1, .2, .3...).
  - Reserva de ley orgánica del art. 81 cuando aplica.
  - Ley(es) de desarrollo concreta(s).
  - Doctrina del Tribunal Constitucional más relevante (STC con número y materia).
- Cobertura completa de los 16 artículos: 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29. **Antes faltaban completamente** los arts. 23, 25 (interno), 26, y la mayoria solo tenían una frase.
- Añadido bloque dedicado al art. 18.4 (protección de datos) por su relevancia para el bloque técnico.

**Sección 5.3 — Derechos y deberes de los ciudadanos (arts. 30-38)**:
- Cada artículo (30, 31, 32, 33, 34, 35, 36, 37, 38) con redacción completa, apartados y desarrollo legislativo.
- Añadido el caso de la **objeción de conciencia del art. 30.2** como única excepción fuera de los arts. 14-29 amparable ante el TC.
- Anadidos enlaces a leyes de desarrollo: Código Civil, LET, Ley 50/2002 Fundaciones, RDL 2/2004 Haciendas Locales, etc.

**Sección 5.4 — Principios rectores (arts. 39-52)**:
- Cada artículo (39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52) con redacción completa, apartados y leyes de desarrollo.
- Doctrina constitucional sobre eficacia limitada (art. 53.3): mandato al legislador, criterio interpretativo, vinculación poderes públicos.
- Nuevo callout EJEMPLO AYTO MADRID con materialización local de los principios (Red Bibliotecas, EMVS, Concejalia Familias, etc.).
- Reforma 2024 del art. 49 con texto literal nuevo y reforma original explicada.

### Fuentes añadidas en v2.0

22 leyes de desarrollo (orgánicas y ordinarias) y 7 sentencias del Tribunal Constitucional. Ver `tema-1-fuentes.md` para el detalle.

---

## v1.0 — 2026-04-23 — Borrador inicial

**Estado**: pendiente de validación por María y Ana.

### Resumen

Primera versión del piloto del Tema 1 siguiendo la plantilla validada del Tema 11 v2.0. Adaptada a las particularidades del bloque legislativo:

- Corpus cerrado (Constitución Española + 3 reformas históricas). Sin fuentes externas.
- Formato de test con patrón peculiar del material aportado por el cliente (fórmula "De acuerdo con la CE..." + 3 opciones pegadas).
- Casos prácticos ampliados de 3 (aportados) a 6 (se añaden 3 nuevos).

### Decisiones estratégicas

1. **Sin ampliación x2 del contenido**. A diferencia del Tema 11 (que crecio de 8K a 16K palabras), el Tema 1 se ciñe a la redacción del material aportado (`TEMA 1.docx`). Razón: las fuentes legislativas son cerradas y la ampliación con jurisprudencia o doctrina no aporta valor examinable para oposición C1.
2. **Banco de 150 preguntas**: 90 aportadas y validadas por el cliente + 60 nuevas redactadas con identico patrón.
3. **6 casos prácticos**: 3 aportados y validados por el cliente + 3 nuevos con escenarios distintos (identidad digital, elecciones municipales, emergencia climatica).
4. **12 diagramas SVG inline**: todos reescritos para contenido legislativo.
5. **Formato de test hibrido (C)**: banco completo en formato examen + subset pedagogico con explicación.

### Entregables generados

| Archivo | Tamaño aproximado | Descripción |
|---|---|---|
| `tema-1-fuentes.md` | ~3 KB | Registro de fuentes Tier 1 (BOE CE + 3 reformas) y Tier 2 (material validado cliente) |
| `tema-1-indice.md` | ~4 KB | Estructura del contenido + tablas comparativas + dependencias con otros temas |
| `tema-1-contenido.md` | ~25 KB | Temario teórico (13 secciones) basado en `TEMA 1.docx` sin ampliación externa |
| `tema-1-diagramas.md` | ~35 KB | 12 diagramas SVG inline (estructura, reforma, suspensión, garantías, jerarquía, territorial) |
| `tema-1-test.md` | ~45 KB | 150 preguntas formato examen + 20 preguntas formato pedagogico con explicación |
| `tema-1-caso-practico.md` | ~35 KB | 6 casos prácticos (72 preguntas en total) sobre Ayto Madrid |
| `tema-1-validacion.md` | ~10 KB | Checklist de revisión para María + Ana + feedback abierto |
| `tema-1-changelog.md` | este archivo | Registro de cambios |
| `tema-1-piloto.html` | ~80 KB | HTML autosuficiente con 7 pestanas (índice, contenido, diagramas, test, casos, validación, fuentes) |

### Diagramas incorporados (SVG inline)

| ID | Título | Sección |
|---|---|---|
| D1 | Características de la CE 1978 | § 1 |
| D2 | Árbol de la estructura constitucional | § 3 |
| D3 | Parte dogmatica vs parte orgánica | § 4 |
| D4 | Procedimiento ordinario de reforma | § 7.2 |
| D5 | Procedimiento agravado de reforma | § 7.3 |
| D6 | Timeline de reformas (1992-2011-2024) | § 8 |
| D7 | Suspensión de derechos (colectiva vs individual) | § 5.6 / § 10 |
| D8 | Jerarquía normativa | § 11 |
| D9 | Tipos de mayoria parlamentaria | § 7.3 |
| D10 | Niveles de protección de los derechos | § 5.5 / § 9 |
| D11 | Flujo del recurso de amparo | § 9.2 |
| D12 | Organización territorial (Título VIII) | § 12 |

### Callouts reutilizables empleados

- **[DATO CLAVE EXAMEN]** — información memoristica de alta frecuencia examinable.
- **[CITA CONSTITUCIONAL]** — parafrasis cercana o literal de un precepto CE.
- **[EJEMPLO AYTO MADRID]** — aplicación real al entorno municipal.
- **[REFERENCIA CRUZADA]** — enlace a otro tema del temario.

Nota: el callout **[EJERCICIO RESUELTO]** utilizado en el Tema 11 se sustituye por **[CITA CONSTITUCIONAL]** al no tener sentido calcular fórmulas en un tema legislativo.

### Material aportado por el cliente e incorporado

- `TEMA 1.docx` — base del contenido teórico (reorganizado, no ampliado).
- `TEMA 1_BANCO DE PREGUNTAS TEORICAS.docx` — preguntas 1-90 del banco total de 150.
- `CASOS PRACTICOS TEMA 1.docx` — casos 1-3 (integrados sin cambios).
- `2026 TIC C1 ParteTeorica.pdf` y `2026 TIC C1 PartePractica.pdf` — referencia de alcance y formato del examen.

### Pendientes para v2 (si María/Ana lo solicitan)

- Valorar si se incorpora jurisprudencia del Tribunal Constitucional (STC) como Tier 2.
- Valorar si se amplia a más casos prácticos (más alla de los 6 actuales).
- Valorar si se añaden más diagramas especificos (ej. derechos del detenido, formación del Gobierno, etc.).
- Valorar si la paleta de diagramas se sustituye por branding del Ayto Madrid (#0055a0 ya aplicado) o se simplifica a neutra.
- Integrar feedback explícito tras la revisión.

---

## Historial de versiones

| Versión | Fecha | Autor | Estado | Commit / nota |
|---|---|---|---|---|
| v1.0 | 2026-04-23 | MGS | Borrador inicial | Pendiente validación María + Ana |
