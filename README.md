# 🔬 Laboratório de Sistemas Digitais - ENE[XXXX]

## 📝 Sobre o Projeto

Este repositório contém todos os experimentos, códigos-fonte e relatórios desenvolvidos durante a disciplina de **Laboratório de Sistemas Digitais**, parte do currículo de Engenharia de Redes de Comunicações da Universidade de Brasília (UnB).

O objetivo principal foi aplicar na prática os conceitos teóricos de circuitos lógicos, desde portas lógicas básicas até sistemas sequenciais complexos, utilizando a linguagem de descrição de hardware (HDL) **VHDL** e a plataforma de desenvolvimento **Intel Quartus Prime**.

-----

## 🏛️ Informações da Disciplina

  * **Universidade:** Universidade de Brasília (UnB)
  * **Curso:** Engenharia de Redes de Comunicações
  * **Disciplina:** Laboratório de Sistemas Digitais - ENE[Código da Matéria]
  * **Professor:** Guilherme Torres
  * **Semestre Cursado:** 2024/2

-----

## 🛠️ Tecnologias e Ferramentas Utilizadas

  * **Linguagem de Descrição de Hardware (HDL):** VHDL
  * **Software de Simulação e Síntese:** Intel Quartus Prime Lite Edition
  * **Software de Simulação de Formas de Onda:** ModelSim
  

-----

## 📂 Estrutura do Repositório

O repositório está organizado em pastas, uma para cada experimento realizado. A estrutura padrão de cada experimento é:

```
├── 🧪 Experimento_XX-[Nome_do_Experimento]/
│
├── 📄 Relatorio/
│   └── Relatorio_XX.pdf  
│
├── 💻 Codigo_Fonte/
│   ├── [nome_do_arquivo].vhd (Código VHDL da implementação)
│   └── [nome_do_arquivo]_tb.vhd (Testbench para simulação)
│
└── 📈 Simulacao/
    └── [screenshot_da_simulacao].png (Imagem da forma de onda resultante)

```

-----

## 🧪 Lista de Experimentos Desenvolvidos

| Nº  | Tópico do Experimento             | Descrição Breve                                                               | Link para a Pasta                                                                 |
| :-: | :-------------------------------- | :---------------------------------------------------------------------------- | :-------------------------------------------------------------------------------- |
| 01  | **Portas Lógicas Básicas** | Implementação e simulação de portas lógicas AND, OR, NOT, XOR, NAND e NOR.    | [Link](https://www.google.com/search?q=./%F0%9F%A7%AA%2520Experimento_01-Portas_Logicas)                                       |
| 02  | **Circuitos Combinacionais I** | Projeto de um somador completo de 4 bits e um multiplexador 4x1.              | [Link](https://www.google.com/search?q=./%F0%9F%A7%AA%2520Experimento_02-Circuitos_Combinacionais_I)                            |
| 03  | **Circuitos Combinacionais II** | Implementação de decodificadores BCD para 7 segmentos.                         | [Link](https://www.google.com/search?q=./%F0%9F%A7%AA%2520Experimento_03-Circuitos_Combinacionais_II)                           |
| 04  | **Circuitos Sequenciais - Flip-Flops** | Construção e análise de Flip-Flops tipo D, T e JK.                            | [Link](https://www.google.com/search?q=./%F0%9F%A7%AA%2520Experimento_04-Circuitos_Sequenciais)                                |
| 05  | **Máquinas de Estados Finitos** | Projeto de um detector de sequência "1101" utilizando FSM (Moore e Mealy).    | [Link](https://www.google.com/search?q=./%F0%9F%A7%AA%2520Experimento_05-Maquinas_de_Estados)                                 |                                  | |

-----

## 🚀 Como Utilizar

Para simular ou sintetizar qualquer um dos projetos, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/[seu-usuario]/[nome-do-repositorio].git
    ```
2.  **Pré-requisitos:** Certifique-se de ter o [Intel Quartus Prime Lite](https://www.intel.com.br/content/www/br/pt/software/programmable/quartus-prime/download.html) instalado.
3.  **Abra o Projeto:** Navegue até a pasta do experimento desejado e abra o arquivo de projeto `.qpf` no Quartus.
4.  **Compile o Código:** Inicie a compilação (Processing \> Start Compilation) para verificar a sintaxe e gerar os arquivos necessários.
5.  **Simule:** Abra o ModelSim (Tools \> Run Simulation Tool \> RTL Simulation) para executar o testbench e visualizar as formas de onda.

-----

## 🎯 Principais Aprendizados

  * Domínio da sintaxe e das estruturas da linguagem **VHDL** para descrever hardware.
  * Compreensão profunda da diferença entre **circuitos combinacionais e sequenciais**.
  * Experiência prática com o fluxo de desenvolvimento para FPGAs: **simulação, síntese e análise de temporização**.
  * Desenvolvimento de **testbenches** eficazes para validação e depuração de projetos digitais.
  * Aplicação de conceitos de **máquinas de estados finitos** para resolver problemas de lógica sequencial.

-----

## 👨‍💻 Autor

  * **Bernardo Rizzone Sousa Vale de Araujo**
  * **LinkedIn:** 
  * **E-mail:** bernardorizzone98@gmail.com

-----
