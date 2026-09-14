# Unit Economics

**Producto modelado:** Filtro de ducha anti-cloro/cal (bundle: filtro + 2 cartuchos)
**Moneda:** COP · **Modelo:** contraentrega (COD) · **Tipo:** ESTIMATE (supuestos abajo)

## Base case

| Concepto | COP |
|---|---:|
| PVP (bundle) | 119.900 |
| Costo producto (importado) | −28.000 |
| Flete recaudo contraentrega | −12.000 |
| Comisión recaudo/plataforma (~4%) | −4.800 |
| Empaque / misc | −3.000 |
| **Margen bruto pre-ads** | **72.100 (60%)** |

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
