<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0B0B,100:FF2A2A&height=170&section=header&text=Language%20Processors&fontSize=40&fontColor=EAEAEA&fontAlignY=38&desc=Procesadores%20del%20Lenguaje%20%C2%B7%20UAH%20%C2%B7%202026-27&descAlignY=62&descColor=EAEAEA" width="100%"/>

<div align="center">

![UAH](https://img.shields.io/badge/UAH-GII-161616?style=flat-square&labelColor=FF2A2A) ![ECTS](https://img.shields.io/badge/ECTS-6-161616?style=flat-square&labelColor=FF2A2A) ![Elective](https://img.shields.io/badge/Elective-161616?style=flat-square) ![Term](https://img.shields.io/badge/Term-3rd_year_%C2%B7_1st_semester-161616?style=flat-square)

![ANTLR](https://img.shields.io/badge/ANTLR-4.13.2-E34F26?style=flat-square) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)

[![Profile](https://img.shields.io/badge/Danix29-profile-161616?style=flat-square&logo=github&logoColor=white)](https://github.com/Danix29) [![Portfolio](https://img.shields.io/badge/portfolio-danix29.github.io-FF2A2A?style=flat-square)](https://danix29.github.io)

</div>

---

## About

**Procesadores del Lenguaje** (Language Processors) · Universidad de Alcalá, Grado en Ingeniería Informática · 3rd year, 1st semester.

Compiler and language-processor construction from front to back end. The course builds, phase by phase, a compiler for **C−** (Louden's subset of C) that ends in **RISC-V assembly**; the first phase is the front end: recognise the language and build its syntax tree.

---

## Syllabus

| Block | Content |
|-------|---------|
| Lexical Analysis | Regular expressions, finite automata, tokenization, lexer generators (ANTLR, Flex/Lex) |
| Syntax Analysis | Context-free grammars, LL and LR parsing, parser generators (ANTLR, Bison/Yacc), abstract syntax trees |
| Semantic Analysis | Symbol tables, scope resolution, type checking, attribute grammars |
| Intermediate Code & Optimisation | Intermediate representations, basic blocks, local optimisation, code generation basics |

---

## Units covered so far

- **Unit 1** · Introduction to compilers
- **Unit 2** · Lexical analysis: what a lexer does, its elements, specifying tokens, regular expressions, finite automata and building a lexical analyser

---

## Practices

| # | Name | Description | Stack |
|---|------|-------------|-------|
| PL1 | [Gramáticas y generadores automáticos](practicas/PL1_Grupo10) 🔒 | Lexer y parser de C− (Louden) con `for`, `char`, `bool` y operadores lógicos; lexer, parser y simulador de partidas de los *Battle Logs* de Pokémon TCG Live | ANTLR 4 · Python · Visitor |

**PL1 · Grammars and automatic generators** (groups of four, September 2026). Learn to use a lexer/parser generator (ANTLR), recognise a language with lexical and syntactic analysers, build the abstract syntax tree of an input and start with symbol tables and error handling. Two independent parts: lexical and syntactic analysis of C−, and a second language processor. Deliverable: code plus an explanatory report, which weighs most in the grade.

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
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF2A2A,100:0B0B0B&height=90&section=footer" width="100%"/>

<sub>Language Processors · UAH GII · 2026-27 · Daniel Del Nogal Buchanan</sub>
</div>
