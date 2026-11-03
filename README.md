# Agricultura y alimentación · Skills para empleados IA de IAbot.io

Trazabilidad, producción, costes de campaña y revisión de registros de empresas agroalimentarias.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Reconstruir la trazabilidad de lotes](skills/food-lot-traceability/SKILL.md) | un empleado de trazabilidad alimentaria | Mapa de lotes y movimientos con balance y vínculos ausentes. |
| [Revisar documentación de proveedores alimentarios](skills/food-supplier-document-review/SKILL.md) | un empleado de calidad de proveedores | Matriz de homologación documental con cobertura y pendientes. |
| [Revisar registros de cadena de frío](skills/cold-chain-log-review/SKILL.md) | un empleado de control documental alimentario | Informe de cobertura y desviaciones con intervalos, lotes y evidencias. |
| [Preparar evidencias para retirada de producto](skills/food-recall-evidence-pack/SKILL.md) | un empleado de coordinación de calidad | Expediente trazable de producto, existencias, destinatarios y comunicaciones preparadas. |
| [Costes por cultivo y campaña](skills/farm-cost-by-crop/SKILL.md) | un empleado de gestión de explotaciones | Cuenta de costes por cultivo con criterios, unidades y datos pendientes. |
| [Rendimientos y mermas de producción](skills/food-production-yield/SKILL.md) | un empleado de control de producción alimentaria | Balance de masa o unidades por lote y registro de desviaciones. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/agrifood-skills --list
npx skills add Iabot-io/agrifood-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Reconstruir la trazabilidad de lotes:** «Reconstruye la trazabilidad del lote indicado y muestra qué vínculos o cantidades siguen sin justificar.»
- **Revisar documentación de proveedores alimentarios:** «Revisa estas fichas de proveedor y señala documentos caducados o referencias que no coinciden.»
- **Revisar registros de cadena de frío:** «Revisa estos registros con los límites del procedimiento y prepara las desviaciones para calidad.»

## Herramientas y límites

Utiliza registros de lotes, hojas de cálculo y procedimientos aprobados del operador. Los límites de seguridad y decisiones sobre producto corresponden a su sistema de autocontrol.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [AESAN, guía de trazabilidad agroalimentaria](https://www.aesan.gob.es/actualidad/publicaciones-seguridad-alimentaria/guia-para-la-aplicacion-del-sistema-de-trazabilidad-en-la-empresa-agroalimentaria)
- [AESAN, sistema de gestión de seguridad alimentaria](https://aesan.gob.es/seguridad-alimentaria/higiene-alimentos/sgsa)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
