<!--
   ⬡ ⬡ ⬡  README de perfil — dannn-36  ⬡ ⬡ ⬡
   Si estás leyendo el código fuente de este README: hola, colega curioso. 👽
-->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=A277FF&center=true&vCenter=true&width=650&lines=%3E+Hola%2C+soy+Daniel+Villamil+%F0%9F%91%BD;%3E+C%2B%2B+%7C+Embebidos+%7C+Alto+rendimiento;%3E+Escribo+motores%2C+compiladores+y+firmware;%3E+Assembly+no+me+da+miedo+(bueno%2C+un+poco);%3E+%E4%BD%A0%E5%A5%BD%EF%BC%81+(HSK+1+desbloqueado)" alt="Typing SVG"/>
</p>

<p align="center">
  <b>Estudiante de Ingeniería de Sistemas · Universidad El Bosque</b> · Bogotá, Colombia 🇨🇴<br/>
  C++ · sistemas embebidos · software de alto rendimiento
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/daniel-villamil-611146342"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:josdanvidu@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=dannn-36&color=blueviolet&style=for-the-badge&label=VISITANTES" alt="Visitas"/>
  <!-- Si subes tu CV al repo (ej. CV_Daniel_Villamil.pdf), descomenta esta línea:
  <a href="CV_Daniel_Villamil.pdf"><img src="https://img.shields.io/badge/CV-000000?style=for-the-badge&logo=readdotcv&logoColor=white" alt="CV"/></a>
  -->
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-Compila_sin_warnings-00C853?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/segfaults_este_mes-sin_comentarios-FF5252?style=flat-square"/>
  <img src="https://img.shields.io/badge/caf%C3%A9-colombiano_%E2%98%95-6F4E37?style=flat-square"/>
  <img src="https://img.shields.io/badge/-%E2%AC%A1_hexagon_enjoyer-FFB300?style=flat-square"/>
</p>

```
        ⬡ ⬡ ⬡ ⬡ ⬡
       ⬡ ⬡ ⬡ ⬡ ⬡ ⬡        H O N E Y C O M B
        ⬡ ⬡ ⬢ ⬡ ⬡          E N G I N E
       ⬡ ⬡ ⬡ ⬡ ⬡ ⬡        runtime C++ · editor Electron · 2.5D
        ⬡ ⬡ ⬡ ⬡ ⬡
```

---

## 🧑‍💻 `$ whoami`

```cpp
#include <string_view>
#include <array>

struct Daniel {
    std::string_view ubicacion   = "Bogotá, Colombia 🇨🇴";
    std::string_view universidad = "Universidad El Bosque — Ing. de Sistemas (2027)";
    std::string_view trabajo     = "Ingeniero de Software @ TechIQ SAS";

    std::array<std::string_view, 5> stack {
        "C++20", "C", "Python", "C#", "Assembly x86/ARM"
    };

    std::array<std::string_view, 4> obsesiones {
        "motores de juego", "compiladores", "edge AI", "exprimir cada byte de RAM"
    };

    std::array<std::string_view, 3> idiomas {
        "Español (nativo)", "English (advanced)", "中文 (HSK 1)"
    };

    [[nodiscard]] constexpr bool es_legendario() const noexcept { return true; }
};

static_assert(Daniel{}.es_legendario(), "imposible, revisa tu compilador");
```

- 🏭 Mi software de órdenes de servicio e inspección vehicular corre en **18 Centros de Diagnóstico Automotor**.
- 🐝 Estoy construyendo **HoneyComb Engine**, un motor isométrico 2.5D con runtime nativo en C++.
- 🔌 Hago que redes neuronales quepan en un **ESP32-CAM**, donde cada kilobyte cuenta.
- 🧠 Escribí un analizador estático que te dice cuánta energía gasta tu código **antes** de ejecutarlo.

---

## 🏆 Logros desbloqueados

