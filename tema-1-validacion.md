# Tema 1 — Checklist de Validacion

> **Titulo oficial**: La Constitucion Espanola (I): Estructura y contenido. Derechos y deberes fundamentales. Su garantia y suspension.
> **Version**: 1.0
> **Fecha**: 2026-04-23
> **Revisoras**: Maria + Ana

---

## Como usar este checklist

Cada item se valora con:

- **OK** -> el criterio se cumple sin cambios.
- **REVISAR** -> necesita ajuste o aclaracion (indicar que).
- **NO** -> no se cumple o es incorrecto. Justificar brevemente.

Al final hay un **apartado de observaciones generales** para feedback abierto.

---

## 1. Fuentes y trazabilidad

- [ ] Las fuentes Tier 1 listadas en `tema-1-fuentes.md` son correctas (BOE CE 1978 + 3 reformas).
- [ ] No se han introducido fuentes Tier 2 ni doctrinales adicionales (regla del proyecto: ceñirse al material aportado).
- [ ] Cada afirmacion del contenido que reproduce texto constitucional esta marcada con `[CE, art. X]`.
- [ ] Las tres reformas (1992, 2011, 2024) estan correctamente identificadas con ano + articulo afectado.
- [ ] Cada pregunta del banco y de los casos practicos puede reconducirse a un articulo de la CE o al material aportado por el cliente.

## 2. Estructura del contenido

- [ ] El `tema-1-indice.md` refleja fielmente la estructura de `tema-1-contenido.md`.
- [ ] Las 13 secciones del contenido cubren: introduccion, datos clave, estructura, parte dogmatica/organica, Titulo I completo, sintesis Titulos II-X, reforma, reformas historicas, garantias, suspension, jerarquia, organizacion territorial, resumen.
- [ ] Los conceptos memorizables aparecen marcados como `[DATO CLAVE EXAMEN]`.
- [ ] Las ampliaciones conceptuales que citan literalmente la CE aparecen como `[CITA CONSTITUCIONAL]`.
- [ ] Los ejemplos del Ayuntamiento de Madrid estan marcados como `[EJEMPLO AYTO MADRID]`.
- [ ] Los enlaces a otros temas se marcan como `[REFERENCIA CRUZADA]`.

## 3. Rigor juridico

- [ ] Las fechas de 1978 son correctas: aprobacion 31/10, referendum 6/12, sancion 27/12, publicacion BOE 29/12.
- [ ] El numero de articulos (169) es correcto.
- [ ] La clasificacion de derechos por bloques es correcta:
    - Arts. 14-29: derechos fundamentales y libertades publicas (proteccion maxima).
    - Arts. 30-38: derechos y deberes (proteccion media).
    - Arts. 39-52: principios rectores (proteccion minima).
- [ ] Las mayorias exigidas para reforma son correctas: 3/5 (ordinaria), 2/3 (agravada), 1/10 (referendum facultativo).
- [ ] El listado de derechos suspendibles del art. 55.1 es correcto (17, 18.2, 18.3, 19, 20 apartados a y d y 5, 21, 28.2, 37.2).
- [ ] El listado de derechos suspendibles en el art. 55.2 es correcto (17.2, 18.2, 18.3).
- [ ] La reforma de 1992 afecto al art. 13.2 (sufragio UE en elecciones municipales).
- [ ] La reforma de 2011 afecto al art. 135 (estabilidad presupuestaria y prioridad deuda publica).
- [ ] La reforma de 2024 afecto al art. 49 ("personas con discapacidad").

## 4. Diagramas SVG

- [ ] Los 12 diagramas estan presentes en `tema-1-diagramas.md`.
- [ ] Cada diagrama incluye `role="img"` y `aria-label` descriptivo (accesibilidad).
- [ ] Paleta coherente: Ayto Madrid #0055a0 + #d13c3c + #2d8659 + #e89822.
- [ ] Ningun diagrama depende de CDN, fuentes externas ni scripts.
- [ ] Dimensiones adecuadas para HTML + impresion (640-720 px de ancho).
- [ ] El contenido textual de los diagramas es correcto y no contradice el temario (cruzar D4/D5 con seccion 7, D7 con seccion 5.6, D10 con seccion 9).

## 5. Banco de 150 preguntas

- [ ] Las 90 primeras preguntas son identicas al banco validado aportado por el cliente.
- [ ] Las 60 nuevas (91-150) siguen el mismo patron estilistico:
    - Formula inicial "De acuerdo con la CE / De conformidad con / Segun...".
    - 3 opciones a/b/c.
    - Vocabulario constitucional literal.
    - Agrupacion por bloques tematicos.
- [ ] Cada pregunta tiene una unica respuesta correcta verificable en el texto constitucional.
- [ ] La plantilla de respuestas al final agrupa correctamente las 150 respuestas.
- [ ] No hay preguntas ambiguas (ej. dos respuestas plausibles).
- [ ] La seccion pedagogica de 20 preguntas incluye explicacion y referencia al articulo.

## 6. Casos practicos

