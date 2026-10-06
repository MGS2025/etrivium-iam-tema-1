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

- [ ] Las fuentes Tier 1 listadas en `tema-1-fuentes.md` son correctas (BOE CE 1978 + 4 reformas).
- [ ] No se han introducido fuentes doctrinales: el texto fuera de las cajas se ciñe a lo que dice la norma.
- [ ] Cada afirmación del contenido que reproduce texto constitucional esta marcada con `(art. X CE)`.
- [ ] Las cuatro reformas (1992, 2011, 2024 y 2026) están correctamente identificadas con año + artículo afectado.
- [ ] Cada pregunta del banco y de los casos prácticos puede reconducirse a un artículo de la CE o de la norma citada.

## 2. Estructura del contenido

- [ ] El `tema-1-indice.md` refleja fielmente la estructura de `tema-1-contenido.md`.
- [ ] Las 13 secciones del contenido cubren: introducción, datos clave, estructura, parte dogmática/orgánica, Título I completo, síntesis Títulos II-X, reforma, reformas históricas, garantías, suspensión, jerarquía, organización territorial, resumen.
- [ ] Los conceptos memorizables aparecen marcados como `[DATO CLAVE]`.
- [ ] Las citas literales de la CE aparecen como `[CITA NORMATIVA]`.
- [ ] Los ejemplos del Ayuntamiento de Madrid están marcados como `[EJEMPLO DE APLICACIÓN EN EL AYTO]`.
- [ ] Los enlaces a otros temas se marcan como `[RELACIÓN CON OTROS TEMAS]`.

## 3. Rigor jurídico

- [ ] Las fechas de 1978 son correctas: aprobación 31/10, referéndum 6/12, sanción 27/12, publicación BOE 29/12.
- [ ] El número de artículos (169) es correcto.
- [ ] La clasificación de derechos por bloques es correcta:
    - Arts. 14-29: derechos fundamentales y libertades públicas (protección máxima).
    - Arts. 30-38: derechos y deberes (protección media).
    - Arts. 39-52: principios rectores (protección mínima).
- [ ] Las mayorías exigidas para reforma son correctas: 3/5 (ordinaria), 2/3 (agravada), 1/10 (referéndum facultativo).
- [ ] El listado de derechos suspendibles del art. 55.1 es correcto (17, 18.2, 18.3, 19, 20 apartados a y d y 5, 21, 28.2, 37.2; el 17.3 se exceptúa en el estado de excepción).
- [ ] El listado de derechos suspendibles en el art. 55.2 es correcto (17.2, 18.2, 18.3).
- [ ] La reforma de 1992 afectó al art. 13.2 (sufragio UE en elecciones municipales).
- [ ] La reforma de 2011 afectó al art. 135 (estabilidad presupuestaria y prioridad deuda pública).
- [ ] La reforma de 2024 afectó al art. 49 ("personas con discapacidad").
- [ ] La reforma de 2026 afectó al art. 69.3 (senador propio de Formentera).

## 4. Diagramas SVG

- [ ] Los 12 diagramas están presentes en `tema-1-diagramas.md`.
- [ ] Cada diagrama incluye `role="img"` y `aria-label` descriptivo (accesibilidad).
- [ ] Paleta coherente: Ayto Madrid #0055a0 + #d13c3c + #2d8659 + #e89822.
- [ ] Ningún diagrama depende de CDN, fuentes externas ni scripts.
- [ ] Dimensiones adecuadas para HTML + impresión (640-720 px de ancho).
- [ ] El contenido textual de los diagramas es correcto y no contradice el temario (cruzar D4/D5 con sección 7, D7 con sección 5.6, D10 con sección 9).

## 5. Banco de 150 preguntas

- [ ] El enunciado y la respuesta correcta de cada pregunta salen del texto literal del precepto citado (o de una variación leve), y los distractores son variaciones leves inequívocamente falsas.
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

- [ ] Los 3 primeros casos (1-3) son coherentes con el articulado CE.
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
- [ ] Los callouts siguen los 4 tipos establecidos (DATO CLAVE / CITA NORMATIVA / EJEMPLO DE APLICACIÓN EN EL AYTO / RELACIÓN CON OTROS TEMAS).
- [ ] La nomenclatura de artículos es consistente (`(art. X CE)`).
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

- [ ] Las referencias cruzadas al Tema 2 (organización territorial) y a los Temas 25, 32 y 39 (seguridad y protección de la información) son coherentes con el temario oficial.
- [ ] El glosario constitucional utilizado es el mismo que en los demás temas administrativos (1-10).
- [ ] La paleta visual se mantiene respecto al piloto del Tema 11 (Ayto Madrid + colores auxiliares).

---

## Observaciones generales

### Decisiones conscientes que conviene confirmar

1. **No se amplía el contenido teórico x2** (a diferencia del Tema 11).
2. **No se incorpora jurisprudencia del Tribunal Constitucional**: el texto fuera de las cajas se ciñe a lo que dicen la Constitución y sus leyes de desarrollo.
3. **El banco se amplía de 90 a 150 preguntas** siguiendo el mismo patrón.
4. **Se generan 3 casos prácticos nuevos** con escenarios diversos (identidad digital, elecciones municipales, emergencia climática).
5. **Se mantienen los 12 diagramas SVG** propuestos, todos adaptados a contenido legislativo.
6. **El formato de test es híbrido**: banco completo en formato examen (3 opciones pegadas) + subset de 20 preguntas con explicación pedagógica.

### Material descartado conscientemente

- Doctrina académica y manuales comerciales: fuera del alcance.
- Jurisprudencia del TC: retirada en v2.3.

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
