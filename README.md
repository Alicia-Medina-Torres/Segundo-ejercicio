# Segundo-ejercicio

# Pokédex Interactiva con Sistema de Batallas

Este proyecto simula una Pokédex interactiva que permite:
1.   Gestionar Pokémon (agregar, modificar, eliminar).
2.   Simular batallas entre Pokémon.
3.   Visualizar estadísticas detalladas de cada Pokémon.

# Estructura del Proyecto

    |pokedex/  
    │  
    ├── data/  
    │   └── pokemon.csv          # Base de datos de Pokémon (requerido)  
    │  
    ├── main.py                  # Programa principal  
    └── README.md                # Documentación  

# Requisitos

1. Python 3.8+
2. Archivo CSV inicial:
3. Debe contener al menos las columnas:

        pokedex_number, name, type_1, type_2, hp, attack, defense, sp_attack, sp_defense, speed.

#  Cómo Ejecutarlo

1. Clonar/descargar el repositorio y colocar el archivo pokemon.csv en data/.
2. Instalar Python (si no lo tienes).
3. Ejecutar el programa:

        python main.py

# Funcionalidades

Menú Principal
Opción	Acción
1	Ver todos los Pokémon (paginados de 50 en 50).
2	Agregar un nuevo Pokémon (autogenera el número de Pokédex).
3	Modificar un Pokémon existente (actualiza stats).
4	Eliminar un Pokémon por su número de Pokédex.
5	Simular una batalla entre dos Pokémon.
6	Mostrar tarjeta detallada de un Pokémon.
7	Salir del programa.


# Sistema de Batallas

1. Mecánica:

El Pokémon con mayor velocidad ataca primero.

Gana el que tenga mayor ataque que la defensa del rival.

2. Efectos visuales:

Animación con arte ASCII y puntos de carga (10 segundos).
