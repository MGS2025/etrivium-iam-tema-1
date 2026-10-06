# Tema 1 — Catálogo de Diagramas

> **Título oficial**: La Constitución Española (I): Estructura y contenido. Derechos y deberes fundamentales. Su garantía y suspensión.
>
> **Versión**: 1.0
> **Fecha**: 2026-04-23
> **Formato**: SVG inline (zero-dependencias, escalable, imprimible)
> **Paleta**: Ayuntamiento de Madrid #0055a0 (primario) + #d13c3c (alertas) + #2d8659 (ventajas) + #e89822 (callouts)

---

## Índice de diagramas

| ID  | Título                                               | Sección | Tipo          | Formato |
|-----|-------------------------------------------------------|---------|---------------|---------|
| D1  | Características de la CE 1978                         | § 1     | Mapa conceptual | 680×360 |
| D2  | Árbol de la estructura constitucional                 | § 3     | Árbol         | 720×420 |
| D3  | Parte dogmática vs parte orgánica                     | § 4     | Comparativa   | 680×360 |
| D4  | Procedimiento ordinario de reforma (art. 167)         | § 7.2   | Flowchart     | 720×420 |
| D5  | Procedimiento agravado de reforma (art. 168)          | § 7.3   | Flowchart     | 720×440 |
| D6  | Timeline de reformas (1992-2011-2024-2026)            | § 8     | Timeline      | 720×300 |
| D7  | Suspensión de derechos (art. 55) — colectiva vs individual | § 5.6 / § 10 | Tabla comparativa | 700×400 |
| D8  | Jerarquía normativa                                   | § 11    | Pirámide      | 640×380 |
| D9  | Tipos de mayoría parlamentaria                        | § 7.3   | Comparativa barras | 680×340 |
| D10 | Niveles de protección de los derechos (art. 53)       | § 5.5 / § 9 | Pirámide      | 680×380 |
| D11 | Flujo del recurso de amparo                           | § 9.2   | Flowchart     | 700×400 |
| D12 | Organización territorial del Estado (Título VIII)     | § 12    | Árbol horizontal | 720×360 |

---

## D1 · Características de la Constitución Española