| | Logro | Cómo se consiguió |
|:-:|---|---|
| 🏭 | **En producción de verdad** | 18 empresas usan un sistema que diseñé y desplegué |
| 🔐 | **Guardián de licencias** | 60+ licencias protegidas con huella de hardware y validación criptográfica |
| 🧠 | **Cerebro de bolsillo** | CNN cuantizada corriendo en tiempo real en una Raspberry Pi 5 (80 % de precisión) |
| 🔬 | **Susurrador de microcontroladores** | Visión por computador en ESP32-CAM con C++ y Assembly |
| 🌳 | **Parser de 5 lenguajes** | Gramáticas ANTLR completas para Python, C, Java, Go y C# en una sola herramienta |
| 🎮 | **Constructor de mundos** | Motor de juegos propio, con editor y runtime separados |
| 🀄 | **你好世界** | HSK 1 en chino mandarín |

---

## ⚙️ Hola mundo, a la antigua

```nasm
; x86-64 Linux — porque printf es para los que tienen prisa
section .data
    msg db "Hola, soy Daniel. Bienvenido a mi perfil.", 10
    len equ $ - msg

section .text
    global _start
_start:
    mov rax, 1          ; sys_write
    mov rdi, 1          ; stdout
    mov rsi, msg
    mov rdx, len
    syscall

    mov rax, 60         ; sys_exit
    xor rdi, rdi        ; return 0, todo salió bien (esta vez)
    syscall
```

---

## 💼 Experiencia

**Ingeniero de Software (Freelance) — TechIQ SAS** · Bogotá · *Ene 2026 – Presente*
`ASP.NET Core` `Angular` `SQL`
- Diseñé y desplegué un sistema multiplataforma (web y móvil) de órdenes de servicio e inspección vehicular usado por **18 Centros de Diagnóstico Automotor**, que reemplazó el seguimiento en papel.
- Construí una plataforma de **licenciamiento remoto** con identificación de hardware y validación criptográfica, que protege el software de inspección en **60+ licencias activas**.

---

## 🛠️ Inventario

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,python,cs,java,ts,mysql&perline=7" alt="Lenguajes"/><br/>
  <img src="https://skillicons.dev/icons?i=linux,raspberrypi,tensorflow,dotnet,angular,electron,docker,git&perline=8" alt="Plataformas y herramientas"/>
</p>

| Área | Herramientas |
|---|---|
| **Lenguajes** | C++17/20, C, Python, C#, Java, TypeScript, SQL, Assembly (x86/ARM) |
| **Sistemas y embebidos** | Linux, ESP-IDF, ESP32, Raspberry Pi, TensorFlow Lite / TFLite Micro |
| **Aplicaciones** | ASP.NET Core, Angular, Electron, Raylib, REST APIs |
| **Compiladores** | ANTLR 4, ASTs, grafos de llamadas, DSLs |
| **Herramientas** | Docker, Git |

---

## 🚀 Proyectos destacados

### 🐝 [HoneyComb Engine — Motor de juegos isométrico 2.5D](https://github.com/dannn-36/HoneyCombEngine-PlataformaNoCode-2.5D) *(en desarrollo)*
Arquitectura desacoplada: **runtime nativo en C++** y **editor en Electron/Angular**, comunicados por un pipeline JSON. Renderizado isométrico de tilemaps, gestión de escenas y entidades, ordenamiento por profundidad y gestión de recursos.
`C++` `Raylib` `Electron` `Angular`

### 🌱 [Calculadora de Impacto Ambiental de Algoritmos](https://github.com/dannn-36/Enviromental_Impact_calculator)
Analizador estático que estima el consumo energético de código en **Python, C, Java, Go y C#** antes de ejecutarlo. Parsea cada lenguaje con gramáticas **ANTLR 4**, construye el grafo de llamadas (Tarjan) para detectar recursión directa y mutua, estima la complejidad **O(…)** y asigna una puntuación ambiental de 0 a 100 ajustada por la eficiencia energética de cada lenguaje.
`Python` `FastAPI` `ANTLR 4` `Chart.js` · 69 tests con pytest

