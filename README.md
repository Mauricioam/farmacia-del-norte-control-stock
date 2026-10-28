# Control de stock para Farmacia del Norte

## Descripción del proyecto

Se busca satisfacer la necesidad de tener un control de stock, de entradas y salidas. Además, se integra la exportación de datos en CSV, para identificar patrones de compra y planificar futuras compras en fechas similares.

## Objetivo

Desarrollar e implementar un sistema informático de control de inventario de perfumería para Farmacia del Norte, que permita registrar ingresos y ventas y generar reportes para optimizar las compras futuras.

## Integrante

- Mauricio Agustín Murdoch

## Docentes

- **Docente titular:** Prof. Gabriela Martínez
- **Docente tutor:** Pablo García

## Declaración de uso de IA

**Herramienta utilizada:** Claude (Anthropic).

### Resumen de prompts y correcciones manuales

| Prompt (resumen) | Corrección manual |
|---|---|
| Guía conceptual de la entrega, proceso de carga de artículos por escrito y cuatro historias de usuario. | Se agregó una decisión al verificar la factura: si es incorrecta, se rechaza el pedido y la acción finaliza. |
| Generar el diagrama del proceso de carga en draw.io para exportarlo al documento. | Si el empleado no confirma el ingreso, el proceso termina en un evento de fin propio ("Ingreso cancelado") en lugar de volver a corregir. |
| Verificar si es correcto que dos flujos converjan en "Validar datos". | La convergencia se reemplzó manualmente en los diagramas usando objeto decisión genérica. |
| Definir por escrito los procesos de venta y de generación de reporte a partir del objetivo general y de los TP 1, 2 y 3. | Se removió el stock mínimo y la alerta de reposición, y no se incluyó la anulación de venta: el sistema propone un MVP sencillo. |
| Aplicar las decisiones de alcance sobre cobro, ítems y generación de reportes. | El cobro se registra solo como total, sin medio de pago, porque no hay facturación. Se mantienen varios ítems por venta. Los reportes los genera solo el propietario. |
| Revisión del proceso de generación de reporte. | Se removió el paso de mostrar el reporte por pantalla: no es una funcionalidad declarada, el sistema solo exporta en CSV. |
| Generar un único archivo draw.io con los tres procesos. | Se reemplazaron las imágenes PNG por versiones de mayor resolución, porque no se veían correctamente. |
| Pasos para crear rama, hacer commit, abrir el Pull Request y borrar archivos en GitHub. | Rama, commit y Pull Request realizados por el autor. |


### Responsabilidad intelectual

Todo contenido, fué revisado y modificado manualmente en los casos necesarios. Se utilizó AI para realizar los diagramas y consultas respecto al uso de Github. Asi también se utiliza para el la modificación de formatos de archivos.
Todo contenido está bajo mi responsabilidad. 
