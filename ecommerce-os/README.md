# 🧠 E-COMMERCE OS — Command Center

Sistema estratégico y operativo (Business Operating System) para construir, validar,
lanzar y escalar negocios de e-commerce en Colombia / LATAM.

**Mercado base:** Colombia (COP) · **Modelo inicial:** validación vía contraentrega (COD)
con ruta a marca propia (Private Label) y LTV por recompra.

---

## Cómo se usa esto

Este directorio es la **memoria del negocio** (Business Memory). No es documentación
decorativa: cada archivo es un artefacto vivo que se actualiza con datos reales.

Regla dura (No Hallucination Policy):
- `FACT` = dato verificado con fuente.
- `ESTIMATE` = estimación con supuesto explícito.
- `HYPOTHESIS` = por validar.
- `OPINION` = juicio estratégico.
- `PENDING` = aún no tenemos el dato. **No se rellena con humo.**

Cada decisión importante se registra en `decisions/decision-log.md`.
Cada experimento en `analytics/experiments.md`.

---

## Estado actual del negocio (snapshot)

| Dimensión | Estado |
|---|---|
| Etapa | **Pre-validación** (0 ventas, 0 tienda) |
| Producto candidato #1 | Filtro de ducha anti-cloro/cal — score 84/100 |
| Decisión abierta (P0) | Velocidad (picadora) vs. defendibilidad (filtro) — **sin resolver** |
| Cuello de botella principal | Falta de decisión + supuestos de competencia/costo sin verificar en Dropi |
| Capital de prueba asumido | 3–6M COP |

---

## Mapa del Command Center

```
ecommerce-os/
├── strategy/     → modelo de negocio, posicionamiento, metas, ventaja competitiva
├── products/     → research, scorecards, ganadores, validación
├── customers/    → avatares, psicología, jobs-to-be-done, objeciones
├── offers/       → ofertas, pricing, bundles, upsells
├── brand/        → posicionamiento, identidad, voz
├── marketing/    → canales, funnels, estrategia
├── ads/          → meta, google, tiktok, creativos, hooks, testing
├── copy/         → headlines, ads, landing pages, email
├── analytics/    → kpis, dashboard, experimentos, reportes
├── finance/      → unit economics, cash flow, rentabilidad
├── operations/   → proveedores, logística, SOPs
└── decisions/    → decision log, experimentos, lecciones aprendidas
```

## Estado de población de archivos

| Archivo | Estado |
|---|---|
| `products/product-research.md` | ✅ Seedeado (research real 2026) |
| `products/product-scorecards.md` | ✅ Seedeado (TOP 3) |
| `products/winners.md` | ✅ Seedeado (#1 filtro de ducha) |
| `finance/unit-economics.md` | ✅ Seedeado (modelo COD) |
| `customers/avatars.md` | ✅ Seedeado (borrador, por validar con review mining) |
| `strategy/goals.md` | ✅ Seedeado |
| `decisions/decision-log.md` | ✅ Activo |
| Resto | ⏳ PENDING — se poblan cuando haya datos/decisión |

---

## Comandos reconocidos

`/research /products /score /avatar /offer /pricing /competitors /funnel /landing`
`/copy /hooks /ads /creative /meta /google /tiktok /cro /analytics /finance`
`/scale /retention /seo /content /shopify /automation /ceo /experiment /kill`
`/opportunity /product [nombre] /campaign` · `CEO REPORT` · `ACTIVATE E-COMMERCE CEO`
