# Sistema de Control de Acceso con Flip-Flops D

## Descripción

Este proyecto consiste en el diseño e implementación de un sistema digital secuencial para control de acceso mediante una contraseña binaria de 4 bits.

El sistema fue desarrollado utilizando flip-flops tipo D, compuertas lógicas y mapas de Karnaugh en Logisim Evolution.

La secuencia correcta es:

1010

Cuando el usuario introduce correctamente la secuencia, el sistema llega al estado de acceso concedido.

---

# Objetivos

- Diseñar un sistema secuencial síncrono.
- Implementar lógica combinacional con compuertas.
- Utilizar flip-flops tipo D para almacenamiento de estados.
- Aplicar mapas de Karnaugh para simplificación lógica.
- Simular el sistema en Logisim Evolution.

---

# Tecnologías Utilizadas

- Logisim Evolution
- Flip-Flops tipo D
- Compuertas AND, OR y NOT
- Diseño secuencial síncrono

---

# Diagrama de Estados

```text
S0 --1--> S1
S0 --0--> ERROR

S1 --0--> S2
S1 --1--> ERROR

S2 --1--> S3
S2 --0--> ERROR

S3 --0--> S4
S3 --1--> ERROR
