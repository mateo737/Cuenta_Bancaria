# Sistema Bancario Simple en Python

Este es un programa básico en Python que simula un sistema bancario simple. Los usuarios pueden crear un cliente, realizar depósitos y retiros. El sistema está diseñado con una clase `Persona` y una clase derivada `Cliente`.

## Clases

### Persona

- Representa a una persona genérica con un nombre y un apellido.

### Cliente

- Hereda de `Persona`.
- Representa a un cliente con atributos adicionales como número de cuenta y saldo.
- Permite realizar transacciones de depósito y retiro.

## Uso

1. Ejecute el programa ejecutando la función `inicio()`.
2. Ingrese la información requerida para crear un nuevo cliente.
3. Elija una de las siguientes opciones:
    - **D: Depósito**
        - Ingrese la cantidad a depositar.
    - **R: Retiro**
        - Ingrese la cantidad a retirar.
    - **S: Salir**
        - Salga del programa.

## Mejoras

- **Manejo de Errores:**
    - El programa ahora incluye un manejo básico de errores para la entrada del usuario.

- **Uso de Float para Saldos:**
    - Los saldos ahora admiten cantidades fraccionarias.

- **Interacción Mejorada con el Usuario:**
    - Se proporcionan mensajes más claros para guiar al usuario.

- **Nomenclatura Consistente:**
    - Se ha mejorado la consistencia en la nomenclatura.

- **Manejo del Número de Cuenta como Cadena:**
    - El número de cuenta se almacena como una cadena.

## Cómo Ejecutar

1. Asegúrese de tener Python instalado.
2. Ejecute el programa ejecutando el script:

    ```bash
    python banking_system.py
    ```
