# 😵 Jogo da Forca em C

![Linguagem C](https://img.shields.io/badge/Linguagem-C-00599C?style=for-the-badge&logo=c&logoColor=white) ![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

## 📝 Sobre o Projeto

Este repositório contém o projeto final da disciplina de **Algoritmos e Programação Estruturada**. O objetivo foi desenvolver um **Jogo da Forca** clássico utilizando a linguagem C, aplicando conceitos fundamentais como manipulação de arquivos, alocação de memória, ponteiros e modularização de código.

O diferencial deste projeto é o uso de um banco de dados de palavras externo (`.txt`), permitindo que o jogo seja expandido sem necessidade de recompilar o código.

## 🎮 Funcionalidades

* **Múltiplos Temas:** O usuário pode escolher entre 5 categorias:
    1.  Animais
    2.  Cores
    3.  Países ou Cidades
    4.  Frutas
    5.  Profissões
* **Sistema de Vidas:** O jogador possui um limite máximo de 5 erros.
* **Persistência de Dados:** As palavras são lidas de arquivos de texto.
* **Adicionar Palavras:** Ao final da partida, é possível cadastrar uma nova palavra no tema escolhido, que ficará salva permanentemente para os próximos jogos.
* **Interface Visual:** Feedback visual do boneco na forca utilizando caracteres ASCII.

## 📂 Estrutura de Arquivos

O projeto está organizado da seguinte maneira:

```text
/
├── forca.c              # Código fonte principal (Main)
├── forca.h              # Arquivo de cabeçalho (Protótipos e Constantes)
├── forca.exe            # Executável do jogo
├── animais.txt          # Banco de palavras: Animais
├── cores.txt            # Banco de palavras: Cores
├── frutas.txt           # Banco de palavras: Frutas
├── paisescidades.txt    # Banco de palavras: Países e Cidades
├── profissoes.txt       # Banco de palavras: Profissões
└── README.md            # Documentação do projeto
