# Tema 1 — Checklist de Validación

> **Título oficial**: La Constitución Española (I): Estructura y contenido. Derechos y deberes fundamentales. Su garantía y suspensión.
> **Versión**: 1.0
> **Fecha**: 2026-04-23
> **Revisoras**: María + Ana

---

## Cómo usar este checklist

Cada ítem se valora con:

- **OK** -> el criterio se cumple sin cambios.
- **REVISAR** -> necesita ajuste o aclaración (indicar que).
- **NO** -> no se cumple o es incorrecto. Justificar brevemente.

Al final hay un **apartado de observaciones generales** para feedback abierto.

---

## 1. Fuentes y trazabilidad

- [ ] Las fuentes Tier 1 listadas en `tema-1-fuentes.md` son correctas (BOE CE 1978 + 3 reformas).
- [ ] No se han introducido fuentes Tier 2 ni doctrinales adicionales (regla del proyecto: ceñirse al material aportado).
- [ ] Cada afirmación del contenido que reproduce texto constitucional esta marcada con `[CE, art. X]`.
- [ ] Las tres reformas (1992, 2011, 2024) están correctamente identificadas con año + artículo afectado.
- [ ] Cada pregunta del banco y de los casos prácticos puede reconducirse a un artículo de la CE o al material aportado por el cliente.

## 2. Estructura del contenido

- [ ] El `tema-1-indice.md` refleja fielmente la estructura de `tema-1-contenido.md`.
- [ ] Las 13 secciones del contenido cubren: introducción, datos clave, estructura, parte dogmática/orgánica, Título I completo, síntesis Títulos II-X, reforma, reformas históricas, garantías, suspensión, jerarquía, organización territorial, resumen.
- [ ] Los conceptos memorizables aparecen marcados como `[DATO CLAVE EXAMEN]`.
- [ ] Las ampliaciones conceptuales que citan literalmente la CE aparecen como `[CITA CONSTITUCIONAL]`.
- [ ] Los ejemplos del Ayuntamiento de Madrid están marcados como `[EJEMPLO AYTO MADRID]`.
- [ ] Los enlaces a otros temas se marcan como `[REFERENCIA CRUZADA]`.

## 3. Rigor jurídico

- [ ] Las fechas de 1978 son correctas: aprobación 31/10, referéndum 6/12, sanción 27/12, publicación BOE 29/12.
- [ ] El número de artículos (169) es correcto.
- [ ] La clasificación de derechos por bloques es correcta:
    - Arts. 14-29: derechos fundamentales y libertades públicas (protección máxima).
    - Arts. 30-38: derechos y deberes (protección media).
    - Arts. 39-52: principios rectores (protección mínima).
- [ ] Las mayorías exigidas para reforma son correctas: 3/5 (ordinaria), 2/3 (agravada), 1/10 (referéndum facultativo).
- [ ] El listado de derechos suspendibles del art. 55.1 es correcto (17, 18.2, 18.3, 19, 20 apartados a y d y 5, 21, 28.2, 37.2).
- [ ] El listado de derechos suspendibles en el art. 55.2 es correcto (17.2, 18.2, 18.3).
- [ ] La reforma de 1992 afectó al art. 13.2 (sufragio UE en elecciones municipales).
- [ ] La reforma de 2011 afectó al art. 135 (estabilidad presupuestaria y prioridad deuda pública).
- [ ] La reforma de 2024 afectó al art. 49 ("personas con discapacidad").

## 4. Diagramas SVG

- [ ] Los 12 diagramas están presentes en `tema-1-diagramas.md`.
- [ ] Cada diagrama incluye `role="img"` y `aria-label` descriptivo (accesibilidad).
- [ ] Paleta coherente: Ayto Madrid #0055a0 + #d13c3c + #2d8659 + #e89822.
- [ ] Ningún diagrama depende de CDN, fuentes externas ni scripts.
- [ ] Dimensiones adecuadas para HTML + impresión (640-720 px de ancho).
- [ ] El contenido textual de los diagramas es correcto y no contradice el temario (cruzar D4/D5 con sección 7, D7 con sección 5.6, D10 con sección 9).

## 5. Banco de 150 preguntas

- [ ] Las 90 primeras preguntas son idénticas al banco validado aportado por el cliente.
- [ ] Las 60 nuevas (91-150) siguen el mismo patrón estilístico:
    - Fórmula inicial "De acuerdo con la CE / De conformidad con / Según...".
    - 3 opciones a/b/c.
    - Vocabulario constitucional literal.
    - Agrupación por bloques temáticos.
- [ ] Cada pregunta tiene una única respuesta correcta verificable en el texto constitucional.
- [ ] La plantilla de respuestas al final agrupa correctamente las 150 respuestas.
- [ ] No hay preguntas ambiguas (ej. dos respuestas plausibles).
- [ ] La sección pedagógica de 20 preguntas incluye explicación y referencia al artículo.

## 6. Casos prácticos

- [ ] Los 3 primeros casos (1-3) son idénticos a los del material aportado por el cliente.
- [ ] Los 3 nuevos casos (4-6) mantienen escenario del Ayto Madrid.
- [ ] Cada caso tiene plantilla de respuestas al final.
- [ ] Las preguntas de los 3 casos nuevos son coherentes con el articulado CE.
- [ ] El total de preguntas de casos prácticos (72) proporciona suficiente material de simulacro.
- [ ] Los casos cubren temáticas diversas: plataforma digital (1-3), identidad digital y videovigilancia (4), elecciones municipales (5), emergencia climática y estados de crisis (6).

