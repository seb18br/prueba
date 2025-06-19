# Enunciado - Prueba Formativa 4

**Asignatura:** Fundamentos de Programación (FPY1101)  
**Tema:** Listas, Diccionarios, Funciones en Python  
**Duración:** 2 horas  
**Modalidad:** Individual

## Contexto:
El Departamento de Turismo de Chile necesita un sistema para analizar turistas que ingresan al país. Cada turista se registra en un diccionario con la siguiente estructura:

```python
turistas = {
    "001": ["John Doe", "Estados Unidos", "12-01-2024"],
    ...
}
```

## Menú Principal:
1. Turistas por país.
2. Turistas por mes.
3. Eliminar turista.
4. Salir.

Cada opción se implementa como una función externa. Debes programar las siguientes funciones:

### Opción 1: turistas_por_pais(pais)
Muestra los nombres de los turistas del país ingresado.

### Opción 2: turistas_por_mes(mes)
Calcula el porcentaje de turistas que llegaron ese mes.

### Opción 3: eliminar_turista()
Pide un nombre y elimina el turista si existe (independiente de mayúsculas).

### Opción 4: salir del programa
Mostrar "Programa terminado..."

Además, incluye validaciones para el mes y opciones inválidas.

