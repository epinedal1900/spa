# Algoritmo de Posición Solar (SPA)

## Descripción General

Este proyecto implementa un Algoritmo de Posición Solar (SPA) para calcular la posición del sol en el cielo para cualquier momento y ubicación dados. Se basa en la implementación en C del documento "Solar Position Algorithm for Solar Radiation Applications", disponible en este [enlace](https://www.nrel.gov/docs/fy08osti/34302.pdf). Esta implementación se ha adaptado del código proporcionado por la Alliance for Sustainable Energy, que se encuentra en [https://midcdmz.nrel.gov/spa/](https://midcdmz.nrel.gov/spa/).

## Primeros Pasos

### Prerrequisitos

- Compilador de C (se recomienda GCC)
- Conocimientos básicos de programación en C y conceptos astronómicos

### Instalación

1. **Clonar el Repositorio**

   ```
   git clone https://github.com/epinedal1900/SPA.git
   ```

2. **Navegar al Directorio del Proyecto**

   ```
   cd src
   ```

3. **Compilar el Código Fuente**
   ```
   gcc -o spa main.c spa.c utilities.c -lm
   ```
   Reemplaza `main.c`, `spa.c`, `utilities.c` con los nombres reales de los archivos fuente.

### Ejecución del Programa

- Después de compilar, ejecutar el programa:
  ```
  ./spa
  ```

## Estructura del Proyecto

- `spa.c` - Funciones centrales del SPA que implementan los cálculos de la posición solar.
- `utilities.c` - Funciones de utilidad para operaciones matemáticas.
- `spa.h` - Archivo de encabezado que contiene prototipos de funciones y constantes.
- `main.c` - Implementación de ejemplo que utiliza el SPA.
- `tests/` - Pruebas unitarias e integradas para el SPA.

## Colaboradores

- **Emmanuel Pineda León** - _Trabajo Inicial_ - [github](https://github.com/epinedal1900)
