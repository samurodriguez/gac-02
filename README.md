# Clase 2 - Github Actions

## Ejercicios

### 1. Eventos

Crear un workflow que muestre la fecha por consola y que se ejecute:

- cada 2 minutos
- cuando se haga push en cualquier rama que no sea main

### 2. Matrix

Crear un workflow que se ejecute con 3 sistemas operativos diferentes y con 3 versiones diferentes de node o java (lo que prefiráis).

- Extra: Hacer que solo deje ejecutar 2 variantes al mismo tiempo.
- Extra: Si alguna variante falla, cancelar el resto de ejecuciones. Testead que funciona forzando que el job falle en una versión específica.
- Extra: Hacer una exclusión para que una variante en específico no se ejecute (por ejemplo macos-latest con node/java v.X).
