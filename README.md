# Diagrama de Bloques - Máquina Expendedora

```mermaid
graph TD;
    A[Macrosistema: Máquina expendedora] --> B[Subsistema de interacción usuario-máquina];
    A --> C[Subsistema de dispensación de productos];
    A --> D[Subsistema de procesamiento de pagos];
    A --> E[Subsistema de gestión y control];

    B --> B1[Interfaz de usuario];
    B --> B2[Comandos de voz];

    C --> C1[Brazo robótico];

    D --> D1[Efectivo];
    D --> D2[Tarjeta de débito/crédito];
    D --> D3[Control de entrega de productos];

    E --> E1[Conexión a internet];
    E --> E2[Aplicación para administradores];
