# Decision Log

Cada decisión estratégica importante se registra aquí. Formato fijo.

---

## D-001 — Mercado base y modelo de validación

```
DATE:            2026-09-14
DECISION:        Colombia (COP) como mercado base; validar vía contraentrega (COD)
                 con ruta a Private Label + LTV por recompra.
WHY:             COD es el método dominante en CO; permite validar sin checkout de
                 tarjeta; ruta a marca evita commodity.
DATA:            Entrega efectiva 65–78% con confirmación; RTO 20–35% (fuentes 2026).
ASSUMPTION:      Usuario opera desde Colombia (por confirmar explícitamente).
EXPECTED RESULT: Filtro de selección de producto centrado en "baja culpa en la puerta".
ACTUAL RESULT:   PENDING
LESSON:          PENDING
NEXT ACTION:     Confirmar mercado con el usuario.
```

---

## D-002 — Producto candidato #1

```
DATE:            2026-09-14
DECISION:        Filtro de ducha anti-cloro/cal como candidato #1 (score 84/100).
WHY:             White space local + LTV por cartuchos + baja culpa en puerta.
DATA:            Ver products/product-scorecards.md y finance/unit-economics.md.
ASSUMPTION:      Competencia baja y costo ~28k COP (ESTIMATE, sin verificar en Dropi).
EXPECTED RESULT: Candidato apto para test de oferta.
ACTUAL RESULT:   PENDING (sin test)
LESSON:          PENDING
NEXT ACTION:     Verificar competencia/costo en Dropi; luego test de oferta.
```

---

## D-003 — [RESUELTA / P0] Velocidad vs. defendibilidad

```
DATE:            2026-09-14
DECISION:        RESUELTA → DEFENDIBILIDAD. Se valida el filtro de ducha.
WHY:             El usuario prioriza construir activo/empresa (LTV, marca) sobre caja rápida.
DATA:            Scorecards 84 (ahora ~80) vs 76.
ASSUMPTION:      Se acepta validación más lenta (mercado problem-unaware).
EXPECTED RESULT: Avanzar a verificación de mercado → oferta → test.
ACTUAL RESULT:   Ejecutado; ver D-004.
LESSON:          -
NEXT ACTION:     Verificar competencia/precio CO (D-004).
```

---

## D-004 — Corrección de tesis tras verificar mercado CO

```
DATE:            2026-09-14
DECISION:        Mantener filtro de ducha, pero corregir tesis: NO es white space.
WHY:             Verificación pública: commodity activa en MercadoLibre CO + EASY retail.
DATA:            Múltiples listings ML CO; EASY vende anti-cloro; Jolie prueba modelo branded.
ASSUMPTION:      El moat viable es marca + educación + suscripción de cartuchos.
EXPECTED RESULT: Score baja 84→~80; nuevo riesgo #1 = poder de fijación de precio.
ACTUAL RESULT:   PENDING — a probar en test de oferta.
LESSON:          No puntuar "white space" sin verificar oferta local primero. Corregido en caliente.
NEXT ACTION:     Conseguir precio ancla real en COP (usuario) + decidir posicionamiento
                 premium vs. paridad antes de montar tienda/oferta.
```

---

## D-005 — [KILL parcial / P0] Filtro vía Dropi falla la tesis

```
DATE:            2026-09-14
DECISION:        MATAR el filtro de ducha como negocio vía Dropi dropshipping.
                 Mantener el filtro SOLO si se hace private-label (importación).
WHY:             Datos reales de Dropi rompen las 2 razones para elegir este producto:
                 (1) NO hay cartuchos de repuesto -> sin LTV/suscripcion -> sin moat.
                 (2) Costo proveedor $42k/$30k vs ancla mercado $30-62k -> margen ~7%
                     al precio sugerido -> imposible pagar ads en COD.
                 (3) Proveedor unico (CYBERMARKET) -> cero diferenciacion + riesgo supply.
DATA:            Dropi: Combo costo $42.000/sug $62.000; Universal costo $30.000/sug $30.000.
                 CAC entregado COD ~$25.000. Break-even CAC al sugerido = $4.500.
ASSUMPTION:      Costo import private-label ~$2-4 USD/filtro (ESTIMATE, por verificar).
EXPECTED RESULT: Elegir entre A) private-label directo, B) probe de demanda barato, C) pivot.
ACTUAL RESULT:   PENDING decision del usuario.
LESSON:          Verificar SIEMPRE costo real de proveedor y existencia de SKU de recompra
                 ANTES de construir la tesis de LTV. El canal de abastecimiento define
                 si un producto puede o no ser defendible.
NEXT ACTION:     Usuario decide A/B/C. Si A -> verificar costos Alibaba/1688 antes de comprar.
```

---

## D-006 — Cambio de unidad de decisión: vertical con recompra

```
DATE:            2026-09-14
DECISION:        Dejar de cazar "producto héroe"; comprometer un VERTICAL con LTV.
                 Vertical elegido: MASCOTAS. Modelo: adquisición por producto-cuña ->
                 recompra por consumibles/accesorios -> bundle -> suscripción.
WHY:             Dropi solo da productos de una sola venta; el problema no era el producto
                 sino la ausencia de recompra. Pet es el único de los 5 con LTV estructural
                 y el endgame defendible más claro (marca pet D2C). Fiel a "defendibilidad".
DATA:            Research: margen pet 40-60%, baja sensibilidad al precio, recompra real.
ASSUMPTION:      El motor de recompra arranca por aseo/accesorios (ingeribles = registro ICA).
EXPECTED RESULT: El producto-cuña solo adquiere; la rentabilidad vive en la recompra.
ACTUAL RESULT:   PENDING — falta elegir producto-cuña con datos de Dropi + confirmación usuario.
LESSON:          Si el canal no ofrece SKU de recompra, subir el nivel: elegir vertical, no producto.
NEXT ACTION:     (1) Usuario confirma o redirige el vertical. (2) Buscar producto-cuña pet en
                 Dropi (cepillo/cortauñas/fuente) y pasar costo/sugerido para puntuar.
```
