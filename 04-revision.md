# 04 · Revisión: qué comparé y qué corregí

> Dos o tres líneas por hallazgo. Los concretos de esta semana: **los problemas estaban en
> los reportes de los vendedores y en la salida del asistente**.

---

## 1 · Los tres totales declarados iban mal contra el criterio (el hallazgo grande)

**Qué comparé:** los totales que cada vendedor declaró contra la suma de las líneas apenas
apliqué el criterio. **Beto** declaró $68,100, que incluye el F-1044 **cancelado**
($9,500). **Carla** declaró $91,800: su folio **F-2211 está dos veces** (lo captura del
chat lo dice ella misma: "lo capturé dos veces porque me pidieron copia"). **Mauricio**
declaró $74,700 en "miles", que suma los $33,000 de **Hoteles del Valle, "En proceso de
cierre"**, que todavía no está facturado. **Corrección:** el borrador salió con los totales
del criterio ($58,600 / $69,300 / $41,700, equipo $169,600 = 94.2 % de la meta) y las tres
banderas para Ana de verificación en el sistema antes de mandar.

## 2 · El borrador del asistente repitió el dato "tal cual" de Beto

**Qué encontré:** en su primer borrador, el asistente extrajo las cifras de la columna
"Total de la semana" de cada correo — no aplicó el criterio por folio — y por eso también
iba a marcar el $68,100 (con el cancelado adentro) y el $91,800 de Carla (con el doble).
**Corrección:** le pedí que **trabajara folio por folio con el registro y el criterio
(GUARDADOS)**, no con la línea de total de cada correo; después se calcularon de nuevo
con el criterio; la evidencia quedó con la decisión por folio.

## 3 · La columna de % de meta de una excluyente (Carla)

**Qué encontré:** con el total declarado de Carla (91,800), su % de meta hubiera salido 153 % — el doble folio alarga otro número de decisiones del director. **Corrección:** se recalculó: 69,300 / 60,000 = **115.5%**. La bandera "dígito no validado" quedó en el registro del folio hasta que Ana
confirme las facturas en el sistema.

## 4 · Una práctica de Mauricio (nuevos datos y "sin folios")

**Qué encontré:** el reporte de Mauricio llegó **sin folios** y **en "miles de pesos"** (el único de los tres sin folios). y para el criterio no es suficientemente verificable. **Corrección:** el agente normalizó (miles → pesos: 24.5 → $24,500) y cada línea del registro lleva
"por confirmar en el sistema" hasta que Ana cruce las facturas. Pedir folios a los tres (formato común) es el cambio para la próxima semana.

## 5 · El porcentaje de la meta quedó sin base

**Qué encontré:** la "meta" por vendedor ($60,000) y del equipo ($180,000) venía en el
brief, no en el correo de ningún vendedor. En el primer borrador, los porcentajes estaban sin su base. **Corrección:** quedó explícito en
el registro: % meta = total del criterio / $60,000 por vendedor; % equipo = total /
$180,000.

## Qué concluí en una línea

Ni los vendedores ni la IA comprueban la salida por solos: la salida correcta salió de
**recalcular con el criterio, folio por folio, y pedir verificación en el sistema** de
lo que quedó dudoso. De esa prueba salió la versión definitiva del flujo.
