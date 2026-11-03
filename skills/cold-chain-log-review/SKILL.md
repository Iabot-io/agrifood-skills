---
name: cold-chain-log-review
description: Detectar huecos y desviaciones en registros de temperatura según límites aportados. En IAbot.io, asígnala a un empleado de control documental alimentario y aporta series de temperatura, lotes, equipos y límites aprobados del plan de autocontrol.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Agricultura y alimentación
---

# Revisar registros de cadena de frío

## Uso en IAbot.io

Asigna esta skill a **un empleado de control documental alimentario** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta series de temperatura, lotes, equipos y límites aprobados del plan de autocontrol.

**Ejemplo de encargo:** «Revisa estos registros con los límites del procedimiento y prepara las desviaciones para calidad.»

**Resultado a revisar:** Informe de cobertura y desviaciones con intervalos, lotes y evidencias.

## Cuándo usarla y qué necesita

Detectar huecos y desviaciones en registros de temperatura según límites aportados

Trabaja con series de temperatura, lotes, equipos y límites aprobados del plan de autocontrol. Utiliza registros de lotes, hojas de cálculo y procedimientos aprobados del operador. Los límites de seguridad y decisiones sobre producto corresponden a su sistema de autocontrol.

## Procedimiento

1. Relaciona sensor, equipo, lote, unidad e intervalo de lectura con el registro correspondiente.
2. Verifica continuidad temporal, zona horaria, calibración documentada y valores ausentes.
3. Aplica únicamente límites y reglas del procedimiento aprobado, conservando duración y magnitud de cada desviación.
4. Relaciona desviaciones con aperturas, averías o traslados documentados sin atribuir una causa no comprobada.
5. Entrega los casos al responsable conforme al protocolo vigente; conserva pendientes las decisiones sobre producto.

## Comprobación del resultado

- No se rellenan huecos de datos como temperaturas normales.
- No se inventa un límite genérico para todos los alimentos.
- El análisis no declara aptitud para consumo ni libera un lote.

## Entrega

Informe de cobertura y desviaciones con intervalos, lotes y evidencias.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [AESAN, guía de trazabilidad agroalimentaria](https://www.aesan.gob.es/actualidad/publicaciones-seguridad-alimentaria/guia-para-la-aplicacion-del-sistema-de-trazabilidad-en-la-empresa-agroalimentaria)
- [AESAN, sistema de gestión de seguridad alimentaria](https://aesan.gob.es/seguridad-alimentaria/higiene-alimentos/sgsa)
