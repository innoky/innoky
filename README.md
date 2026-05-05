<div align="center">

# Иннокентий Романов

<sub>I'm building abstractions.</sub>

</div>

```asm
;══════════════════════════════════════════════════════════════════════════
;  innoky.asm — programmer profile, x86_64 / Linux
;  build:  nasm -f elf64 innoky.asm && ld -o innoky innoky.o
;══════════════════════════════════════════════════════════════════════════

BITS 64
GLOBAL _start

section .data
    name        db "Innokenty Romanov", 0
    university  db "НИЯУ МИФИ — программная инженерия", 0
    location    db "Moscow, RU", 0
    motto       db "I'm building abstractions.", 0

    ; ── Stack — что использую сейчас ─────────────────────────────────────
    languages   db "C++ (main)", 0, "C", 0, "Rust", 0, \
                   "Python", 0, "JavaScript / TypeScript", 0, \
                   "a bit of assembler", 0
    backend     db "Django", 0, "FastAPI", 0, "Aiogram", 0
    frontend    db "ReactJS", 0
    storage     db "PostgreSQL", 0, "Redis", 0
    runtime     db "Linux", 0, "Docker", 0, "Vulkan", 0
    devops      db "Git", 0, "GitHub Actions", 0, "systemd", 0

section .bss
    next_year   resq 1     ; ещё не аллоцировано
    side_quests resq 64    ; место под ad-hoc проекты

section .text
;──────────────────────────────────────────────────────────────────────────
; Основные интересы — низкоуровневые системы и абстракции над ними.
;──────────────────────────────────────────────────────────────────────────

interests:
    .systems     dq "ADTs, lock-free, smart-ptrs, lazy seqs"
    .networking  dq "tunnels, p2p, distributed storage"
    .graphics    dq "Vulkan, browser engines"
    .crypto      dq "TLS-camo, AEAD framing, REALITY"
    ret

;──────────────────────────────────────────────────────────────────────────
; Точка входа.
;──────────────────────────────────────────────────────────────────────────
_start:
    call    learn         ; всегда крутится в фоне
    call    abstract      ; main loop
    jmp     _start
```

<br/>

<div align="center">

## Pinned

<table>
<tr>
<td width="50%" valign="top">

### [MezeraEngine](https://github.com/innoky/MezeraEngine)
<sub>Vulkan-based experimental 3D engine</sub>

`C++` · `Vulkan` · WIP

</td>
<td width="50%" valign="top">

### [mimic](https://github.com/innoky/mimic)
<sub>Encrypted proxy with TLS Chrome 120 camouflage</sub>

`Rust` · `BoringSSL` · `Flutter` · `tokio`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [VMLX](https://github.com/innoky/VMLX)
<sub>High-performance browser engine with VMLX support</sub>

`C++`

</td>
<td width="50%" valign="top">

### [dockhand](https://github.com/innoky/Dockhand)
<sub>Lightweight C++ utility for automated Docker deployment via SSH</sub>

`C++` · `SSH` · `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [torsper](https://github.com/innoky/torsper)
<sub>Distributed information storage on the TOR network</sub>

`C++` · `TOR`

</td>
<td width="50%" valign="top">

### [LockFree-Structures](https://github.com/innoky/LockFree-Structures)
<sub>Lab-grade implementations of lock-free data structures</sub>

`C++` · `atomics`

</td>
</tr>
</table>

</div>

<br/>

<div align="center">

## Stats

<a href="https://github.com/innoky">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=innoky&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=innoky&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</a>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=innoky&theme=tokyonight&hide_border=true" height="180"/>

</div>

<br/>

<div align="center">

## Stack

![C++](https://img.shields.io/badge/-C++-00599C?logo=c%2B%2B&logoColor=white&style=flat-square)
![C](https://img.shields.io/badge/-C-A8B9CC?logo=c&logoColor=white&style=flat-square)
![Rust](https://img.shields.io/badge/-Rust-CE422B?logo=rust&logoColor=white&style=flat-square)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square)
![Assembly](https://img.shields.io/badge/-Assembly-654FF0?logo=gnu&logoColor=white&style=flat-square)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square)

![Vulkan](https://img.shields.io/badge/-Vulkan-AC162C?logo=vulkan&logoColor=white&style=flat-square)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black&style=flat-square)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat-square)
![Postgres](https://img.shields.io/badge/-PostgreSQL-336791?logo=postgresql&logoColor=white&style=flat-square)
![Redis](https://img.shields.io/badge/-Redis-DC382D?logo=redis&logoColor=white&style=flat-square)

![Django](https://img.shields.io/badge/-Django-092E20?logo=django&logoColor=white&style=flat-square)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square)
![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black&style=flat-square)
![Aiogram](https://img.shields.io/badge/-Aiogram-2CA5E0?logo=telegram&logoColor=white&style=flat-square)

</div>

<br/>

<div align="center">

<sub>
  <code>// Если хочется посотрудничать или просто поговорить о низкоуровневом — пиши</code>
</sub>

</div>
