# Product Scorecards

**Escala:** 0–100 · 90–100 excepcional · 80–89 alto potencial · 70–79 interesante ·
60–69 validar con cautela · <60 bajo potencial.

**Aviso:** los scores de *Competencia* son ESTIMATE — no se scrapeó Dropi/Ad Library en
vivo. Se recalculan cuando tengamos ese dato.

> **CORRECCIÓN 2026-09-14 (red-team):** el score inicial de Competencia del filtro (85 =
> "white space") estaba SOBREVALORADO. Verificación pública muestra oferta commodity
> activa en Colombia: múltiples listings en MercadoLibre CO ("filtro ducha cloro",
> "filtro agua ducha", "filtro elimina cloro") + presencia retail en EASY Colombia (FACT).
> No es mercado virgen. La oportunidad **no es ser primero, es ser la primera MARCA**
> (educación del problema + suscripción de cartuchos). Score de Competencia bajado 85→55.
> Nuevo riesgo #1: **poder de fijación de precio** — el cliente puede comparar en ML un
> filtro de aspecto idéntico a menor precio. Precio ancla exacto en COP = PENDING (ML CO
> bloqueado por egress). Ver `product-research.md`.

## TOP 3

| # | Producto | Demanda | Margen | Competencia (est.) | Fit COD | LTV/Recompra | **SCORE** |
|---|---|---|---|---|---|---|---|
| 🥇 | Filtro de ducha anti-cloro/cal | Alta ↑ | Alto (60%)* | **Media** (commodity ML) | Alto | **Alto** (repuestos) | **~80** |
| 🥈 | Picadora multifunción (chopper) | Muy alta | 65–75% | **Muy alta** | Muy alto | Bajo | **76** |
| 🥉 | Máscara LED facial | Alta | 50–65% | Media-alta | Medio (ticket alto) | Bajo-medio | **71** |

## Desglose ponderado — #1 Filtro de ducha

| Factor | Score | Peso | Resultado | Nota |
|---|---:|---:|---:|---|
| Demanda | 80 | 15% | 12,0 | Tendencia global "hard water", CO virgen |
| Margen | 75 | 15% | 11,25 | ~60% bruto pre-ads (ver unit-economics) |
| Competencia | 55 | 12% | 6,6 | CORREGIDO: commodity activa en ML CO + EASY (FACT), no white space |
| Fit COD (poca culpa puerta) | 85 | 15% | 12,75 | Resuelve problema real |
| Diferenciación | 80 | 10% | 8,0 | Espacio de marca + educación |
| Viralidad / demo | 75 | 8% | 6,0 | Antes/después de agua |
| Logística | 85 | 8% | 6,8 | Liviano, no frágil |
| LTV / recompra | 90 | 12% | 10,8 | Cartuchos = casi suscripción |
| Riesgo / regulación | 70 | 5% | 3,5 | Sin INVIMA (no cosmético) |
| **TOTAL** | | 100% | **~80** | (bajó de 84 tras corrección de Competencia) |

*Margen 60% marcado con asterisco: en riesgo si el ancla de precio de ML obliga a bajar PVP.

**Contra (anti-humo):** (1) validación más lenta — mercado *problem-unaware*, hay que
educar el problema antes de vender; (2) NO es white space — hay commodity en ML/EASY, así
que el moat debe ser marca + educación + suscripción de cartuchos, no ser primero;
(3) poder de fijación de precio es el riesgo a probar primero. Si la prioridad es caja
rápida, #2 gana en velocidad a costa de red ocean y cero LTV.

## Kill criteria (definir ANTES de gastar) — ver `decisions/decision-log.md`

- CPA_entregado > break-even → matar/iterar.
- Tasa entrega < 60% → problema de confirmación/producto.
- CVR landing < umbral (definir en test).
