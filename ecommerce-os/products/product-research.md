# Product Research

**Última actualización:** 2026-09-14 · **Analista:** AGENT 03 — Product Hunter

## Insight rector (FACT + ESTIMATE)

En Colombia el factor que decide rentabilidad **no es la viralidad del producto,
sino la economía de la contraentrega (COD)**. Las listas de "productos ganadores"
son ruido: todo el que las lee ya vende eso.

| Realidad COD Colombia | Valor | Tipo |
|---|---|---|
| Entrega efectiva con confirmación WhatsApp/IVR | 65–78% | FACT (fuentes 2026) |
| Entrega sin confirmación | 50–60% | FACT |
| Devolución / RTO estructural | 20–35% | FACT |
| Método de pago dominante | Contraentrega | FACT |
| Crecimiento transacciones digitales CO Q1-2026 (YoY) | +22,2% | FACT (CCCE) |

**Consecuencia:** el criterio #1 de selección es **"baja culpa del comprador en la
puerta"** — productos utilitarios que resuelven un problema visible se rechazan menos
que compras impulsivas de las que uno se arrepiente. Métrica real = **CPA por pedido
entregado y pagado** = CPA_lead ÷ (tasa confirmación × tasa entrega), no el CPA a secas.

## Descartados de entrada (con razón)

| Producto | Motivo de descarte |
|---|---|
| Ropa oversized / hoodies | Rechazo por talla → RTO altísimo |
| Sauna blanket / botella hidrógeno | Voluminoso (flete) + evidencia débil / pseudociencia |
| Serums cosméticos ingeribles | Requieren notificación INVIMA → fricción regulatoria |

## Segunda ronda de caza (2026-09-14, tras kill del filtro) — calibrada

**Criterios duros aprendidos (GO/NO-GO):**
1. Margen ≥ 3× (sugerido ÷ costo). El filtro dio 1,5× → muerto.
2. Ticket $90k–$180k COP (FACT: Dropi subió fletes en Q4 2026 → se necesita ticket más alto).
3. Baja culpa en la puerta (dolor/problema, no impulso arrepentible) → RTO <25%.
4. Palanca de repeat o AOV (consumible / bundle / línea complementaria).
5. <1 kg, sin talla, sin INVIMA pesado.

**Lista de caza (verificar costo/sugerido en Dropi — solo el usuario ve ese dato):**

| # | Tesis | Términos Dropi | Repeat/LTV | Ruta private-label |
|---|---|---|---|---|
| 1 | Masajeador cervical / EMS | masajeador cuello, cervical, electroestimulador | Bajo (cross-sell) | Marca bienestar + geles/recambio |
| 2 | Línea mascotas (cepillo quita-pelo +) | cepillo mascotas, quita pelo, corta uñas mascota | **Alto** (snacks/accesorios) | Pet D2C con consumibles |
| 3 | Depiladora facial / removedor vello | depiladora facial, removedor vello | Bajo | Beauty-tech + reposición |
| 4 | Gadget hogar wow | organizador nevera, selladora bolsas, trapeador | Bajo | Débil (commodity) |
| 5 | Corrector postura / faja | corrector postura, faja lumbar | Bajo | ⚠️ talla = riesgo RTO |

**Estado:** esperando datos de Dropi del usuario (costo/sugerido/stock) para puntuar.
Regla: el que pase GO/NO-GO con mejor margen + repeat → se compromete a test. No más caza.

Fuentes 2ª ronda: Andrey Business (Dropi CO 2026), Stockeado, Overviewdata (COD research),
Zendrop/SaleHoo (high-margin 2026). Categorías con margen: bienestar, mascotas, beauty tools,
hogar/cocina, consumibles.

## Short-list evaluado → ver `product-scorecards.md`

1. 🥇 Filtro de ducha anti-cloro/cal — 84/100
2. 🥈 Picadora multifunción (chopper) — 76/100
3. 🥉 Máscara LED facial — 71/100

## Verificación de competencia en Colombia (2026-09-14)

**FACT (web pública):**
- MercadoLibre Colombia tiene múltiples listings activos: "filtro ducha cloro",
  "filtro agua ducha", "filtro elimina cloro", "filtro para duchas elimina el cloro".
- EASY Colombia (retail físico) vende "Filtro para ducha anti-cloro".
- Referente de marca global: **Jolie** (US) — filtro premium, "clinically tested",
  ~46% menos caída reportada, +158 publicaciones. Prueba que el modelo BRANDED premium
  funciona; el mercado CO en cambio es commodity sin marca.

**Conclusión corregida:** NO es white space. La tesis cambia de "ser primero" a
**"ser la primera MARCA que educa el problema y captura recompra por cartuchos"**.
Moat = brand + educación + suscripción, no primer movimiento.

**Riesgo #1 nuevo — poder de fijación de precio:** si el cliente compara en ML un filtro
de aspecto idéntico más barato, el bundle de ~120k COP necesita diferenciación fuerte
para sostenerse. **Este es el primer supuesto a probar** en el test de oferta.

## Supuestos que aún NO están verificados (PENDING)

- **Precio ancla exacto en COP** en ML/Falabella/EASY (ML CO bloqueado por egress proxy;
  requiere que el usuario lo consulte o acceso alterno). Crítico para pricing.
- Costo de producto real (importado / catálogo Dropi) — requiere login de Dropi del usuario.
- Densidad de anunciantes activos en Meta Ad Library CO.

## Fuentes

- Shopify — productos más vendidos Colombia 2026
- Glimpse / Sell The Trend — Google Trends & viral products 2026
- Andrey Business — Dropi Colombia 2026 (tasas COD)
- Fufills — Cash on Delivery Latin America guide
- Trade.gov — Colombia eCommerce country guide