### 👁️ Detector de personas embebido
Pipeline de visión por computador en **ESP32-CAM** escrito en C++ y Assembly bajo fuertes restricciones de memoria, integrado con un servicio HTTP de telemetría en el propio dispositivo.
`C++` `Assembly` `TensorFlow Lite Micro` `ESP32-CAM`

### ♻️ Clasificación de residuos con Edge AI
CNN entrenada y cuantizada para clasificar residuos en tiempo real en **Raspberry Pi 5**, con **80 % de precisión** e inferencia de baja latencia en el dispositivo.
`Python` `TensorFlow Lite` `Raspberry Pi 5`

### 🎫 [ServiceDesk TI](https://github.com/dannn-36/ServiceDeskTI-Angular)
Mesa de servicio para gestionar incidentes, solicitudes y flujos de trabajo entre agentes, supervisores y clientes, con arquitectura **Repository–Service**.
`ASP.NET Core 9` `Angular 18` `Entity Framework Core` `MySQL`

### ⚙️ [Credit DSL — Compiladores](https://github.com/dannn-36/DSL-compiladores)
DSL interno para representar y evaluar reglas de aprobación de crédito mediante un **AST**, con interfaz WPF que visualiza el árbol de la regla principal.
`C#` `.NET 8` `WPF`

### 🛒 [Sistema de Ventas](https://github.com/dannn-36/SistemaDeVentas)
Sistema de gestión de ventas en Python.
`Python`

<details>
<summary><b>📂 Side quests (más proyectos)</b></summary>
<br/>

| Proyecto | Descripción | Stack |
|---|---|---|
| [PCA Demo](https://github.com/dannn-36/PCA_DEMO) · [🔗 demo](https://pcademostracion.vercel.app) | Demostración interactiva de Análisis de Componentes Principales | HTML, JS |
| [Algoritmos de cifrado](https://github.com/dannn-36/pagina-algoritmos-cifrado) | Página web con algoritmos de criptografía | JavaScript |
| [Taller de esteganografía](https://github.com/dannn-36/taller_esteganografia) | Ocultamiento de información en archivos | — |
| [Tienda MS](https://github.com/dannn-36/Tienda-MS) | Tienda con arquitectura de microservicios | Java |
| [Dockers](https://github.com/dannn-36/Dockers) | Configuraciones y prácticas con contenedores | Docker |
| [Página de redes](https://github.com/dannn-36/Pagina-redes) | Sitio sobre conceptos de redes | HTML |
| [Applied Math](https://github.com/dannn-36/applied-math) | Ejercicios de matemáticas aplicadas | Python |
| [Melanie's Smoothies](https://github.com/dannn-36/melanies_smoothies) | Formulario web de pedidos de smoothies | Python |

</details>

---

## 🎓 Educación

**Ingeniería de Sistemas — Universidad El Bosque** · Bogotá · *Graduación esperada: 2027*
Cursos relevantes: Sistemas Operativos, Microprocesadores, Arquitectura de Sistemas, Algoritmos y Complejidad, Redes.

---

## 📊 Telemetría

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=dannn-36&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Estadísticas de GitHub"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dannn-36&layout=compact&theme=tokyonight&hide_border=true" alt="Lenguajes más usados"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=dannn-36&theme=tokyonight&hide_border=true" alt="Racha de contribuciones"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=dannn-36&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" alt="Trofeos"/>
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=dannn-36&theme=tokyo-night&hide_border=true&area=true" alt="Gráfica de actividad"/>
</p>

---

## 🐍 La serpiente se come mis commits

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dannn-36/dannn-36/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dannn-36/dannn-36/output/github-snake.svg"/>
    <img alt="Serpiente comiéndose las contribuciones" src="https://raw.githubusercontent.com/dannn-36/dannn-36/output/github-snake-dark.svg"/>
  </picture>
</p>

---

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Frase aleatoria de programación"/>
</p>

<p align="center">
  <code>while (alive) { eat(); sleep(); code(); repeat(); }</code><br/>
  <sub>⬡ Hecho con C++, café y demasiadas horas de depuración ⬡</sub>
</p>
