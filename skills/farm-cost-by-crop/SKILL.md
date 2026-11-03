---
name: farm-cost-by-crop
description: Distribuir costes de una explotación por cultivo y campaña con criterios de reparto trazables. En IAbot.io, asígnala a un empleado de gestión de explotaciones y aporta parcelas, campañas, labores, consumos, costes y producción registrada.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Agricultura y alimentación
---

# Costes por cultivo y campaña

## Uso en IAbot.io

Asigna esta skill a **un empleado de gestión de explotaciones** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta parcelas, campañas, labores, consumos, costes y producción registrada.

**Ejemplo de encargo:** «Calcula costes por hectárea y kilogramo por cultivo, separando costes directos y repartidos.»

**Resultado a revisar:** Cuenta de costes por cultivo con criterios, unidades y datos pendientes.

## Cuándo usarla y qué necesita

Distribuir costes de una explotación por cultivo y campaña con criterios de reparto trazables

Trabaja con parcelas, campañas, labores, consumos, costes y producción registrada. Utiliza registros de lotes, hojas de cálculo y procedimientos aprobados del operador. Los límites de seguridad y decisiones sobre producto corresponden a su sistema de autocontrol.

## Procedimiento

1. Fija parcelas, superficie, cultivo y periodo de campaña; evita mezclar campañas superpuestas.
2. Asigna costes directos a las labores o parcelas identificadas, manteniendo facturas y consumos originales.
3. Reparte costes comunes con el criterio acordado y muestra el efecto de otros criterios razonables si es relevante.
4. Calcula indicadores por hectárea y por producción efectivamente registrada, separando previsión y cosecha real.
5. Concilia el total asignado con la contabilidad de origen y explica exclusiones o diferencias.

## Comprobación del resultado

- No se divide por una producción inexistente o prevista sin indicarlo.
- Las superficies corresponden al mismo alcance del coste.
- El reparto de costes comunes queda reproducible.

## Entrega

Cuenta de costes por cultivo con criterios, unidades y datos pendientes.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [AESAN, guía de trazabilidad agroalimentaria](https://www.aesan.gob.es/actualidad/publicaciones-seguridad-alimentaria/guia-para-la-aplicacion-del-sistema-de-trazabilidad-en-la-empresa-agroalimentaria)
- [AESAN, sistema de gestión de seguridad alimentaria](https://aesan.gob.es/seguridad-alimentaria/higiene-alimentos/sgsa)