**Sección**: § 1 — Introducción y características
**Propósito**: Sintetizar las características definitorias de la CE 1978 en un mapa conceptual.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 360" role="img" aria-label="Características de la Constitución Española de 1978">
  <style>
    .d1-center{fill:#0055a0;stroke:#003d73;stroke-width:2}
    .d1-node{fill:#ffffff;stroke:#0055a0;stroke-width:1.5}
    .d1-title{font:700 14px system-ui,sans-serif;fill:#ffffff;text-anchor:middle}
    .d1-label{font:600 12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .d1-link{stroke:#0055a0;stroke-width:1;fill:none}
    .d1-sub{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <line x1="340" y1="180" x2="130" y2="60" class="d1-link"/>
  <line x1="340" y1="180" x2="340" y2="50" class="d1-link"/>
  <line x1="340" y1="180" x2="550" y2="60" class="d1-link"/>
  <line x1="340" y1="180" x2="80" y2="180" class="d1-link"/>
  <line x1="340" y1="180" x2="600" y2="180" class="d1-link"/>
  <line x1="340" y1="180" x2="130" y2="300" class="d1-link"/>
  <line x1="340" y1="180" x2="340" y2="310" class="d1-link"/>
  <line x1="340" y1="180" x2="550" y2="300" class="d1-link"/>
  <ellipse cx="340" cy="180" rx="75" ry="40" class="d1-center"/>
  <text x="340" y="175" class="d1-title">CE 1978</text>
  <text x="340" y="195" class="d1-title" style="font-weight:400;font-size:11px">169 arts. + 10 Tít.</text>
  <rect x="60" y="40" width="140" height="40" rx="6" class="d1-node"/>
  <text x="130" y="58" class="d1-label">Pactada</text>
  <text x="130" y="72" class="d1-sub">consenso político</text>
  <rect x="270" y="20" width="140" height="40" rx="6" class="d1-node"/>
  <text x="340" y="38" class="d1-label">Rígida</text>
  <text x="340" y="52" class="d1-sub">arts. 167 y 168</text>
  <rect x="480" y="40" width="140" height="40" rx="6" class="d1-node"/>
  <text x="550" y="58" class="d1-label">Escrita y codificada</text>
  <text x="550" y="72" class="d1-sub">un solo texto</text>
  <rect x="10" y="160" width="140" height="40" rx="6" class="d1-node"/>
  <text x="80" y="178" class="d1-label">Extensa</text>
  <text x="80" y="192" class="d1-sub">169 artículos</text>
  <rect x="530" y="160" width="140" height="40" rx="6" class="d1-node"/>
  <text x="600" y="178" class="d1-label">Aplicación directa</text>
  <text x="600" y="192" class="d1-sub">e inmediata</text>
  <rect x="60" y="280" width="140" height="40" rx="6" class="d1-node"/>
  <text x="130" y="298" class="d1-label">Derivada</text>
  <text x="130" y="312" class="d1-sub">influencias externas</text>
  <rect x="270" y="290" width="140" height="40" rx="6" class="d1-node"/>
  <text x="340" y="308" class="d1-label">Origen popular</text>
  <text x="340" y="322" class="d1-sub">referéndum 1978</text>
  <rect x="480" y="280" width="140" height="40" rx="6" class="d1-node"/>
  <text x="550" y="298" class="d1-label">Ideológica</text>
  <text x="550" y="312" class="d1-sub">valores superiores art.1</text>
</svg>
```

---

## D2 · Árbol de la estructura constitucional

**Sección**: § 3 — Estructura del texto
**Propósito**: Visualizar la estructura completa de la CE: Preámbulo + Preliminar + 10 Títulos + Disposiciones.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 420" role="img" aria-label="Árbol de la estructura de la Constitución Española">
  <style>
    .d2-root{fill:#0055a0;stroke:#003d73;stroke-width:2}
    .d2-dogm{fill:#e89822;stroke:#a66410;stroke-width:1}
    .d2-org{fill:#2d8659;stroke:#1d5d3e;stroke-width:1}
    .d2-disp{fill:#6b6b6b;stroke:#3b3b3b;stroke-width:1}
    .d2-title{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d2-label{font:600 11px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d2-range{font:10px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d2-link{stroke:#999;stroke-width:1;fill:none}
    .d2-legend{font:11px system-ui,sans-serif;fill:#333}
  </style>
  <rect x="280" y="15" width="160" height="40" rx="6" class="d2-root"/>
  <text x="360" y="32" class="d2-title">CE 1978</text>
  <text x="360" y="48" class="d2-range">169 art. + Preámbulo</text>
  <line x1="360" y1="55" x2="80" y2="95" class="d2-link"/>
  <line x1="360" y1="55" x2="210" y2="95" class="d2-link"/>
  <line x1="360" y1="55" x2="510" y2="95" class="d2-link"/>
  <line x1="360" y1="55" x2="640" y2="95" class="d2-link"/>
  <rect x="20" y="90" width="120" height="40" rx="4" class="d2-dogm"/>
  <text x="80" y="106" class="d2-label">Preámbulo</text>
  <text x="80" y="122" class="d2-range">interpretativo</text>
  <rect x="150" y="90" width="120" height="40" rx="4" class="d2-dogm"/>
  <text x="210" y="106" class="d2-label">Tít. Preliminar</text>
  <text x="210" y="122" class="d2-range">arts. 1-9</text>
  <rect x="450" y="90" width="120" height="40" rx="4" class="d2-dogm"/>
  <text x="510" y="106" class="d2-label">Título I</text>
  <text x="510" y="122" class="d2-range">arts. 10-55</text>
  <rect x="580" y="90" width="120" height="40" rx="4" class="d2-disp"/>
  <text x="640" y="106" class="d2-label">DDAA/DDTT</text>
  <text x="640" y="122" class="d2-range">4+9+1+1</text>
  <text x="40" y="155" class="d2-legend" style="font-weight:700">Parte orgánica — Títulos II a X</text>
  <rect x="20" y="165" width="80" height="34" rx="4" class="d2-org"/>
  <text x="60" y="180" class="d2-label">Tít. II</text>
  <text x="60" y="193" class="d2-range">56-65 Corona</text>
  <rect x="110" y="165" width="80" height="34" rx="4" class="d2-org"/>
  <text x="150" y="180" class="d2-label">Tít. III</text>
  <text x="150" y="193" class="d2-range">66-96 Cortes</text>
  <rect x="200" y="165" width="80" height="34" rx="4" class="d2-org"/>
  <text x="240" y="180" class="d2-label">Tít. IV</text>
  <text x="240" y="193" class="d2-range">97-107 Gob.</text>
  <rect x="290" y="165" width="80" height="34" rx="4" class="d2-org"/>
  <text x="330" y="180" class="d2-label">Tít. V</text>
  <text x="330" y="193" class="d2-range">108-116 Rel.</text>
  <rect x="380" y="165" width="80" height="34" rx="4" class="d2-org"/>
  <text x="420" y="180" class="d2-label">Tít. VI</text>
  <text x="420" y="193" class="d2-range">117-127 Judic.</text>
  <rect x="470" y="165" width="80" height="34" rx="4" class="d2-org"/>
  <text x="510" y="180" class="d2-label">Tít. VII</text>
  <text x="510" y="193" class="d2-range">128-136 Econ.</text>
  <rect x="560" y="165" width="80" height="34" rx="4" class="d2-org"/>
  <text x="600" y="180" class="d2-label">Tít. VIII</text>
  <text x="600" y="193" class="d2-range">137-158 Terr.</text>
  <rect x="110" y="210" width="80" height="34" rx="4" class="d2-org"/>
  <text x="150" y="225" class="d2-label">Tít. IX</text>
  <text x="150" y="238" class="d2-range">159-165 TC</text>
  <rect x="200" y="210" width="80" height="34" rx="4" class="d2-org"/>
  <text x="240" y="225" class="d2-label">Tít. X</text>
  <text x="240" y="238" class="d2-range">166-169 Ref.</text>
  <text x="40" y="280" class="d2-legend" style="font-weight:700">Título I — Capítulos</text>
  <rect x="20" y="290" width="130" height="40" rx="4" class="d2-dogm"/>
  <text x="85" y="306" class="d2-label">Cap. I</text>
  <text x="85" y="322" class="d2-range">arts. 11-13 Españoles/extr.</text>
  <rect x="160" y="290" width="130" height="40" rx="4" class="d2-dogm"/>
  <text x="225" y="306" class="d2-label">Cap. II</text>
  <text x="225" y="322" class="d2-range">arts. 14-38 Der. y lib.</text>
  <rect x="300" y="290" width="130" height="40" rx="4" class="d2-dogm"/>
  <text x="365" y="306" class="d2-label">Cap. III</text>
  <text x="365" y="322" class="d2-range">arts. 39-52 Principios</text>
  <rect x="440" y="290" width="130" height="40" rx="4" class="d2-dogm"/>
  <text x="505" y="306" class="d2-label">Cap. IV</text>
  <text x="505" y="322" class="d2-range">arts. 53-54 Garantías</text>
  <rect x="580" y="290" width="120" height="40" rx="4" class="d2-dogm"/>
  <text x="640" y="306" class="d2-label">Cap. V</text>
  <text x="640" y="322" class="d2-range">art. 55 Suspensión</text>
  <rect x="20" y="350" width="120" height="20" rx="3" class="d2-dogm"/>
  <text x="150" y="364" class="d2-legend">Parte dogmática</text>
  <rect x="260" y="350" width="120" height="20" rx="3" class="d2-org"/>
  <text x="390" y="364" class="d2-legend">Parte orgánica</text>
  <rect x="500" y="350" width="120" height="20" rx="3" class="d2-disp"/>
  <text x="630" y="364" class="d2-legend">Disposiciones</text>
</svg>
```

---

## D3 · Parte dogmática vs parte orgánica

**Sección**: § 4
**Propósito**: Comparar ambos bloques en forma de tabla dual.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 360" role="img" aria-label="Parte dogmática vs Parte orgánica de la CE">
  <style>
    .d3-dogm{fill:#e89822}
    .d3-org{fill:#2d8659}
    .d3-box{fill:#fff;stroke-width:1.5}
    .d3-head{font:700 16px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d3-sub{font:600 12px system-ui,sans-serif;fill:#1a1a1a}
    .d3-item{font:12px system-ui,sans-serif;fill:#333}
  </style>
  <rect x="30" y="20" width="300" height="36" rx="6" class="d3-dogm"/>
  <text x="180" y="44" class="d3-head">PARTE DOGMÁTICA</text>
  <rect x="350" y="20" width="300" height="36" rx="6" class="d3-org"/>
  <text x="500" y="44" class="d3-head">PARTE ORGÁNICA</text>
  <rect x="30" y="70" width="300" height="260" rx="6" class="d3-box" style="stroke:#e89822"/>
  <text x="46" y="95" class="d3-sub">Títulos que la integran</text>
  <text x="46" y="115" class="d3-ítem">• Título Preliminar (arts. 1-9)</text>
  <text x="46" y="133" class="d3-ítem">• Título I (arts. 10-55)</text>
  <text x="46" y="165" class="d3-sub">Contenido</text>
  <text x="46" y="183" class="d3-ítem">• Valores superiores (art. 1.1)</text>
  <text x="46" y="199" class="d3-ítem">• Soberanía nacional (art. 1.2)</text>
  <text x="46" y="215" class="d3-ítem">• Forma política (art. 1.3)</text>
  <text x="46" y="231" class="d3-ítem">• Derechos fundamentales</text>
  <text x="46" y="247" class="d3-ítem">• Garantías (art. 53)</text>
  <text x="46" y="263" class="d3-ítem">• Suspensión (art. 55)</text>
  <text x="46" y="295" class="d3-sub">Foco</text>
  <text x="46" y="313" class="d3-ítem">Persona · Valores · Derechos</text>
  <rect x="350" y="70" width="300" height="260" rx="6" class="d3-box" style="stroke:#2d8659"/>
  <text x="366" y="95" class="d3-sub">Títulos que la integran</text>
  <text x="366" y="115" class="d3-ítem">• Títulos II a X (arts. 56-169)</text>
  <text x="366" y="147" class="d3-sub">Contenido</text>
  <text x="366" y="165" class="d3-ítem">• Corona (II)</text>
  <text x="366" y="181" class="d3-ítem">• Cortes Generales (III)</text>
  <text x="366" y="197" class="d3-ítem">• Gobierno (IV) y relaciones (V)</text>
  <text x="366" y="213" class="d3-ítem">• Poder Judicial (VI)</text>
  <text x="366" y="229" class="d3-ítem">• Economía y Hacienda (VII)</text>
  <text x="366" y="245" class="d3-ítem">• Organización territorial (VIII)</text>
  <text x="366" y="261" class="d3-ítem">• Tribunal Constitucional (IX)</text>
  <text x="366" y="277" class="d3-ítem">• Reforma constitucional (X)</text>
  <text x="366" y="299" class="d3-sub">Foco</text>
  <text x="366" y="317" class="d3-ítem" style="font-weight:600">Estado · Poderes · Instituciones</text>
</svg>
```

---

## D4 · Procedimiento ordinario de reforma (art. 167)

**Sección**: § 7.2
**Propósito**: Flujo paso a paso del procedimiento ordinario de reforma constitucional.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 420" role="img" aria-label="Flujo del procedimiento ordinario de reforma constitucional">
  <style>
    .d4-box{fill:#0055a0;stroke:#003d73;stroke-width:1.5}
    .d4-alt{fill:#e89822;stroke:#a66410;stroke-width:1.5}
    .d4-ok{fill:#2d8659;stroke:#1d5d3e;stroke-width:1.5}
    .d4-ref{fill:#d13c3c;stroke:#8a2828;stroke-width:1.5}
    .d4-title{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d4-sub{font:11px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d4-arrow{stroke:#333;stroke-width:2;fill:none;marker-end:url(#d4-arrow)}
    .d4-label{font:11px system-ui,sans-serif;fill:#333;text-anchor:middle}
  </style>
  <defs>
    <marker id="d4-arrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#333"/>
    </marker>
  </defs>
  <rect x="260" y="20" width="200" height="50" rx="8" class="d4-box"/>
  <text x="360" y="42" class="d4-title">1. INICIATIVA</text>
  <text x="360" y="58" class="d4-sub">Gob · Cong · Sen · CCAA</text>
  <line x1="360" y1="70" x2="360" y2="100" class="d4-arrow"/>
  <rect x="230" y="100" width="260" height="50" rx="8" class="d4-box"/>
  <text x="360" y="122" class="d4-title">2. APROBACIÓN: 3/5 de CADA Cámara</text>
  <text x="360" y="138" class="d4-sub">Congreso + Senado</text>
  <line x1="360" y1="150" x2="360" y2="180" class="d4-arrow"/>
  <line x1="230" y1="125" x2="115" y2="180" class="d4-arrow"/>
  <rect x="230" y="180" width="260" height="50" rx="8" class="d4-ok"/>
  <text x="360" y="202" class="d4-title">3a. ACUERDO -> APROBADO</text>
  <text x="360" y="218" class="d4-sub">texto final</text>
  <rect x="15" y="180" width="200" height="60" rx="8" class="d4-alt"/>
  <text x="115" y="200" class="d4-title">3b. SIN ACUERDO</text>
  <text x="115" y="216" class="d4-sub">Comisión Mixta paritaria</text>
  <text x="115" y="232" class="d4-sub">nueva votación en ambas Cámaras</text>
  <line x1="115" y1="240" x2="115" y2="270" class="d4-arrow"/>
  <rect x="15" y="270" width="200" height="60" rx="8" class="d4-alt"/>
  <text x="115" y="290" class="d4-title">4. FALLBACK</text>
  <text x="115" y="308" class="d4-sub">Senado: mayoría absoluta</text>
  <text x="115" y="323" class="d4-sub">Congreso: 2/3 del pleno</text>
  <line x1="360" y1="230" x2="360" y2="270" class="d4-arrow"/>
  <rect x="260" y="270" width="200" height="50" rx="8" class="d4-ref"/>
  <text x="360" y="292" class="d4-title">5. REFERÉNDUM</text>
  <text x="360" y="308" class="d4-sub">FACULTATIVO (1/10 parte)</text>
  <line x1="360" y1="320" x2="360" y2="360" class="d4-arrow"/>
  <rect x="260" y="360" width="200" height="50" rx="8" class="d4-ok"/>
  <text x="360" y="382" class="d4-title">ENTRADA EN VIGOR</text>
  <text x="360" y="398" class="d4-sub">publicación en BOE</text>
  <text x="570" y="32" class="d4-label" style="font-weight:700;fill:#d13c3c">[CE, art. 167]</text>
  <text x="570" y="52" class="d4-label">Para reformas que</text>
  <text x="570" y="68" class="d4-label">NO afectan al 168</text>
</svg>
```

---

## D5 · Procedimiento agravado de reforma (art. 168)

**Sección**: § 7.3
**Propósito**: Flujo del procedimiento agravado: revisión total o afectación de Preliminar, 15-29 o Título II.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 470" role="img" aria-label="Flujo del procedimiento agravado de reforma constitucional">
  <style>
    .d5-box{fill:#d13c3c;stroke:#8a2828;stroke-width:1.5}
    .d5-step{fill:#0055a0;stroke:#003d73;stroke-width:1.5}
    .d5-ok{fill:#2d8659;stroke:#1d5d3e;stroke-width:1.5}
    .d5-title{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d5-sub{font:11px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d5-label{font:11px system-ui,sans-serif;fill:#333;text-anchor:middle}
    .d5-arrow{stroke:#333;stroke-width:2;fill:none;marker-end:url(#d5-arrow)}
    .d5-note{font:italic 10px system-ui,sans-serif;fill:#8a2828;text-anchor:middle}
  </style>
  <defs>
    <marker id="d5-arrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#333"/>
    </marker>
  </defs>
  <rect x="160" y="10" width="400" height="56" rx="8" class="d5-box"/>
  <text x="360" y="32" class="d5-title">SUPUESTO DE ART. 168</text>
  <text x="360" y="48" class="d5-sub">Revisión TOTAL · o parcial que afecte a:</text>
  <text x="360" y="62" class="d5-sub">Título Preliminar · Cap. II Sec. 1.ª Título I (15-29) · Título II</text>
  <line x1="360" y1="66" x2="360" y2="90" class="d5-arrow"/>
  <rect x="240" y="90" width="240" height="50" rx="8" class="d5-step"/>
  <text x="360" y="112" class="d5-title">1. APROBACIÓN DEL PRINCIPIO</text>
  <text x="360" y="128" class="d5-sub">2/3 de CADA Cámara</text>
  <line x1="360" y1="140" x2="360" y2="170" class="d5-arrow"/>
  <rect x="240" y="170" width="240" height="50" rx="8" class="d5-step"/>
  <text x="360" y="192" class="d5-title">2. DISOLUCIÓN DE LAS CORTES</text>
  <text x="360" y="208" class="d5-sub">Inmediata — nuevas elecciones</text>
  <line x1="360" y1="220" x2="360" y2="250" class="d5-arrow"/>
  <rect x="240" y="250" width="240" height="50" rx="8" class="d5-step"/>
  <text x="360" y="272" class="d5-title">3. RATIFICACIÓN NUEVAS CORTES</text>
  <text x="360" y="288" class="d5-sub">estudio del nuevo texto</text>
  <line x1="360" y1="300" x2="360" y2="330" class="d5-arrow"/>
  <rect x="240" y="330" width="240" height="50" rx="8" class="d5-step"/>
  <text x="360" y="352" class="d5-title">4. APROBACIÓN DEL TEXTO</text>
  <text x="360" y="368" class="d5-sub">2/3 de cada Cámara (nuevas)</text>
  <line x1="360" y1="380" x2="360" y2="410" class="d5-arrow"/>
  <rect x="240" y="410" width="240" height="44" rx="8" class="d5-ok"/>
  <text x="360" y="437" class="d5-title">5. REFERÉNDUM OBLIGATORIO</text>
  <text x="630" y="105" class="d5-note">2/3</text>
  <text x="630" y="195" class="d5-note">obligatoria</text>
  <text x="630" y="280" class="d5-note">nuevo estudio</text>
  <text x="630" y="360" class="d5-note">2/3 de nuevo</text>
  <text x="630" y="437" class="d5-note" style="fill:#2d8659">OBLIGATORIO</text>
</svg>
```

---

## D6 · Timeline de reformas constitucionales

**Sección**: § 8
**Propósito**: Línea de tiempo con las 4 reformas: 1992, 2011, 2024 y 2026.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 300" role="img" aria-label="Timeline de reformas de la Constitución Española">
  <style>
    .d6-axis{stroke:#0055a0;stroke-width:3}
    .d6-dot{fill:#0055a0;stroke:#003d73;stroke-width:2}
    .d6-year{font:700 16px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
    .d6-art{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d6-desc{font:11px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .d6-card{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .d6-badge{fill:#e89822}
  </style>
  <line x1="40" y1="150" x2="690" y2="150" class="d6-axis"/>
  <polygon points="690,150 680,143 680,157" fill="#0055a0"/>
  <circle cx="120" cy="150" r="12" class="d6-dot"/>
  <text x="120" y="130" class="d6-year">1992</text>
  <rect x="50" y="170" width="140" height="80" rx="8" class="d6-card"/>
  <rect x="50" y="170" width="140" height="22" rx="8" class="d6-badge"/>
  <text x="120" y="186" class="d6-art">Artículo 13.2</text>
  <text x="120" y="210" class="d6-desc">Sufragio pasivo UE</text>
  <text x="120" y="226" class="d6-desc">en municipales</text>
  <text x="120" y="242" class="d6-desc" style="font-weight:700">art. 167</text>
  <circle cx="280" cy="150" r="12" class="d6-dot"/>
  <text x="280" y="130" class="d6-year">2011</text>
  <rect x="210" y="170" width="140" height="80" rx="8" class="d6-card"/>
  <rect x="210" y="170" width="140" height="22" rx="8" class="d6-badge"/>
  <text x="280" y="186" class="d6-art">Artículo 135</text>
  <text x="280" y="210" class="d6-desc">Estabilidad</text>
  <text x="280" y="226" class="d6-desc">presupuestaria</text>
  <text x="280" y="242" class="d6-desc" style="font-weight:700">art. 167</text>
  <circle cx="440" cy="150" r="12" class="d6-dot"/>
  <text x="440" y="130" class="d6-year">2024</text>
  <rect x="370" y="170" width="140" height="80" rx="8" class="d6-card"/>
  <rect x="370" y="170" width="140" height="22" rx="8" class="d6-badge"/>
  <text x="440" y="186" class="d6-art">Artículo 49</text>
  <text x="440" y="210" class="d6-desc">Personas con</text>
  <text x="440" y="226" class="d6-desc">discapacidad</text>
  <text x="440" y="242" class="d6-desc" style="font-weight:700">art. 167</text>
  <circle cx="600" cy="150" r="12" class="d6-dot"/>
  <text x="600" y="130" class="d6-year">2026</text>
  <rect x="530" y="170" width="140" height="80" rx="8" class="d6-card"/>
  <rect x="530" y="170" width="140" height="22" rx="8" class="d6-badge"/>
  <text x="600" y="186" class="d6-art">Artículo 69.3</text>
  <text x="600" y="210" class="d6-desc">Senador propio</text>
  <text x="600" y="226" class="d6-desc">de Formentera</text>
  <text x="600" y="242" class="d6-desc" style="font-weight:700">art. 167</text>
  <text x="360" y="30" class="d6-year" style="font-size:14px">Reformas de la CE 1978</text>
  <text x="360" y="50" class="d6-desc">Las cuatro se tramitaron por el procedimiento del art. 167</text>
  <text x="360" y="285" class="d6-desc" style="font-style:italic">[REF-1992] [REF-2011] [REF-2024] [REF-2026]</text>
</svg>
```

---

## D7 · Suspensión de derechos (art. 55) — colectiva vs individual

**Sección**: § 5.6 / § 10
**Propósito**: Tabla comparativa de los derechos suspendibles según modalidad.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 400" role="img" aria-label="Derechos suspendibles según el artículo 55 de la CE">
  <style>
    .d7-col-col{fill:#d13c3c}
    .d7-col-ind{fill:#e89822}
    .d7-row-even{fill:#f5f5f5}
    .d7-row-odd{fill:#fff}
    .d7-head{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d7-cell{font:12px system-ui,sans-serif;fill:#1a1a1a}
    .d7-check{font:700 16px system-ui,sans-serif;text-anchor:middle}
    .d7-note{font:italic 11px system-ui,sans-serif;fill:#555}
  </style>
  <rect x="20" y="20" width="260" height="36" class="d7-col-col" rx="4"/>
  <rect x="290" y="20" width="180" height="36" class="d7-col-col" rx="4"/>
  <rect x="480" y="20" width="200" height="36" class="d7-col-ind" rx="4"/>
  <text x="150" y="43" class="d7-head">DERECHO</text>
  <text x="380" y="43" class="d7-head">COLECTIVA (55.1)</text>
  <text x="580" y="43" class="d7-head">INDIVIDUAL (55.2)</text>
  <rect x="20" y="60" width="660" height="30" class="d7-row-odd"/>
  <text x="30" y="80" class="d7-cell">17 · Libertad y seguridad</text>
  <text x="380" y="80" class="d7-check" style="fill:#2d8659">SI</text>
  <text x="580" y="80" class="d7-check" style="fill:#2d8659">SI (17.2)</text>
  <rect x="20" y="90" width="660" height="30" class="d7-row-even"/>
  <text x="30" y="110" class="d7-cell">18.2 · Inviolabilidad del domicilio</text>
  <text x="380" y="110" class="d7-check" style="fill:#2d8659">SI</text>
  <text x="580" y="110" class="d7-check" style="fill:#2d8659">SI</text>
  <rect x="20" y="120" width="660" height="30" class="d7-row-odd"/>
  <text x="30" y="140" class="d7-cell">18.3 · Secreto de las comunicaciones</text>
  <text x="380" y="140" class="d7-check" style="fill:#2d8659">SI</text>
  <text x="580" y="140" class="d7-check" style="fill:#2d8659">SI</text>
  <rect x="20" y="150" width="660" height="30" class="d7-row-even"/>
  <text x="30" y="170" class="d7-cell">19 · Residencia y circulación</text>
  <text x="380" y="170" class="d7-check" style="fill:#2d8659">SI</text>
  <text x="580" y="170" class="d7-check" style="fill:#d13c3c">NO</text>
  <rect x="20" y="180" width="660" height="30" class="d7-row-odd"/>
  <text x="30" y="200" class="d7-cell">20 · Libertad de expresión (1.a, 1.d, 5)</text>
  <text x="380" y="200" class="d7-check" style="fill:#2d8659">SI</text>
  <text x="580" y="200" class="d7-check" style="fill:#d13c3c">NO</text>
  <rect x="20" y="210" width="660" height="30" class="d7-row-even"/>
  <text x="30" y="230" class="d7-cell">21 · Derecho de reunión</text>
  <text x="380" y="230" class="d7-check" style="fill:#2d8659">SI</text>
  <text x="580" y="230" class="d7-check" style="fill:#d13c3c">NO</text>
  <rect x="20" y="240" width="660" height="30" class="d7-row-odd"/>
  <text x="30" y="260" class="d7-cell">28.2 · Derecho de huelga</text>
  <text x="380" y="260" class="d7-check" style="fill:#2d8659">SI</text>
  <text x="580" y="260" class="d7-check" style="fill:#d13c3c">NO</text>
  <rect x="20" y="270" width="660" height="30" class="d7-row-even"/>
  <text x="30" y="290" class="d7-cell">37.2 · Conflicto colectivo</text>
  <text x="380" y="290" class="d7-check" style="fill:#2d8659">SI</text>
  <text x="580" y="290" class="d7-check" style="fill:#d13c3c">NO</text>
  <rect x="20" y="310" width="660" height="70" rx="4" fill="#fff7eb" stroke="#e89822" stroke-width="1"/>
  <text x="30" y="328" class="d7-cell" style="font-weight:700">Condición de la suspensión colectiva:</text>
  <text x="30" y="344" class="d7-cell">Estado de excepción o de sitio (NO en alarma). LO 4/1981.</text>
  <text x="30" y="362" class="d7-cell" style="font-weight:700">Condición de la suspensión individual:</text>
  <text x="30" y="378" class="d7-cell">Investigaciones sobre bandas armadas o terrorismo · intervención judicial · control parlamentario.</text>
</svg>
```

---

## D8 · Jerarquía normativa

**Sección**: § 11
**Propósito**: Posición de la CE como norma suprema y cascada del ordenamiento.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 380" role="img" aria-label="Jerarquía normativa del ordenamiento jurídico español">
  <style>
    .d8-ce{fill:#0055a0}
    .d8-tr{fill:#3378b9}
    .d8-lo{fill:#5a94c9}
    .d8-lord{fill:#88b2d9}
    .d8-reg{fill:#b9cfea}
    .d8-cost{fill:#d8e3f2}
    .d8-title{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d8-label{font:600 12px system-ui,sans-serif;fill:#1a1a1a}
    .d8-right{font:11px system-ui,sans-serif;fill:#333}
    .d8-head{font:700 14px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
  </style>
  <text x="320" y="24" class="d8-head">JERARQUÍA NORMATIVA — art. 9.3 CE</text>
  <polygon points="260,50 380,50 420,100 220,100" class="d8-ce"/>
  <text x="320" y="82" class="d8-title">CONSTITUCIÓN 1978</text>
  <rect x="200" y="105" width="240" height="38" class="d8-tr"/>
  <text x="320" y="128" class="d8-title">Tratados Internacionales (art. 96)</text>
  <rect x="180" y="148" width="280" height="38" class="d8-lo"/>
  <text x="320" y="171" class="d8-title">Leyes orgánicas (art. 81)</text>
  <rect x="160" y="191" width="320" height="38" class="d8-lord"/>
  <text x="320" y="214" class="d8-title" style="font-size:11px;fill:#1a1a1a">Leyes ordinarias · Decretos-ley · Decretos legislativos</text>
  <rect x="140" y="234" width="360" height="38" class="d8-reg"/>
  <text x="320" y="256" class="d8-label" style="text-anchor:middle">Reglamentos (Real Decreto · Orden Ministerial · Ordenanza)</text>
  <rect x="120" y="277" width="400" height="38" class="d8-cost"/>
  <text x="320" y="300" class="d8-label" style="text-anchor:middle">Costumbre · Principios generales del derecho (supletorio)</text>
  <text x="450" y="78" class="d8-right" style="font-weight:700;fill:#0055a0">NORMA SUPREMA</text>
  <text x="450" y="128" class="d8-right">Prevalencia sobre leyes</text>
  <text x="450" y="171" class="d8-right">Derechos fundamentales</text>
  <text x="450" y="214" class="d8-right">Materias ordinarias</text>
  <text x="510" y="256" class="d8-right">Desarrollo ley</text>
  <text x="530" y="300" class="d8-right">Fuentes supletorias</text>
  <text x="320" y="360" class="d8-right" style="text-anchor:middle;font-style:italic">Supremacía constitucional: TC intérprete supremo (art. 1 LOTC)</text>
</svg>
```

---

## D9 · Tipos de mayoría parlamentaria

**Sección**: § 7.3
**Propósito**: Comparar los tipos de mayoría exigidos en la CE y ubicar las de reforma.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 340" role="img" aria-label="Tipos de mayoría parlamentaria">
  <style>
    .d9-bar{fill:#0055a0}
    .d9-bar-alt{fill:#e89822}
    .d9-bar-hot{fill:#d13c3c}
    .d9-line{stroke:#333;stroke-width:1}
    .d9-label{font:600 13px system-ui,sans-serif;fill:#1a1a1a}
    .d9-val{font:700 14px system-ui,sans-serif;fill:#fff}
    .d9-use{font:11px system-ui,sans-serif;fill:#555}
    .d9-head{font:700 14px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
    .d9-track{fill:#e0e0e0}
  </style>
  <text x="340" y="24" class="d9-head">TIPOS DE MAYORÍA — reforma y referéndum</text>
  <text x="40" y="70" class="d9-label">Mayoría SIMPLE</text>
  <rect x="200" y="55" width="480" height="24" class="d9-track" rx="4"/>
  <rect x="200" y="55" width="240" height="24" class="d9-bar" rx="4"/>
  <text x="210" y="72" class="d9-val">&gt; 50% votos EMITIDOS</text>
  <text x="40" y="88" class="d9-use">uso: decisiones ordinarias</text>
  <text x="40" y="120" class="d9-label">Mayoría ABSOLUTA</text>
  <rect x="200" y="105" width="480" height="24" class="d9-track" rx="4"/>
  <rect x="200" y="105" width="290" height="24" class="d9-bar" rx="4"/>
  <text x="210" y="122" class="d9-val">&gt; 50% MIEMBROS Cámara</text>
  <text x="40" y="138" class="d9-use">uso: investidura · LLOO · moción censura</text>
  <text x="40" y="170" class="d9-label">3/5 (tres quintos)</text>
  <rect x="200" y="155" width="480" height="24" class="d9-track" rx="4"/>
  <rect x="200" y="155" width="360" height="24" class="d9-bar-alt" rx="4"/>
  <text x="210" y="172" class="d9-val">3/5 DE CADA Cámara</text>
  <text x="40" y="188" class="d9-use">uso: REFORMA ORDINARIA (art. 167) · CGPJ · TC</text>
  <text x="40" y="220" class="d9-label">2/3 (dos tercios)</text>
  <rect x="200" y="205" width="480" height="24" class="d9-track" rx="4"/>
  <rect x="200" y="205" width="420" height="24" class="d9-bar-hot" rx="4"/>
  <text x="210" y="222" class="d9-val">2/3 DE CADA Cámara</text>
  <text x="40" y="238" class="d9-use">uso: REFORMA AGRAVADA (art. 168) · fallback 167 Congreso</text>
  <text x="40" y="270" class="d9-label">1/10 petición refer.</text>
  <rect x="200" y="255" width="480" height="24" class="d9-track" rx="4"/>
  <rect x="200" y="255" width="60" height="24" class="d9-bar-alt" rx="4"/>
  <text x="270" y="272" class="d9-val" style="fill:#1a1a1a">1/10 de MIEMBROS</text>
  <text x="40" y="288" class="d9-use">uso: solicitar referéndum facultativo reforma ordinaria</text>
  <text x="340" y="325" class="d9-use" style="text-anchor:middle;font-style:italic">En la reforma agravada el referéndum es OBLIGATORIO, no se solicita</text>
</svg>
```

---

## D10 · Niveles de protección de los derechos (art. 53)

**Sección**: § 5.5 / § 9
**Propósito**: Pirámide de protección: 14-29 (máxima) · 30-38 (media) · 39-52 (mínima).

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 380" role="img" aria-label="Niveles de protección de los derechos constitucionales">
  <style>
    .d10-top{fill:#0055a0}
    .d10-mid{fill:#3378b9}
    .d10-bot{fill:#88b2d9}
    .d10-label{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d10-range{font:600 11px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d10-detail{font:11px system-ui,sans-serif;fill:#1a1a1a}
    .d10-head{font:700 14px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
    .d10-badge-ok{fill:#2d8659}
    .d10-badge-no{fill:#d13c3c}
    .d10-bdg-text{font:700 11px system-ui,sans-serif;fill:#fff;text-anchor:middle}
  </style>
  <text x="340" y="24" class="d10-head">PROTECCIÓN DE LOS DERECHOS — art. 53 CE</text>
  <polygon points="290,40 390,40 410,90 270,90" class="d10-top"/>
  <text x="340" y="60" class="d10-label" style="font-size:10.5px">Máxima protección</text>
  <text x="340" y="78" class="d10-range">arts. 14-29</text>
  <polygon points="270,90 410,90 430,150 250,150" class="d10-mid"/>
  <text x="340" y="110" class="d10-label">Protección media</text>
  <text x="340" y="128" class="d10-range">arts. 30-38</text>
  <polygon points="250,150 430,150 450,220 230,220" class="d10-bot"/>
  <text x="340" y="170" class="d10-label" style="fill:#1a1a1a">Protección mínima</text>
  <text x="340" y="188" class="d10-range" style="fill:#1a1a1a">arts. 39-52</text>
  <rect x="20" y="50" width="230" height="60" rx="6" fill="#fff" stroke="#0055a0"/>
  <text x="30" y="68" class="d10-detail" style="font-weight:700">Derechos fundamentales</text>
  <text x="30" y="84" class="d10-detail">· Ley orgánica (art. 81)</text>
  <text x="30" y="100" class="d10-detail">· Amparo + preferencia y sumariedad</text>
  <rect x="440" y="110" width="220" height="58" rx="6" fill="#fff" stroke="#3378b9"/>
  <text x="450" y="128" class="d10-detail" style="font-weight:700">Derechos y deberes</text>
  <text x="450" y="144" class="d10-detail">· Ley ordinaria</text>
  <text x="450" y="158" class="d10-detail">· Jurisdicción ordinaria</text>
  <rect x="20" y="170" width="200" height="58" rx="6" fill="#fff" stroke="#88b2d9"/>
  <text x="30" y="188" class="d10-detail" style="font-weight:700">Principios rectores</text>
  <text x="30" y="204" class="d10-detail">· Informan legislación/práctica</text>
  <text x="30" y="218" class="d10-detail">· Solo alegables conforme a ley</text>
  <rect x="160" y="250" width="360" height="110" rx="8" fill="#f5f5f5" stroke="#0055a0"/>
  <text x="340" y="272" class="d10-head" style="font-size:12px">COMPARATIVA</text>
  <rect x="170" y="285" width="100" height="22" rx="4" class="d10-badge-ok"/>
  <text x="220" y="301" class="d10-bdg-text" style="font-size:10.5px">14-29: Amparo</text>
  <rect x="276" y="285" width="117" height="22" rx="4" class="d10-badge-no"/>
  <text x="334.5" y="301" class="d10-bdg-text" style="font-size:10.5px">30-38: NO amparo</text>
  <rect x="399" y="285" width="117" height="22" rx="4" class="d10-badge-no"/>
  <text x="457.5" y="301" class="d10-bdg-text" style="font-size:10.5px">39-52: NO amparo</text>
  <text x="340" y="328" class="d10-detail" style="text-anchor:middle">La objeción de conciencia (art. 30) TAMBIÉN tiene amparo</text>
  <text x="340" y="348" class="d10-detail" style="text-anchor:middle;font-style:italic">Todos vinculan a los poderes públicos (53.1) — respeto del contenido esencial</text>
</svg>
```

---

## D11 · Flujo del recurso de amparo

**Sección**: § 9.2
**Propósito**: Itinerario del recurso de amparo desde la vulneración al Tribunal Constitucional.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 440" role="img" aria-label="Flujo del recurso de amparo constitucional">
  <style>
    .d11-start{fill:#e89822}
    .d11-ord{fill:#0055a0}
    .d11-tc{fill:#d13c3c}
    .d11-ok{fill:#2d8659}
    .d11-title{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d11-sub{font:11px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d11-note{font:italic 11px system-ui,sans-serif;fill:#333;text-anchor:middle}
    .d11-arrow{stroke:#333;stroke-width:2;fill:none;marker-end:url(#d11-arrow)}
  </style>
  <defs>
    <marker id="d11-arrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#333"/>
    </marker>
  </defs>
  <rect x="240" y="20" width="220" height="50" rx="8" class="d11-start"/>
  <text x="350" y="42" class="d11-title">1. VULNERACIÓN</text>
  <text x="350" y="58" class="d11-sub">derecho arts. 14-29 o 30 (objeción)</text>
  <line x1="350" y1="70" x2="350" y2="100" class="d11-arrow"/>
  <rect x="240" y="100" width="220" height="60" rx="8" class="d11-ord"/>
  <text x="350" y="122" class="d11-title">2. TRIBUNALES ORDINARIOS</text>
  <text x="350" y="138" class="d11-sub">Procedimiento PREFERENTE</text>
  <text x="350" y="152" class="d11-sub">y SUMARIO (art. 53.2)</text>
  <line x1="350" y1="160" x2="350" y2="200" class="d11-arrow"/>
  <rect x="240" y="200" width="220" height="50" rx="8" class="d11-ord"/>
  <text x="350" y="222" class="d11-title">3. AGOTAMIENTO VÍA JUDICIAL</text>
  <text x="350" y="238" class="d11-sub">requisito previo al amparo</text>
  <line x1="350" y1="250" x2="350" y2="290" class="d11-arrow"/>
  <rect x="240" y="290" width="220" height="60" rx="8" class="d11-tc"/>
  <text x="350" y="312" class="d11-title">4. RECURSO DE AMPARO</text>
  <text x="350" y="328" class="d11-sub">Tribunal Constitucional</text>
  <text x="350" y="342" class="d11-sub">plazo 30 días</text>
  <line x1="350" y1="350" x2="350" y2="380" class="d11-arrow"/>
  <rect x="240" y="380" width="220" height="44" rx="8" class="d11-ok"/>
  <text x="350" y="407" class="d11-title">AMPARO / DENEGACIÓN</text>
  <rect x="20" y="100" width="200" height="120" rx="8" fill="#fff" stroke="#0055a0"/>
  <text x="120" y="122" class="d11-note" style="font-weight:700">ÁMBITO DEL AMPARO</text>
  <text x="120" y="142" class="d11-note">Art. 14 (igualdad)</text>
  <text x="120" y="158" class="d11-note">Arts. 15-29 (fundamentales)</text>
  <text x="120" y="174" class="d11-note">Art. 30.2 (objeción</text>
  <text x="120" y="188" class="d11-note">de conciencia)</text>
  <text x="120" y="210" class="d11-note" style="font-weight:700;fill:#d13c3c">NO cabe amparo:</text>
  <text x="120" y="226" class="d11-note" style="fill:#d13c3c">principios rectores (39-52)</text>
  <rect x="480" y="100" width="200" height="120" rx="8" fill="#fff" stroke="#0055a0"/>
  <text x="580" y="122" class="d11-note" style="font-weight:700">LEGITIMACIÓN</text>
  <text x="580" y="142" class="d11-note">· Toda persona natural o jurídica</text>
  <text x="580" y="158" class="d11-note">  con interés legitimo</text>
  <text x="580" y="174" class="d11-note">· Defensor del Pueblo (art. 54)</text>
  <text x="580" y="190" class="d11-note">· Ministerio Fiscal</text>
  <text x="580" y="210" class="d11-note" style="font-style:italic">LOTC 2/1979</text>
</svg>
```

---

## D12 · Organización territorial del Estado (Título VIII)

**Sección**: § 12
**Propósito**: Estructura territorial: Estado · CCAA · Provincia · Municipio. Introducción al Título VIII.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 360" role="img" aria-label="Organización territorial del Estado — Título VIII">
  <style>
    .d12-state{fill:#0055a0}
    .d12-ccaa{fill:#3378b9}
    .d12-prov{fill:#88b2d9}
    .d12-mun{fill:#d8e3f2}
    .d12-label{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d12-mun-label{font:700 12px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
    .d12-art{font:10px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d12-mun-art{font:10px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
    .d12-line{stroke:#0055a0;stroke-width:2;fill:none}
    .d12-head{font:700 14px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
    .d12-note{font:italic 11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <text x="360" y="24" class="d12-head">ORGANIZACIÓN TERRITORIAL — CE Título VIII</text>
  <rect x="260" y="50" width="200" height="44" rx="8" class="d12-state"/>
  <text x="360" y="72" class="d12-label">ESTADO</text>
  <text x="360" y="88" class="d12-art">art. 137 · principio de autonomía</text>
  <line x1="360" y1="94" x2="360" y2="130" class="d12-line"/>
  <line x1="160" y1="130" x2="560" y2="130" class="d12-line"/>
  <line x1="160" y1="130" x2="160" y2="150" class="d12-line"/>
  <line x1="360" y1="130" x2="360" y2="150" class="d12-line"/>
  <line x1="560" y1="130" x2="560" y2="150" class="d12-line"/>
  <rect x="64" y="150" width="192" height="44" rx="8" class="d12-ccaa"/>
  <text x="160" y="172" class="d12-label" style="font-size:12px">COMUNIDADES AUTÓNOMAS</text>
  <text x="160" y="188" class="d12-art">arts. 143-158 · Estatutos</text>
  <rect x="264" y="150" width="192" height="44" rx="8" class="d12-prov"/>
  <text x="360" y="172" class="d12-label" style="fill:#0b2f57">PROVINCIAS</text>
  <text x="360" y="188" class="d12-art" style="fill:#0b2f57">art. 141 · Diputaciones</text>
  <rect x="464" y="150" width="192" height="44" rx="8" class="d12-mun" stroke="#0055a0" stroke-width="1.5"/>
  <text x="560" y="172" class="d12-mun-label">MUNICIPIOS</text>
  <text x="560" y="188" class="d12-mun-art">art. 140 · Ayuntamientos</text>
  <line x1="560" y1="194" x2="560" y2="220" class="d12-line"/>
  <rect x="440" y="220" width="240" height="58" rx="8" fill="#fff7eb" stroke="#e89822" stroke-width="1.5"/>
  <text x="560" y="240" class="d12-mun-label" style="font-weight:700;fill:#a66410">AYUNTAMIENTO DE MADRID</text>
  <text x="560" y="258" class="d12-note">Capital del Estado (art. 5 CE)</text>
  <text x="560" y="273" class="d12-note">Pleno · Alcalde · Junta de Gobierno</text>
  <rect x="60" y="290" width="600" height="56" rx="8" fill="#f5f5f5" stroke="#0055a0"/>
  <text x="360" y="310" class="d12-mun-label" style="font-weight:700">PRINCIPIOS DEL TÍTULO VIII</text>
  <text x="360" y="326" class="d12-note">Autonomía (art. 137) · Solidaridad (art. 138) · Igualdad (art. 139) · No privilegio</text>
  <text x="360" y="342" class="d12-note" style="font-style:italic">Será objeto principal del Tema 2 del temario</text>
</svg>
```

---

## Notas de implementación

- Todos los SVG son **inline**, sin dependencias externas, escalables y copiables a cualquier contenedor HTML.
- Paleta principal: **Ayuntamiento de Madrid** (#0055a0) más auxiliares para alertas (#d13c3c), confirmación (#2d8659) y callouts (#e89822).
- Tipografía por defecto del navegador (`system-ui, sans-serif`) — no requiere cargar fuentes.
- Dimensiones entre 640-720 px de ancho para integrarse bien en columnas de lectura y en la impresión A4.
- `role="img"` + `aria-label` en cada raíz `<svg>` para accesibilidad.
- Los diagramas están listos para su embebido directo en `tema-1-piloto.html` (pestaña "Diagramas") o en `tema-1-contenido.md` cuando se exporte a HTML.
