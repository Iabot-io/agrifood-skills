---
name: food-supplier-document-review
description: Comparar la documentación de proveedores alimentarios con requisitos de homologación definidos. En IAbot.io, asígnala a un empleado de calidad de proveedores y aporta ficha del proveedor, especificaciones, documentos y requisitos de homologación.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Agricultura y alimentación
---

# Revisar documentación de proveedores alimentarios

## Uso en IAbot.io

Asigna esta skill a **un empleado de calidad de proveedores** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta ficha del proveedor, especificaciones, documentos y requisitos de homologación.

**Ejemplo de encargo:** «Revisa estas fichas de proveedor y señala documentos caducados o referencias que no coinciden.»

**Resultado a revisar:** Matriz de homologación documental con cobertura y pendientes.

## Cuándo usarla y qué necesita

Comparar la documentación de proveedores alimentarios con requisitos de homologación definidos

Trabaja con ficha del proveedor, especificaciones, documentos y requisitos de homologación. Utiliza registros de lotes, hojas de cálculo y procedimientos aprobados del operador. Los límites de seguridad y decisiones sobre producto corresponden a su sistema de autocontrol.

## Procedimiento

1. Identifica proveedor, establecimiento, productos y alcance real de los documentos.
2. Extrae requisitos de homologación del procedimiento aportado sin inventar certificados obligatorios.
3. Comprueba vigencia, titular, producto y alcance de cada evidencia, distinguiendo declaración y verificación.
4. Registra ausencias y contradicciones con preguntas concretas al proveedor.
5. Prepara un expediente para la decisión del responsable de calidad, conservando restricciones de uso.

## Comprobación del resultado

- Un certificado de otro centro no cubre automáticamente al proveedor revisado.
- Las referencias de producto coinciden con las suministradas.
- La revisión documental no aprueba por sí sola el proveedor.

## Entrega

Matriz de homologación documental con cobertura y pendientes.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [AESAN, guía de trazabilidad agroalimentaria](https://www.aesan.gob.es/actualidad/publicaciones-seguridad-alimentaria/guia-para-la-aplicacion-del-sistema-de-trazabilidad-en-la-empresa-agroalimentaria)
- [AESAN, sistema de gestión de seguridad alimentaria](https://aesan.gob.es/seguridad-alimentaria/higiene-alimentos/sgsa)
