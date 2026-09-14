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
