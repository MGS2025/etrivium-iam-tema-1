# Tema 1 v2.1 | ETRIVIUM IAM

Piloto del **Tema 1** del temario oficial de la oposición **Técnico Auxiliar TIC C1** del Ayuntamiento de Madrid.

> **Título oficial del tema**: La Constitución Española (I): Estructura y contenido. Derechos y deberes fundamentales. Su garantía y suspensión.
>
> **Versión**: v2.1 — Validado por María y Ana (corrección ortográfica integral · ver `informe-correcciones-v2.1.html`)
> **Fecha**: 2026-06-11 (v2.1) · piloto inicial 2026-04-23

## Publicación

El piloto se publica en GitHub Pages: **https://mgs2025.github.io/etrivium-iam-tema-1-v1-piloto/**

## Entregables incluidos

| Archivo | Contenido |
|---|---|
| `tema-1-piloto.html` · `index.html` | HTML autosuficiente con 7 pestañas (Inicio, Contenido, Diagramas, Test, Casos, Validación, Fuentes), motor de test con penalización 1/3, 12 diagramas SVG embebidos |
| `tema-1-fuentes.md` | Registro de fuentes Tier 1 (BOE CE + 3 reformas) y Tier 2 (material validado por cliente) |
| `tema-1-indice.md` | Estructura del contenido · 13 secciones · tablas comparativas |
| `tema-1-contenido.md` | Temario teórico basado en el material aportado · sin ampliación externa |
| `tema-1-diagramas.md` | Catálogo de 12 diagramas SVG inline (estructura CE, reforma, suspensión, amparo, territorial...) |
| `tema-1-test.md` | Banco de **150 preguntas** (90 validadas + 60 nuevas) + 20 preguntas pedagógicas con explicación |
| `tema-1-caso-practico.md` | **6 casos prácticos** del Ayuntamiento de Madrid (72 preguntas en total) |
| `tema-1-validacion.md` | Checklist de revisión para María y Ana |
| `tema-1-changelog.md` | Registro de cambios |

## Decisiones estratégicas de la V1

1. **Corpus cerrado**: solo BOE de la Constitución 1978 y sus 3 reformas (1992, 2011, 2024). Sin doctrina externa.
2. **Sin ampliación x2** del contenido (a diferencia del Tema 11): se ciñe al material aportado por el cliente.
3. **Formato de test fiel al modelo examen**: fórmula "De acuerdo con la CE..." + 3 opciones pegadas + vocabulario literal.
4. **Más casos prácticos**: 6 frente a 1 del Tema 11. 3 validados por cliente + 3 nuevos (identidad digital, elecciones municipales, emergencia climática).
5. **12 diagramas SVG** autosuficientes, zero-dependencias.
6. **HTML autosuficiente**: sin CDN (salvo Google Fonts DM Sans), imprimible a PDF, accesible vía `role="img"` + `aria-label`.

## Contexto

- Contrato: 14.900 EUR + IVA con IAM (Informática del Ayuntamiento de Madrid)
- Deadline: 16 noviembre 2026
- Revisoras: María + Ana
- Piloto previo: Tema 11 (informática básica) — https://github.com/MGS2025/etrivium-iam-piloto

## Licencia

Todos los derechos reservados. Material de uso interno para el contrato con IAM.
