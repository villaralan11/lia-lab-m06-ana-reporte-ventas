# 01 · El flujo, con las cinco piezas de la plantilla (lectura 6.1)

> **Plantilla aplicada:** Flujo: [nombre] · Disparador: ¿cuándo arranca? · Registro: ¿qué
> datos anota y dónde? · Decisión: ¿qué decide y con qué criterio? · Respuesta: ¿qué
> entrega? · Evidencia: ¿qué queda para revisar, quién y cada cuánto?

---

## Flujo: **Reporte semanal de ventas para el Director Comercial**

## Disparador · ¿cuándo arranca?

**Cada lunes a las 9:05.** No es "cuando se pueda": 9:05 es la hora después del límite de
recibo (los vendedores entregan antes de las 9:00) y deja tiempo de sobra para la revisión
de Ana antes de que el reporte salga a las 11:00 (regla del brief). El disparador funciona
solo si ya llegaron los tres reportes; si a las 9:05 falta uno, el flujo arranca igual con
la alerta de faltante en la evidencia y Ana ya sabe a quién está esperando.

## Registro · ¿qué datos anota de cada caso y dónde?

Antes de decidir nada, el agente llena una fila por **cada folio** que llegó en los tres
reportes, en la hoja "Registro ventas semana" con estos datos:

| Campo | De dónde sale |
|---|---|
| Vendedor | El remitente del reporte (Beto / Carla / Mauricio) |
| Folio | El número de folio (F-1041, F-2210…) |
| Cliente | El nombre del cliente |
| Monto | El monto del folio, normalizado a pesos (los miles de Mauricio pasan a $) |
| Estatus según el vendedor | Facturado / Cancelado / En proceso / (vacío) |
| Fuente | Hoja de cálculo, chat o correo (cómo llegó el dato) |
| Resultado del sistema | Qué marca el sistema: facturado o no, en qué fecha |

La columna "Resultado del sistema" es el punto crítico: el correo del vendedor **no es la
verdad**, el sistema sí. Si el sistema no confirma el folio facturado dentro de la semana,
no se cuenta (aunque el vendedor diga lo contrario).

## Decisión · ¿qué resuelve el agente, con qué criterio? ¿Qué casos pasan a una persona?

**El criterio está escrito (una venta cuenta solo si):**
1. El folio está **facturado** (no cotización ni "en proceso").
2. La facturación cayó **dentro de la semana que se reporta** (lunes a domingo anterior).
3. **No** está cancelado.
4. El folio **no está repetido** (si el mismo folio aparece dos veces, se cuenta una).

**El agente decide solo** con ese criterio: cuenta o no cuenta cada folio, suma los que
cuentan por vendedor, calcula el % contra la meta de $60,000 por vendedor y el total del
equipo contra $180,000, y arma la nota de exclusiones.

**Lo que pasa a Ana (no se resuelve solo):**
- Folio del que **no hay confirmación** en el sistema (factura no localizada, fecha dudosa).
- Estatus **distinto al del sistema** (el vendedor dice "Facturado", el sistema dice otra cosa).
- El **total del vendedor no cuadra** con la suma de sus líneas: es el acceso a preguntar,
  no a corregir por cuenta propia.
- Montos raros (cero, negativos, sin folio).

## Respuesta · ¿qué entrega? ¿Borrador para aprobar o acción directa?

**Un BORRADOR, nunca un envío directo.** El agente entrega el texto del reporte al
Director Comercial (ventas por vendedor, % de meta, total del equipo y la nota de lo
excluido) **para que lo revise y lo aprube Ana**, quien se lo manda a la dirección antes de
las 11:00.

Por qué no envío directo: este reporte es el insumo con el que el Director Comercial toma
decisiones de pedidos y comisiones. El propio brief advierte que Ana "no quiere que un
error llegue al director". El agente solo ve la fila; Ana ve la operación. El error del
doble folio de esta semana (buen ejemplo en [03](./03-prueba-con-los-datos.md)) es exactamente
el escenario que no dejaría pasar un envío automático.

## Evidencia · ¿qué queda para revisar, quién la revisa y cada cuánto?

- **El registro semanal queda completo**: la fila de cada folio con (cuenta / no cuenta) y
  el **motivo** de la decisión ("F-1044: cancelado", "F-2211: folio repetido, se cuenta una vez",
  "Hoteles del Valle: no facturado").
- **La versión final del reporte** que Ana aprobó (con fecha y hora) queda junto al
  registro: si algo cambió entre el borrador y el enviado, queda la diferencia visible.
- **Quién y cada cuánto:** Ana revisa una **muestra cada lunes** antes de aprobar (por eso
  el borrador) y hace una **revisión completa al cierre de cada mes** comparando los
  cuatro registros contra el sistema, con el fin de que el criterio siga apuntando a lo
  que el sistema marca.
- Si se tiene que corregir un dato, se le avisa al vendedor y el registro queda con nota
  "corregido por X el día Y": la trazabilidad completa del error.
