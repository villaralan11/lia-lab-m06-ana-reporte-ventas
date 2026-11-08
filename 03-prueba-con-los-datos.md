# 03 · La prueba: los tres reportes de este lunes y lo que entregó el asistente

> **Qué hice:** pegué los tres reportes del lunes en el chat, le di al asistente el criterio
> exacto de mi decisión (del archivo [01](./01-flujo-cinco-piezas.md)) y le pedí que
> aplicara el registro + decisión + borrador, con la banda "si del criterio no sale, pasa a
> Ana". Aquí está lo que entregó.

---

## Registro del agente (fila por folio con su decisión)

| Vendedor | Folio | Cliente | Monto | Estatus del vendedor | Decisión del agente | Motivo (una frase) |
|---|---|---|---|---|---|---|
| Beto Ríos | F-1041 | Papelería Lupita | $12,400 | Facturado | **CUENTA** | Facturado, en la semana, no repetido |
| Beto Ríos | F-1042 | Abarrotes El Sol | $18,900 | Facturado | **CUENTA** | Facturado, en la semana, no repetido |
| Beto Ríos | F-1044 | Miscelánea Norte | $9,500 | Cancelado | **EXCLUYE** | Cancelado → el criterio lo elimina |
| Beto Ríos | F-1045 | Super Hogar | $27,300 | Facturado | **CUENTA** | Facturado, en la semana, no repetido |
| Carla Núñez | F-2210 | Ferretería Centro | $31,000 | (sin estatus en el mensaje) | **CUENTA** | Facturado según el mensaje; por confirmar en el sistema |
| Carla Núñez | F-2211 | Mercado Verde | $22,500 | (sin estatus en el mensaje) | **CUENTA** (1 VEZ) | Facturado de acuerdo al mensaje |
| Carla Núñez | F-2211 | Mercado Verde | $22,500 | (duplicado) | **EXCLUYE el segundo** | Folio repetido → se cuenta una vez |
| Carla Núñez | F-2213 | Tienda La Esquina | $15,800 | (sin estatus en el mensaje) | **CUENTA** | Facturado según el mensaje; por confirmar en el sistema |
| Mauricio Pérez | (sin folio) | Papelería Central | $24,500 | Facturado | **CUENTA** | Facturado (monto en miles: se normaliza) |
| Mauricio Pérez | (sin folio) | Cafetería Roma | $17,200 | Facturado | **CUENTA** | Facturado (monto en miles: se normaliza) |
| Mauricio Pérez | (sin folio) | Hoteles del Valle | $33,000 | En proceso de cierre | **EXCLUYE + bandera** | No facturado → no cuenta; pasa a Ana para verificar en sistema |

## Totales recalculados (contra las metas)

| Vendedor | Total cuenta | Meta | % de meta | Total que el vendedor declaró | Problema |
|---|---|---|---|---|---|
| Beto Ríos | **$58,600** | $60,000 | **97.7 %** | $68,100 | Su total incluye el F-1044 cancelado: **$9,500 de más** |
| Carla Núñez | **$69,300** | $60,000 | **115.5 %** | $91,800 | Su total incluye el F-2211 dos veces: **$22,500 de más** |
| Mauricio Pérez | **$41,700** | $60,000 | **69.5 %** | $74,700 | Su total suma los $33,000 de "En proceso de cierre", que no cuenta |
| **Equipo** | **$169,600** | $180,000 | **94.2 %** | $234,600 (si los sumamos crudos) | Los tres totales "as is" no son los del criterio |

---

## El borrador del reporte (lo que el asistente armó para que Ana lo apruebe)

> Asunto: Reporte semanal de ventas — semana del 12 al 18 de octubre
> Para: Director Comercial
> (borrador: corresponde a Ana aprobarlo y mandarlo antes de las 11:00)

---

Buenos días,

Comparto el cierre de esta semana (del 12 al 18 de octubre), con el criterio: solo facturado dentro
de la semana; sin cancelados, cotizaciones ni folios repetidos.

**Ventas por vendedor**
- Beto Ríos: **$58,600** (97.7 % de la meta de $60,000)
- Carla Núñez: **$69,300** (115.5 % de la meta de $60,000)
- Mauricio Pérez: **$41,700** (69.5 % de la meta de $60,000)

**Total del equipo:** **$169,600** — **94.2 %** de la meta de $180,000.

**Lo que se excluyó y por qué:**
- **F-1044 — Miscelánea Norte ($9,500):** cancelado, no cumple el criterio.
- **F-2211 (2.ª aparición) — Mercado Verde ($22,500):** folio ya contado, repetido en el
  reporte de Carla; se cuenta una sola vez.
- **Hoteles del Valle ($33,000) de Mauricio Pérez:** marcado "En proceso de cierre", no
  facturado en la semana; pendiente confirmar en sistema si queda facturado. Si se
  lanza en la semana próxima, va en ese reporte.

**Bandera para Ana (antes de mandar):**
1. El total declarado de **Beto no cuadra** ($68,100 vs. $58,600): pasar a validar el
   F-1044 en el sistema (¿de verdad quedó cancelado o era otro folio?).
2. El total declarado de **Carla no cuadra** ($91,800 vs. $69,300): doble F-2211 en su
   mensaje. Confirmar en el sistema los folios (F-2210, F-2211, F-2213).
3. Los datos de **Mauricio** llegaron **sin folios** y en miles de pesos: por eso hay que cruzar el
   total facturado en el sistema para dejarlo entrar al reporte. Actualización del criterio: pedir folios a Mauricio como lo exigen los otros dos.

Atentamente,
[agente] — pendiente de aprobación de Ana
