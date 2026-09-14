# Unit Economics

**Producto modelado:** Filtro de ducha anti-cloro/cal
**Moneda:** COP · **Modelo:** contraentrega (COD)

> ⚠️ **DATOS REALES DE DROPI (2026-09-14) — el modelo ESTIMATE inicial estaba MAL.**
> Proveedor único: CYBERMARKET (PRIMO'S). Solo 2 SKUs, **sin cartuchos de repuesto**.
> - Combo Filtro Ajustable: costo **$42.000**, sugerido $62.000, stock 85
> - Filtro Universal: costo **$30.000**, sugerido $30.000, stock 917
> Mi estimación previa (costo $28.000 / PVP $119.900) era fantasía en ambos extremos.

## Realidad con costo Dropi (FACT)

| Escenario | PVP | Costo | Flete+recaudo+emp. | Bruto pre-ads | Veredicto |
|---|---:|---:|---:|---:|---|
| Combo al sugerido | 62.000 | 42.000 | ~15.500 | **~4.500 (7%)** | ☠️ Inviable para ads |
| Combo forzado | 99.900 | 42.000 | ~17.000 | ~40.900 | ⚠️ Price-check risk |
| Universal | 89.900 | 30.000 | ~16.200 | ~43.700 | 🟡 Menos malo |

CAC por pedido ENTREGADO (entrega 72%, CPA_lead ~18k) ≈ **$25.000**. Solo los escenarios
forzados dejan contribución, y sin cartucho no hay LTV que lo justifique.
**Conclusión: vía Dropi el filtro NO es viable como negocio defendible.** Ver decision-log D-005.

## Modelo private-label (opción A — objetivo real)

ESTIMATE por verificar en Alibaba/1688:
- Filtro FOB ~$2–4 USD (~8.000–16.000 COP) + cartuchos propios baratos.
- Restaura margen ~70% Y habilita recompra de cartuchos = LTV real.
- Requiere MOQ (~$800–1.500 USD) + lead time 20–35 días. PENDING verificación de costo.

## Prueba de estrés COD (lo que las listas ignoran)

| Variable | Supuesto |
|---|---|
| CPA por lead confirmado | ~18.000 COP (ESTIMATE, varía mucho) |
| Tasa de entrega efectiva | 72% |
| **CAC por pedido ENTREGADO** | **~25.000 COP** |
| **Contribución por pedido entregado** | **~47.100 COP (39% del PVP)** ✅ |
| **Break-even CPA_lead** | **~51.900 COP** (colchón amplio) |

## Sensibilidad — las 2 variables que matan el negocio

| Escenario | Tasa entrega | CPA_lead | Contribución/pedido |
|---|---:|---:|---:|
| Conservador | 62% | 25.000 | ~32.000 |
| **Base** | 72% | 18.000 | ~47.100 |
| Agresivo | 78% | 14.000 | ~54.000 |

> Todo lo demás es secundario. Si tasa entrega < 60% o CPA_lead > 52k → revisar.

## Supuestos a verificar (PENDING)

- Costo real del producto y flete (Dropi/importación).
- CPA_lead real (solo se sabe tras el creative/traffic test).
- % del flete trasladable al cliente (mejora margen si aplica).

## LTV (por construir tras primera venta)

- Recompra objetivo: cartuchos cada 2–3 meses → convierte una venta única en flujo.
- Suscripción de repuestos = palanca #1 de LTV. Ver `offers/upsells.md` (PENDING).
