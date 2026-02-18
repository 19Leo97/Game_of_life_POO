# Juego de la Vida (Conway's Game of Life)

Este proyecto es una implementación del famoso autómata celular "Juego de la Vida" de John Conway, desarrollado como un taller para la materia de **Programación Orientada a Objetos**.

El programa permite simular la evolución de células en una cuadrícula basándose en reglas de supervivencia y reproducción, ofreciendo una interfaz interactiva para manipular el estado de la simulación en tiempo real.

---

## 🚀 Requisitos e Instalación

* **Software**: Es necesario contar con [Processing](https://processing.org/) instalado.
* **Modo**: El programa debe ejecutarse utilizando el **Modo Python** (`Python Mode`) dentro de Processing.

## 🎮 Controles de la Simulación

Puedes interactuar con la grilla y controlar la ejecución mediante las siguientes teclas y acciones de ratón:

### Interacción Manual
* **Click Izquierdo**: Permite matar o revivir una célula individualmente al hacer clic sobre ella.

### Ejecución y Velocidad
* **Tecla Espacio**: Pausa o reanuda la simulación (Play/Pause).
* **Flecha Izquierda**: Disminuye la velocidad de la simulación.
* **Flecha Derecha**: Aumenta la velocidad de la simulación.

### Generación de Patrones
El programa permite cargar configuraciones iniciales presionando las teclas numéricas:

| Tecla | Acción / Patrón |
| :---: | :--- |
| **0** | **Reset**: Limpia la grilla (extinción total). |
| **1** | **Random**: Genera células vivas de forma aleatoria. |
| **2** | **Quad**: Oscilador de periodo 2. |
| **3** | **Undecapole**: Patrón oscilador. |
| **4** | **Achim's p11**: Oscilador de periodo 11. |
| **5** | **295P5H1V1**: Nave espacial diagonal. |
| **6** | **Barge**: Nave espacial (*Spaceship*). |
| **7** | **83P7H1V1**: Nave espacial de periodo 7. |
| **8** | **64P2H1V0**: La nave espacial de periodo 2 más pequeña. |
| **9** | **T-nosed p6**: Oscilador de periodo 6. |

## 🛠️ Detalles Técnicos

* **Reglas**: Se aplican las reglas estándar de Conway (B3/S23).
* **Dimensiones**: Configurado para una ventana de 1350x690 píxeles con celdas de 12x12.
* **Estructura**: El código principal se encuentra en `GameOfLife.pyde` y utiliza archivos `.cells.txt` para cargar las estructuras complejas.

---
*Este proyecto forma parte del repositorio de proyectos de POO.*
