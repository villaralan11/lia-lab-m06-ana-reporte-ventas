# Proyecto · Clase 6 · Ana decide qué delegar del reporte semanal de ventas

**LIA Lab · DEV.F · Módulo 6 (Agentes y automatización)**
**Rol: Ana (Ventas de Distribuidora Solmar) · Tiempo estimado: ~30 min**

Caso: Ana consolida a mano las ventas de sus tres vendedores cada lunes y arma el reporte
para el Director Comercial. Le toma casi una hora. Esta entrega define **qué le delega a la
IA** con la plantilla de la lectura 6.1 (disparador, registro, decisión, respuesta y
evidencia), y prueba el flujo con los reportes reales de este lunes.

## Estructura del proyecto

| Archivo | Contenido |
|---|---|
| [01-flujo-cinco-piezas.md](./01-flujo-cinco-piezas.md) | El flujo escrito con las cinco piezas de la plantilla de la lectura 6.1 |
| [02-lo-que-no-delegaria.md](./02-lo-que-no-delegaria.md) | Qué se queda con Ana y por qué |
| [03-prueba-con-los-datos.md](./03-prueba-con-los-datos.md) | La prueba con los tres reportes del lunes: qué entregó el asistente |
| [04-revision.md](./04-revision.md) | Los problemas concretos que encontré y cómo se corregieron |

## Cómo saber si quedó bien (checklist del brief)

- [x] El flujo tiene **las cinco piezas** y cada una contesta su pregunta (el disparador es una hora o evento concreto, no "cuando se pueda").
- [x] El **criterio de decisión está escrito** (qué cuenta como venta) y dice **qué casos pasan a Ana**.
- [x] La respuesta es un **borrador que Ana aprueba** antes de enviarlo al director, y se explica por qué.
- [x] La **evidencia** deja ver qué se excluyó y por qué, quién la revisa y cada cuánto.
- [x] La prueba usó **los datos de este lunes** y la revisión nombra **al menos un problema concreto** y cómo lo corregió.

## Reglas del reporte (del brief)

- Venta = pedido **facturado dentro de la semana que se reporta** (lunes a domingo anterior).
- No cuentan: **cancelados, cotizaciones, folios repetidos**.
- Meta: **$60,000** por vendedor · **$180,000** del equipo.
- El reporte lleva: ventas por vendedor, % de meta, total del equipo y **nota de lo excluido y por qué**.
- Los vendedores mandan ventas antes de las 9:00 del lunes; el reporte sale a las 11:00.
