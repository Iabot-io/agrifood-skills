---
name: food-production-yield
description: Reconciliar rendimientos de fabricación distinguiendo merma registrada, producto y diferencias de balance. En IAbot.io, asígnala a un empleado de control de producción alimentaria y aporta partes de fabricación, entradas, salidas, mermas y unidades por lote.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Agricultura y alimentación
---

# Rendimientos y mermas de producción

## Uso en IAbot.io

Asigna esta skill a **un empleado de control de producción alimentaria** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta partes de fabricación, entradas, salidas, mermas y unidades por lote.

**Ejemplo de encargo:** «Revisa el balance de estos lotes y separa merma documentada de diferencia sin explicación.»

**Resultado a revisar:** Balance de masa o unidades por lote y registro de desviaciones.

## Cuándo usarla y qué necesita

Reconciliar rendimientos de fabricación distinguiendo merma registrada, producto y diferencias de balance

Trabaja con partes de fabricación, entradas, salidas, mermas y unidades por lote. Utiliza registros de lotes, hojas de cálculo y procedimientos aprobados del operador. Los límites de seguridad y decisiones sobre producto corresponden a su sistema de autocontrol.

## Procedimiento

1. Identifica lote, receta o proceso, unidad y periodo de cada parte de fabricación.
2. Normaliza cantidades y conserva conversiones entre peso, volumen y unidades solo si están justificadas.
3. Reconcilia entradas con producto terminado, subproductos, reproceso y mermas registradas.
4. Calcula rendimiento con la misma base de medida y compara solo procesos equivalentes.
5. Explica diferencias documentadas y prepara investigación de las restantes, sin ajustar cifras para cerrar el balance.

## Comprobación del resultado

- No se cuenta el reproceso simultáneamente como entrada nueva y producción final.
- Las conversiones de volumen a masa tienen factor y fuente.
- El rendimiento no se presenta como prueba de seguridad alimentaria.

## Entrega

Balance de masa o unidades por lote y registro de desviaciones.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [AESAN, guía de trazabilidad agroalimentaria](https://www.aesan.gob.es/actualidad/publicaciones-seguridad-alimentaria/guia-para-la-aplicacion-del-sistema-de-trazabilidad-en-la-empresa-agroalimentaria)
- [AESAN, sistema de gestión de seguridad alimentaria](https://aesan.gob.es/seguridad-alimentaria/higiene-alimentos/sgsa)
