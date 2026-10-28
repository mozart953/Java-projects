# Java Projects

This repository contains multiple Java projects created for academic exercises and practical implementations. Each project is a separate NetBeans/Ant project.

## General characteristics

- Language: Java
- Build system: Apache Ant (each project includes `build.xml` and `nbproject/` files)
- IDE: NetBeans (compatible projects)
- Common packages: use of `src/<package>/` structure
- Many GUI projects use Java Swing (`.form` files with NetBeans GUI builder)
- Some projects include compiled classes in `build/` directories

## Prerequisites

- Java Development Kit (JDK) 8+ installed (Java SE)
- Apache Ant (optional if using NetBeans) or NetBeans IDE
- For specific projects: libraries may be referenced (see `nbproject/project.properties`)

## Installation and execution

### Using NetBeans (recommended)

1. Open NetBeans
2. `File > Open Project...` and select the desired project folder
3. Right-click the project and select `Clean and Build`
4. Right-click the project and select `Run` (or run the main class)

### Using Ant from command line

1. Open a terminal in the project directory (the folder containing `build.xml`)
2. Compile: `ant compile`
3. Run: `ant run` (if configured) or run the main class manually with `java -cp build/classes <package>.<MainClass>`

Some projects define a specific main class in `manifest.mf` or `project.properties`.

## Project list

### Basic exercises (console)

| Project | Main class/package | Description |
|---|---|---|
| `Ejercicio1` | `ejercicio1.Main` | Counts digits of a decimal number entered by the user. |
| `Ejercicio2` - `Ejercicio29` | varies (`ejercicioN.*`) | Series of practice exercises covering loops, conditionals, arrays, and basic logic. |
| `EjercicioCero` | varies | Introductory exercise. |
| `Holamundo` | varies | Basic Hello World. |
| `Programa1` | varies | Basic program. |
| `JavaApplication1`, `JavaApplication89` | varies | Generic NetBeans application templates/exercises. |
| `tabla_multiplicar` | varies | Multiplication table. |
| `serie de fibonacci` | varies | Fibonacci series. |
| `NumerosPrimos` | varies | Prime number detection/generation. |
| `Palindromo` | varies | Palindrome checker. |
| `MenorMayornNumeros` | varies | Find min/max among numbers. |

### GUI (Swing) applications

| Project | Main class/package | Description |
|---|---|---|
| `Ventana` | varies | Basic window examples. |
| `Menus` | varies | Menu components in Swing. |
| `Calculadora` variants (e.g. in exercises) | varies | Calculator implementations. |
| `Detodito` | varies | Multi-function GUI tool. |
| `Totitowilson` | varies | GUI application. |
| `Encriptadorwilson` | varies | Encryption/decryption GUI. |
| `Conversor` | varies | Unit/conversion GUI. |
| `Cajero` / `ProyectoCajero` / `ProyectoCajero_Archivos` | varies | ATM/cashier systems with logic and/or file handling. |
| `Warbolgraficow`, `Warboldatos` | varies | Graphical/data projects. |
| `Warbolmdc` | `warbolmdc.Pruebas`, `logica_programa.*` | Tree/logic visualization components (includes `Nodo`, `Arbol`). |
| `Wexpresionesregulares` | `wexpresionesregulares.Exregular` (form) | Regular expressions GUI tool. |
| `AdivinadorWilson` | varies | Number guessing game GUI. |
| `Pacmanwilson` / `Wilsonpacmandos` | `wilsonpacmandos.Wilsonpacmandos` | Pacman-style game (2D rendering, keyboard control, collision logic). |

### Data structures and algorithms

| Project | Main class/package | Description |
|---|---|---|
| `Arbolito` / `Arbol_mdcw` / `Esarbolbinario` / `LienzoArbol` / `Matriz_arbol` | varies | Binary trees, tree visualizations, operations. |
| `Ordenamientoburbujainsercion` / `Ordenamientoswilson` | varies | Sorting algorithms (bubble, insertion, etc.). |
| `AlgoritmosDekker` | varies | Dekker's algorithm (mutual exclusion). |
| `problemaOchoReinas_WilsonPop` | varies | N-Queens (8 queens) solution. |
| `programa banquero 2` / `Programa_Banquero` | varies | Banker's algorithm (deadlock avoidance). |

### Files, I/O and persistence

| Project | Main class/package | Description |
|---|---|---|
| `ExamenFinal_Archivos` | varies | File handling exam project. |
| `ProyectoCajero_Archivos` | varies | Cashier system with file persistence. |
| `Tarea12_Archivos` | varies | File handling task. |
| `Hoja1` | varies | File/data exercises. |

### Compilers and formal languages

| Project | Main class/package | Description |
|---|---|---|
| `EjemploCUP` | `ejemplocup.EjemploCUP` | Example integrating JFlex (lexical analyzer) and CUP (parser generator). Includes `ycalc.cup`, generated `AnalizadorLexico.java`, `AnalizadorSintactico.java`, `sym.java`, and test file `test.txt`. Menu to generate or execute. |
| `AnalizadorLexico` | varies | Lexical analyzer exercises. |
| `Analizadorformulasw` | varies | Formula analyzer. |
| `Ejerciciotokens` / `Separadortokens` / `tokenscompiladores1` | varies | Tokenization exercises. |
| `Automatawilson` | varies | Automata implementations. |

### Databases and connectivity

| Project | Main class/package | Description |
|---|---|---|
| `ConexionSQL` | varies | SQL database connection. |
| `ConexionProlog` / `ConexionProlog_WilsonPop` | varies | Prolog connectivity/integration. |
| `JPAEje1`, `JPAEje2`, `JPAEje3` | varies | JPA (Java Persistence API) exercises. |

### Other projects

| Project | Main class/package | Description |
|---|---|---|
| `Repaso` | varies | Review exercises. |
| `Ejerciciosjava` | varies | Collection of Java exercises. |
| `Proyecto1`, `Proyecto2`, `ProyectoNo2` | varies | General projects. |
| `ProyectoIA_WilsonPop` | varies | Artificial intelligence project. |
| `proyectoSimulacion1_WilsonPop` | varies | Simulation project. |
| `Tetris` | varies | Tetris game. |

## Notes

- Compiled outputs are present in `build/` for many projects.
- Some projects contain `.form` files (NetBeans GUI designer).
- Project names mix Spanish and English.
- Author metadata in headers: Wilson Pop (and variants).