- [ ] Los 3 primeros casos (1-3) son identicos a los del material aportado por el cliente.
- [ ] Los 3 nuevos casos (4-6) mantienen escenario del Ayto Madrid.
- [ ] Cada caso tiene plantilla de respuestas al final.
- [ ] Las preguntas de los 3 casos nuevos son coherentes con el articulado CE.
- [ ] El total de preguntas de casos practicos (72) proporciona suficiente material de simulacro.
- [ ] Los casos cubren tematicas diversas: plataforma digital (1-3), identidad digital y videovigilancia (4), elecciones municipales (5), emergencia climatica y estados de crisis (6).

## 7. Nivel y adecuacion al C1

- [ ] El nivel de profundidad es adecuado para oposicion C1 (Tecnico Auxiliar TIC).
- [ ] No hay sobrecarga doctrinal ni detalles de Derecho Constitucional avanzado irrelevantes.
- [ ] Se prioriza memorizacion de fechas, articulos, mayorias y clasificaciones.
- [ ] Las preguntas de nivel alto (66-90) requieren comprension pero siempre con fundamento literal en la CE.
- [ ] Los ejemplos del Ayto Madrid son realistas y aportan valor aplicativo.

## 8. Estilo y forma

- [ ] Los ficheros `.md` usan encabezados coherentes (H1, H2, H3, etc.).
- [ ] Las tablas estan correctamente formateadas.
- [ ] Los callouts siguen los 4 tipos establecidos (DATO CLAVE / CITA CONSTITUCIONAL / EJEMPLO AYTO MADRID / REFERENCIA CRUZADA).
- [ ] La nomenclatura de articulos es consistente (`[CE, art. X]`).
- [ ] Las referencias a otros ficheros del tema son correctas (links relativos).
- [ ] Se respeta el castellano sin errores ortograficos manifiestos.

## 9. Entregables HTML

- [ ] `tema-1-piloto.html` es autosuficiente (sin CDN, sin scripts externos, sin iframes).
- [ ] Funciona offline al abrirlo directamente en el navegador.
- [ ] Incluye las siguientes pestanas:
    - Indice.
    - Contenido.
    - Diagramas (los 12 SVG).
    - Test (motor de correccion automatica + penalizacion 1/3).
    - Casos practicos (los 6).
    - Validacion (este checklist).
    - Fuentes.
- [ ] El motor de test penaliza correctamente (1/3 por fallo).
- [ ] El HTML es imprimible a PDF con estilo legible.
- [ ] El branding visual corresponde al Ayuntamiento de Madrid (#0055a0) con logo o escudo centrado.

## 10. Consistencia inter-temas

- [ ] Las referencias cruzadas al Tema 2 (organizacion territorial), Tema 3 (Corona + Cortes) y Tema 4 (Poder Judicial + TC) son coherentes.
- [ ] El glosario constitucional utilizado es el mismo que en los demas temas administrativos (1-10).
- [ ] La paleta visual se mantiene respecto al piloto del Tema 11 (Ayto Madrid + colores auxiliares).

---

## Observaciones generales

### Material aportado que se ha incorporado literalmente

1. Las 90 preguntas del `TEMA 1_BANCO DE PREGUNTAS TEORICAS.docx` se mantienen tal cual (Tier 2 validado).
2. Los 3 casos practicos del `CASOS PRACTICOS TEMA 1.docx` se mantienen tal cual (Tier 2 validado).
3. La redaccion del temario base `TEMA 1.docx` se ha reorganizado y completado con llamadas a articulos, pero sin ampliar con material externo.

### Decisiones conscientes que conviene confirmar

1. **No se amplia el contenido teorico x2** (a diferencia del Tema 11). Decision de Joan: "en este caso debes cenirte a lo que tenemos, sin buscar mas".
2. **No se incorpora jurisprudencia del Tribunal Constitucional**. Decision derivada de la anterior (ninguna STC aparece en el material aportado).
3. **El banco se ampliar de 90 a 150 preguntas** siguiendo el patron del material validado. Decision de Joan.
4. **Se generan 3 casos practicos nuevos** con escenarios diversos (identidad digital, elecciones municipales, emergencia climatica). Decision de Joan.
5. **Se mantienen los 12 diagramas SVG** propuestos, todos adaptados a contenido legislativo.
6. **El formato de test es hibrido**: banco completo en formato examen (3 opciones pegadas) + subset de 20 preguntas con explicacion pedagogica. Decision de Joan.

### Material descartado conscientemente

- Doctrina academica y manuales comerciales: fuera del alcance por decision del cliente.
- Jurisprudencia del TC: no se incorpora v1; puede anadirse en v2 si Maria/Ana lo solicitan.
- Material aportado en PDF del pliego (`2026 TIC C1 ParteTeorica.pdf` y `2026 TIC C1 PartePractica.pdf`): actuan como referencia de alcance y formato, no como fuente de contenido teorico.

---

## Feedback de Maria

*Espacio reservado — rellenar tras revision.*

| Item checklist | Estado | Observacion |
|---|---|---|
|  |  |  |
|  |  |  |
|  |  |  |

---

## Feedback de Ana

*Espacio reservado — rellenar tras revision.*

| Item checklist | Estado | Observacion |
|---|---|---|
|  |  |  |
|  |  |  |
|  |  |  |

---

## Decision de cierre

- [ ] Aprobado sin cambios.
- [ ] Aprobado con cambios menores (listarlos).
- [ ] Requiere v2 (listar cambios sustanciales).

**Firmas**:

- Maria: _______________________________ Fecha: _____________
- Ana: _______________________________ Fecha: _____________
