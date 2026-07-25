# Juntos Game Jam

Proyecto desarrollado para la **Juntos Game Jam**.

## Tecnologías

- **Unreal Engine 5.8**

## Arquitectura

Este proyecto sigue el patrón **Vertical Slice Architecture**, que organiza el código en módulos independientes para facilitar el desarrollo y mantenimiento.

## Estructura de Carpetas

- **Core/**: Contiene los sistemas fundamentales del juego (Game Instance, Game Mode, Pawn base, etc.) y la lógica central que no pertenece a una característica específica.

- **Features/**: Módulos independientes que implementan funcionalidades específicas del juego (ej. movimiento, combate, UI, etc.). Cada feature es autocontenido y puede desarrollarse y probarse de forma aislada.

- **Shared/**: Contiene código y recursos compartidos entre múltiples módulos (utilidades, helpers, interfaces comunes, assets genéricos, etc.).
