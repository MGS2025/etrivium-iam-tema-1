# Tema 1 V1 — Piloto | ETRIVIUM IAM

Piloto del **Tema 1** del temario oficial de la oposicion **Tecnico Auxiliar TIC C1** del Ayuntamiento de Madrid.

> **Titulo oficial del tema**: La Constitucion Espanola (I): Estructura y contenido. Derechos y deberes fundamentales. Su garantia y suspension.
>
> **Version**: V1 — Pendiente validacion
> **Fecha**: 2026-04-23

## Publicacion

El piloto se publica en GitHub Pages: **https://mgs2025.github.io/etrivium-iam-tema-1-v1-piloto/**

## Entregables incluidos

| Archivo | Contenido |
|---|---|
| `tema-1-piloto.html` · `index.html` | HTML autosuficiente con 7 pestanas (Inicio, Contenido, Diagramas, Test, Casos, Validacion, Fuentes), motor de test con penalizacion 1/3, 12 diagramas SVG embebidos |
| `tema-1-fuentes.md` | Registro de fuentes Tier 1 (BOE CE + 3 reformas) y Tier 2 (material validado por cliente) |
| `tema-1-indice.md` | Estructura del contenido · 13 secciones · tablas comparativas |
| `tema-1-contenido.md` | Temario teorico basado en el material aportado · sin ampliacion externa |
| `tema-1-diagramas.md` | Catalogo de 12 diagramas SVG inline (estructura CE, reforma, suspension, amparo, territorial...) |
| `tema-1-test.md` | Banco de **150 preguntas** (90 validadas + 60 nuevas) + 20 preguntas pedagogicas con explicacion |
| `tema-1-caso-practico.md` | **6 casos practicos** del Ayuntamiento de Madrid (72 preguntas en total) |
| `tema-1-validacion.md` | Checklist de revision para Maria y Ana |
| `tema-1-changelog.md` | Registro de cambios |

## Decisiones estrategicas de la V1

1. **Corpus cerrado**: solo BOE de la Constitucion 1978 y sus 3 reformas (1992, 2011, 2024). Sin doctrina externa.
2. **Sin ampliacion x2** del contenido (a diferencia del Tema 11): se cine al material aportado por el cliente.
3. **Formato de test fiel al modelo examen**: formula "De acuerdo con la CE..." + 3 opciones pegadas + vocabulario literal.
4. **Mas casos practicos**: 6 frente a 1 del Tema 11. 3 validados por cliente + 3 nuevos (identidad digital, elecciones municipales, emergencia climatica).
5. **12 diagramas SVG** autosuficientes, zero-dependencias.
6. **HTML autosuficiente**: sin CDN (salvo Google Fonts DM Sans), imprimible a PDF, accesible via `role="img"` + `aria-label`.

## Contexto

- Contrato: 14.900 EUR + IVA con IAM (Informatica del Ayuntamiento de Madrid)
- Deadline: 16 noviembre 2026
- Revisoras: Maria + Ana
- Piloto previo: Tema 11 (informatica basica) — https://github.com/MGS2025/etrivium-iam-piloto

## Licencia

Todos los derechos reservados. Material de uso interno para el contrato con IAM.
