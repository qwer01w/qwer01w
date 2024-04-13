## Diagrama de Bloques - Sistema de Venta Automatizada

```mermaid
graph TD;
    A[Macrosistema: Sistema de venta automatizada] --> B[Subsistema de interacción usuario-máquina];
    A --> C[Subsistema de dispensación de productos];
    A --> D[Subsistema de procesamiento de pagos];
    A --> E[Subsistema de gestión y control];

    B --> B1[Interfaz de usuario];
    B --> B2[Comandos de voz];
    B --> B3[Pantalla táctil];

    C --> C1[Inventario de productos];
    C --> C2[Brazo robótico];

    D --> D1[Sistema de pago (efectivo, tarjeta de débito/crédito)];

    E --> E1[Microcontrolador];
    E --> E2[Sensores];
    E --> E3[Conexión a internet];
    E --> E4[Aplicación para administradores];
