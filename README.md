# 😵 Jogo da Forca em C

![Linguagem C](https://img.shields.io/badge/Linguagem-C-blue) ![Status](https://img.shields.io/badge/Status-Finalizado-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

## 📝 Descrição

[cite_start]Este projeto é uma implementação clássica do **Jogo da Forca** desenvolvida na linguagem C. O software foi criado como trabalho em grupo para a disciplina de **Algoritmos e Programação Estruturada**[cite: 6].

O objetivo principal foi aplicar conceitos avançados da linguagem, como alocação de memória, manipulação de ponteiros, estruturação de código em múltiplos arquivos (`.c` e `.h`) e persistência de dados através da leitura e escrita em arquivos de texto.

## 🎮 Funcionalidades

* [cite_start]**Seleção de Temas:** O jogador pode escolher entre 5 categorias de palavras[cite: 1]:
    1.  [cite_start]Animais [cite: 7]
    2.  [cite_start]Cores [cite: 2]
    3.  [cite_start]Países ou Cidades [cite: 1]
    4.  [cite_start]Frutas [cite: 300]
    5.  Profissões
* **Banco de Dados Dinâmico:** As palavras não estão "chumbadas" no código. O jogo lê arquivos `.txt` externos para sortear a palavra secreta.
* [cite_start]**Sistema de Vidas:** O jogador possui um limite de 5 erros antes de ser "enforcado"[cite: 1].
* [cite_start]**Adicionar Novas Palavras:** Ao final da partida, o usuário tem a opção de inserir uma nova palavra no banco de dados do tema escolhido, enriquecendo o jogo para as próximas partidas[cite: 1].
* **Interface em Console:** Uso de arte ASCII para desenhar a forca e o feedback visual do jogo.

## 🛠️ Tecnologias e Bibliotecas

O projeto utiliza as bibliotecas padrão do C e uma específica para ambiente Windows:

* [cite_start]`stdio.h` (Entrada e saída) [cite: 1]
* [cite_start]`stdlib.h` (Alocação e funções gerais) [cite: 1]
* [cite_start]`string.h` (Manipulação de strings) [cite: 1]
* [cite_start]`time.h` (Geração de sementes aleatórias) [cite: 1]
* [cite_start]`ctype.h` (Tratamento de caracteres) [cite: 1]
* [cite_start]`conio.h` (Para função `getch` - **Nota:** Biblioteca específica para Windows/MinGW)[cite: 1].

## 📂 Estrutura do Projeto

```text
/
├── forca.c              # Arquivo principal com a lógica do jogo (main)
├── forca.h              # Cabeçalho com declaração de funções e constantes
├── forca.exe            # Executável compilado (Windows)
├── arquivos_dados/      # Base de dados das palavras
│   ├── animais.txt
│   ├── cores.txt
│   ├── frutas.txt
│   ├── paisescidades.txt
│   └── profissoes.txt
└── README.md            # Documentação do projeto