## 7. Nivel y adecuación al C1

- [ ] El nivel de profundidad es adecuado para oposición C1 (Técnico Auxiliar TIC).
- [ ] No hay sobrecarga doctrinal ni detalles de Derecho Constitucional avanzado irrelevantes.
- [ ] Se prioriza memorización de fechas, artículos, mayorías y clasificaciones.
- [ ] Las preguntas de nivel alto (66-90) requieren comprensión pero siempre con fundamento literal en la CE.
- [ ] Los ejemplos del Ayto Madrid son realistas y aportan valor aplicativo.

## 8. Estilo y forma

- [ ] Los ficheros `.md` usan encabezados coherentes (H1, H2, H3, etc.).
- [ ] Las tablas están correctamente formateadas.
- [ ] Los callouts siguen los 4 tipos establecidos (DATO CLAVE / CITA CONSTITUCIONAL / EJEMPLO AYTO MADRID / REFERENCIA CRUZADA).
- [ ] La nomenclatura de artículos es consistente (`[CE, art. X]`).
- [ ] Las referencias a otros ficheros del tema son correctas (links relativos).
- [ ] Se respeta el castellano sin errores ortográficos manifiestos.

## 9. Entregables HTML

- [ ] `tema-1-piloto.html` es autosuficiente (sin CDN, sin scripts externos, sin iframes).
- [ ] Funciona offline al abrirlo directamente en el navegador.
- [ ] Incluye las siguientes pestañas:
    - Índice.
    - Contenido.
    - Diagramas (los 12 SVG).
    - Test (motor de corrección automática + penalización 1/3).
    - Casos prácticos (los 6).
    - Validación (este checklist).
    - Fuentes.
- [ ] El motor de test penaliza correctamente (1/3 por fallo).
- [ ] El HTML es imprimible a PDF con estilo legible.
- [ ] El branding visual corresponde al Ayuntamiento de Madrid (#0055a0) con logo o escudo centrado.

## 10. Consistencia inter-temas

- [ ] Las referencias cruzadas al Tema 2 (organización territorial), Tema 3 (Corona + Cortes) y Tema 4 (Poder Judicial + TC) son coherentes.
- [ ] El glosario constitucional utilizado es el mismo que en los demás temas administrativos (1-10).
- [ ] La paleta visual se mantiene respecto al piloto del Tema 11 (Ayto Madrid + colores auxiliares).

---

## Observaciones generales

### Material aportado que se ha incorporado literalmente

1. Las 90 preguntas del `TEMA 1_BANCO DE PREGUNTAS TEORICAS.docx` se mantienen tal cual (Tier 2 validado).
2. Los 3 casos prácticos del `CASOS PRACTICOS TEMA 1.docx` se mantienen tal cual (Tier 2 validado).
3. La redacción del temario base `TEMA 1.docx` se ha reorganizado y completado con llamadas a artículos, pero sin ampliar con material externo.

### Decisiones conscientes que conviene confirmar

1. **No se amplía el contenido teórico x2** (a diferencia del Tema 11). Decisión de Joan: "en este caso debes ceñirte a lo que tenemos, sin buscar más".
2. **No se incorpora jurisprudencia del Tribunal Constitucional**. Decisión derivada de la anterior (ninguna STC aparece en el material aportado).
3. **El banco se amplía de 90 a 150 preguntas** siguiendo el patrón del material validado. Decisión de Joan.
4. **Se generan 3 casos prácticos nuevos** con escenarios diversos (identidad digital, elecciones municipales, emergencia climática). Decisión de Joan.
5. **Se mantienen los 12 diagramas SVG** propuestos, todos adaptados a contenido legislativo.
6. **El formato de test es híbrido**: banco completo en formato examen (3 opciones pegadas) + subset de 20 preguntas con explicación pedagógica. Decisión de Joan.

### Material descartado conscientemente

- Doctrina académica y manuales comerciales: fuera del alcance por decisión del cliente.
- Jurisprudencia del TC: no se incorpora v1; puede añadirse en v2 si María/Ana lo solicitan.
- Material aportado en PDF del pliego (`2026 TIC C1 ParteTeorica.pdf` y `2026 TIC C1 PartePractica.pdf`): actúan como referencia de alcance y formato, no como fuente de contenido teórico.

---

## Feedback de María

*Espacio reservado — rellenar tras revisión.*

| Ítem checklist | Estado | Observación |
|---|---|---|
|  |  |  |
|  |  |  |
|  |  |  |

---

## Feedback de Ana

*Espacio reservado — rellenar tras revisión.*

| Ítem checklist | Estado | Observación |
|---|---|---|
|  |  |  |
|  |  |  |
|  |  |  |

---

## Decisión de cierre

- [ ] Aprobado sin cambios.
- [ ] Aprobado con cambios menores (listarlos).
- [ ] Requiere v2 (listar cambios sustanciales).

**Firmas**:

- María: _______________________________ Fecha: _____________
- Ana: _______________________________ Fecha: _____________
