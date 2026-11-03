---
name: food-lot-traceability
description: Relacionar lotes de entrada, transformaciones y destinatarios conservando cantidades y fechas. En IAbot.io, asígnala a un empleado de trazabilidad alimentaria y aporta recepciones, transformaciones, lotes, existencias y expediciones.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Agricultura y alimentación
---

# Reconstruir la trazabilidad de lotes

## Uso en IAbot.io

Asigna esta skill a **un empleado de trazabilidad alimentaria** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta recepciones, transformaciones, lotes, existencias y expediciones.

**Ejemplo de encargo:** «Reconstruye la trazabilidad del lote indicado y muestra qué vínculos o cantidades siguen sin justificar.»

**Resultado a revisar:** Mapa de lotes y movimientos con balance y vínculos ausentes.

## Cuándo usarla y qué necesita

Relacionar lotes de entrada, transformaciones y destinatarios conservando cantidades y fechas

Trabaja con recepciones, transformaciones, lotes, existencias y expediciones. Utiliza registros de lotes, hojas de cálculo y procedimientos aprobados del operador. Los límites de seguridad y decisiones sobre producto corresponden a su sistema de autocontrol.

## Procedimiento

1. Identifica proveedor, lote y cantidad de cada entrada sin sustituir códigos originales.
2. Relaciona divisiones, mezclas y transformaciones con los lotes de salida y registros de proceso. Distingue cantidad recibida, almacenada y consumida por cada origen; recibir un lote no significa consumirlo por completo.
3. Vincula existencias y expediciones a destinatarios y fechas, conservando devoluciones y rectificaciones.
4. Revisa balance de cantidades, mermas justificadas y movimientos sin vínculo.
5. Entrega la trazabilidad hacia atrás y adelante con limitaciones explícitas para el responsable.

## Comprobación del resultado

- Los lotes mezclados no pierden sus entradas de origen.
- Las mermas no se utilizan para ocultar diferencias sin justificar.
- Trazabilidad completa no se confunde con seguridad del producto.

## Entrega

Mapa de lotes y movimientos con balance y vínculos ausentes.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [AESAN, guía de trazabilidad agroalimentaria](https://www.aesan.gob.es/actualidad/publicaciones-seguridad-alimentaria/guia-para-la-aplicacion-del-sistema-de-trazabilidad-en-la-empresa-agroalimentaria)
- [AESAN, sistema de gestión de seguridad alimentaria](https://aesan.gob.es/seguridad-alimentaria/higiene-alimentos/sgsa)
