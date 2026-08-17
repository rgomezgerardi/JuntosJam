# Let's Save Marco

<img width="315" height="250" alt="image" src="https://github.com/user-attachments/assets/1a3f831f-e2b3-4f77-b8bd-0be02fd454f0" />

Proyecto desarrollado para la **Juntos Game Jam**.

## Tecnologías

- **Unreal Engine 5.8**

## Arquitectura

Este proyecto sigue el patrón **Vertical Slice Architecture**, que organiza el código en módulos independientes para facilitar el desarrollo y mantenimiento.

## Estructura de Carpetas

- **Core/**: Contiene los sistemas fundamentales del juego (Game Instance, Game Mode, Pawn base, etc.) y la lógica central que no pertenece a una característica específica.

- **Features/**: Módulos independientes que implementan funcionalidades específicas del juego (ej. movimiento, combate, UI, etc.). Cada feature es autocontenido y puede desarrollarse y probarse de forma aislada.

- **Shared/**: Contiene código y recursos compartidos entre múltiples módulos (utilidades, helpers, interfaces comunes, assets genéricos, etc.).
