## Diagrama de Bloques - Máquina Expendedora

```mermaid
graph TD;
    A[Macrosistema: Máquina expendedora] --> B[Subsistema de interacción usuario-máquina];
    A --> C[Subsistema de dispensación de productos];
    A --> D[Subsistema de procesamiento de pagos];
    A --> E[Subsistema de gestión y control];

    B --> B1[Interfaz de usuario];
    B --> B2[Comandos de voz];
    B --> B3[Pantalla táctil];

    C --> C1[Inventario de productos];
    C --> C2[Brazo robótico];

    D --> D1[Sistema de pago (efectivo, tarjeta de débito/crédito)];

    E --> E1[Aplicación para administradores];
    E --> E2[Conexión a internet];
