# Sistema Integral de Gestión de Clientes, Servicios y Reservas – Software FJ

Fase 4 – Componente práctico del curso Programación (213023), UNAD. Trabajo individual de Deiby Smith Gómez Luna.

## Descripción

Cuaderno Jupyter en Python que simula la gestión de clientes, servicios (salas, equipos y asesorías) y reservas de Software FJ, aplicando manejo de excepciones en programación orientada a objetos.

## Archivos

- **Sistema_Integral_Gestion_Reservas_Software_FJ_corregido.ipynb**: código completo y 16 operaciones de prueba.
- **sistema_fj.log**: bitácora de eventos y errores generada al ejecutar el cuaderno.
- **Informe Fase 4 - Componente Práctico.pdf**: informe de la actividad.

## Requisitos

Python 3.12 y Jupyter. Solo se usa la librería estándar.

## Cómo ejecutarlo

Abrir el cuaderno y ejecutar *Kernel → Restart & Run All*. Al terminar se crea o actualiza `sistema_fj.log` en la misma carpeta.

## Qué demuestra

Clases abstractas, polimorfismo y encapsulamiento; cinco excepciones personalizadas sobre una base `ExcepcionProyecto`; bloques try/except/else/finally y `raise from`; registro de eventos con `logging`; y un `GestorSistema` con control de registros duplicados.
