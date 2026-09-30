<img src="https://capsule-render.vercel.app/api?type=waving&color=00599C&height=160&section=header&text=procesadores-lenguaje&fontSize=24&fontColor=FFFFFF&fontAlignY=40&desc=PL%20%7C%20UAH%202026-27&descAlignY=60&descColor=9EC8E0" width="100%"/>

<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Flex/Bison](https://img.shields.io/badge/Flex%2FBison-444441?style=for-the-badge)
![ANTLR4](https://img.shields.io/badge/ANTLR-4.13.2-E34F26?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Compilers](https://img.shields.io/badge/Compilers-085041?style=for-the-badge)
![UAH](https://img.shields.io/badge/UAH-GII-085041?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-1D9E75?style=for-the-badge)

</div>

---

## About

**Asignatura:** Procesadores del Lenguaje · UAH GII · Curso 2026-27 · 3er Curso

Compiler and language-processor construction from front to back end. Covers the full pipeline from source text to executable intermediate representation, building a working compiler/interpreter as the main practice.

---

## Topics covered

| Block | Content |
|-------|---------|
| Lexical Analysis | Regular expressions, finite automata, tokenization, lexer generators (Flex/Lex) |
| Syntax Analysis | Context-free grammars, LL and LR parsing, parser generators (Bison/Yacc), abstract syntax trees |
| Semantic Analysis | Symbol tables, scope resolution, type checking, attribute grammars |
| Intermediate Code & Optimisation | Intermediate representations, basic blocks, local optimisation, code generation basics |

---

## Practices

| # | Name | Description | Stack |
|---|------|-------------|-------|
| PL1 | [Gramáticas y generadores automáticos](practicas/PL1_Grupo10) 🔒 | Lexer y parser de C− (Louden) con `for`, `char`, `bool` y operadores lógicos; lexer, parser y simulador de partidas de los *Battle Logs* de Pokémon TCG Live | ANTLR 4 · Python · Visitor |

> 🔒 Las prácticas en grupo están en repositorios **privados** enlazados como submódulos: el enlace solo funciona para los miembros del grupo.
> Para clonarlo todo: `git clone --recurse-submodules https://github.com/Danix29/procesadores-lenguaje.git`

---

## Project structure

```
procesadores-lenguaje/
├── README.md
└── practicas/
    └── PL1_Grupo10/   → submódulo privado (Danix29/PL1_Grupo10)
```

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=00599C&height=100&section=footer" width="100%"/>

*Procesadores del Lenguaje · UAH GII · 2026-27*
</div>
