---
title: "Bitácora de prácticas de la trifecta: Vim, tmux y QMK Firmware"
author: Evaristo Rojas • GECI
date: 2021-11-09
extensions: []
styles: {}
---

# Vim

Editor de texto con TUI

- Contenedores de Docker
- Servidores SSH

# tmux

Gestor de ventanas para la terminal de comandos del sistema operativo

# QMK Firmware

Firmware de código abierto que permite configurar los teclados compatibles

- Vim: _<Esc>_
- tmux: _<C-b>_

---

# Plantilla

## Metas

## Estado actual

## Aprendizajes, descubrimientos y logros

## Molestias

## Ideas

## Prácticando o estudiando

## Dudas por investigar

## Tareas y ejercicios pendientes

---

# Semana 1

- 2021-11-09 - 2021-11-13

## Metas
- Español: 20 wpm
- Python: 10 wpm

## Estado actual
- Español: 12 wpm

## Aprendizajes, descubrimientos y logros
- `vimtutor`
- `lightline.vim`
- `lightline-bufferline`
- `lookatme`

## Molestias
- Desinstalé SpaceVim porque no pude configurarlo
- Mi teclado QMK Firmware se descompuso
- Navegar entre buffers es difícil
- Configurar plugins es difícil

---

# Semana 1

## Ideas
- Prefiero cambiar la configuración de mi teclado en lugar de Vim o tmux

## Practicando o estudiando
- TypeRacer (español)

## Dudas por investigar
- ¿Cómo cambiar la línea de estado de tmux?
- ¿Cómo refactorizar?
- ¿Para qué sirven los corchetes: "[]" en Vim?

## Tareas y ejercicios pendientes
- :help quickref
- :help user-manual

---

# Semana 2

- 2021-11-14 - 2021-11-20

## Aprendizajes, descubrimientos y logros
- tmux 2: Productive Mouse-Free Development
- Personalización de la línea de estado de tmux
- `voldikss/vim-floaterm`
- <C-]> para saltar a la definición del método, <C-o> para regresar
- _[_ y _]_ son para navegación cuando se usan en combinación con _(_, _{_, _[_, _m_, _#_ y _*_
- Configurar **pp** para _pair programming_
    - `:set nornu`

## Molestias
- La ayuda de Vim se abre en un split
    - `:only`
- Las teclas muertas son muy incómodas con Vim
    - Ahora uso: _intl., with AltGr dead keys_

---

# Semana 2

## Ideas
- Restringir personalización de Vim
- Configurar tmux para que funcione como Vim

## Prácticando o estudiando
- :help quickref: Q_ma. Marks and motions
- Practical Vim

## Dudas por investigar
- ¿Cómo refactorizar?
- ¿Cómo instalar corrector ortográfico?

## Tareas y ejercicios pendientes
- :checkhealth
- :help user-manual
- Pair programming con tmux

---

# Semana 3

- 2021-11-21 - 2021-11-27

## Metas

## Estado actual

## Aprendizajes, descubrimientos y logros
- Es trivial replicar mi entorno de desarrollo en un servidor
- **No** es trivial replicar mi entorno de desarrollo en un contenedor
- Es agradable programar en pareja con tmux
- Practical Vim
- Corrector ortográfico en español
    - `:set spell`
    - `:set spelllang=es`

## Molestias
- Preview CSV
- Soft and hard wrap
- MUcomplete tiene conflicto con Telescope

---

# Semana 3

## Ideas
- No estoy seguro si prefiero un plugin para previsualizar CSV
    - `:2,$! sort -t',' -k3nr`
- En Vim queremos:
    - Minimizar pulsasiones de teclas (keystrokes)
    - Minimizar distancia que viajan los dedos
- Vim fue creado en un teclado de **59** teclas
    - El teclado convencional tiene 105 teclas
        - Incrementa la distancia que viajan los dedos
    - El Planck era de 48 teclas
        - Incrementa keystrokes
    - El SP50 es de **60** teclas
- Las capas de los teclados QMK se parecen a los modos de Vim

## Prácticando o estudiando
- :help quickref: Q_ma. Marks and motions

## Dudas por investigar
- ¿Cómo refactorizar?
- ¿Cómo instalar corrector ortográfico?
- Configurar `liuchengxu/vim-which-key`
- Configurar `glacambre/firenvim`

## Tareas y ejercicios pendientes
- :checkhealth
- :help user-manual

