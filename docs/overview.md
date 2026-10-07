# Aplomo System: contexto y alcance

Aplomo System centraliza información de patios industriales de materiales a granel. Su propósito es dar visibilidad a localización de materiales, movimientos y estados operativos, y mantener trazabilidad del flujo de camiones desde entrada hasta salida.

## Estado documentado

Proyecto industrial contratado · febrero–julio de 2026. Proyecto desarrollado entre febrero y julio de 2026. Obtuvo **3.er lugar general en ExpoIngenierías 2026 del Tecnológico de Monterrey**. Este repositorio reúne la presentación pública del proyecto, su alcance y tecnologías.

Lehi Salvador — liderazgo de un equipo multidisciplinario de siete integrantes. Participación en identificación del problema, lógica operativa, diseño, programación, pruebas y coordinación del proyecto.

Esta documentación amplía la información proporcionada por el responsable del producto. Los criterios y siguientes pasos de la hoja de ruta son propuestas de documentación pública; no compromisos de entrega ni capacidades adicionales implementadas.

## Flujo de referencia

1. Entrada del camión.
2. Carga de material.
3. Báscula.
4. Salida.

El flujo describe el contexto del producto. No define una API, integración ni procedimiento productivo listo para ejecutar.

## Vocabulario

| Concepto | Significado en este contexto |
| --- | --- |
| Patio | Espacio industrial donde se ubican y movilizan materiales a granel. |
| Material | Elemento cuya localización y movimientos necesitan trazabilidad. |
| Movimiento | Cambio operativo que conecta material, ubicación y contexto. |
| Estado operativo | Situación actual que ayuda a interpretar el flujo del patio. |
| Recorrido del camión | Secuencia Entrada → Carga → Báscula → Salida. |

## Límites de publicación

- La presentación pública no contiene código, mapas reales del cliente ni registros de vehículos.
- Se documentan catorce módulos visibles en el sistema desarrollado; no se inventan nombres ni disponibilidad pública de esos módulos.
- QR y NFC forman parte de la solución descrita; sus formatos y credenciales no se publican.

Los sistemas reales y su infraestructura se administran por separado. Este repositorio no contiene instrucciones para acceder a clientes o desplegar aplicaciones.

## Siguiente lectura

[Criterios y hoja de ruta pública](roadmap.md) · [Presentación principal](../README.md)
