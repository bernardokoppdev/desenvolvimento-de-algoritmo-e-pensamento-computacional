# 🧮 Calculadora Universal — Flowgorithm

![Ferramenta](https://img.shields.io/badge/Ferramenta-Flowgorithm-blue.svg)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen.svg)
![Funções](https://img.shields.io/badge/Fun%C3%A7%C3%B5es-20-orange.svg)
![Disciplina](https://img.shields.io/badge/Disciplina-Algoritmos-purple.svg)

> **Atividade avaliativa da disciplina de Desenvolvimento de Algoritmos e Pensamento Computacional.**

---

## 📚 Informações da Atividade

| Informação               | Detalhes               |
| ------------------------ | ---------------------- |
| 👨‍🎓 **Aluno**          | Bernardo Kopp Pinheiro |
| 🛠️ **Ferramenta**       | Flowgorithm            |
| 📄 **Arquivo principal** | `calculadora.fprg`     |
| ⭐ **Valor**              | 0,5 ponto              |
| 📅 **Data limite**       | 31/08/2026             |
| ✅ **Status**             | Concluído              |

---

## 🎯 Objetivo

Desenvolver uma **calculadora utilizando Flowgorithm**, aplicando conceitos fundamentais de lógica de programação e pensamento computacional.

Durante o desenvolvimento foram utilizados conceitos como:

* 📥 Entrada e saída de dados
* 📦 Declaração e utilização de variáveis
* ➕ Operadores matemáticos
* 🔀 Estruturas condicionais
* ⚙️ Processamento de informações
* 🧩 Organização de fluxogramas

O programa disponibiliza **20 funções/operações diferentes**, organizadas em **8 categorias**, permitindo que o usuário escolha uma operação, informe os valores necessários e visualize o resultado.

---

## 📝 Funcionamento do Programa

O funcionamento da calculadora segue o seguinte fluxo:

1. ▶️ O programa apresenta o **menu principal**.
2. 🔢 O usuário escolhe uma das **8 categorias disponíveis**.
3. 📋 O programa apresenta as operações correspondentes à categoria.
4. ⌨️ O usuário informa os valores necessários.
5. ⚙️ Os dados são processados utilizando operadores e estruturas condicionais.
6. 📊 O resultado da operação é exibido na tela.
7. 🏁 O programa informa o encerramento da execução.

---

# 🔢 Funções Implementadas

## 📐 1–4. Cálculo de Áreas

O programa permite calcular a área de quatro figuras geométricas diferentes.

### 1. Área do Quadrilátero

Calcula a área utilizando o lado e a altura.

```text id="plf4jk"
Área = lado × altura
```

### 2. Área do Triângulo

Calcula a área utilizando a base e a altura.

```text id="gn1anx"
Área = (base × altura) / 2
```

### 3. Área do Círculo

Calcula a área utilizando o raio.

```text id="e4c41v"
Área = π × raio²
```

### 4. Área do Losango

Calcula a área utilizando as diagonais maior e menor.

```text id="17ix6j"
Área = (diagonal maior × diagonal menor) / 2
```

> ✅ As funções **1, 2, 3 e 4** atendem ao requisito de cálculo de áreas de figuras geométricas.

---

## ⚖️ 5. Cálculo do IMC

Calcula o **Índice de Massa Corporal (IMC)** utilizando o peso e a altura informados pelo usuário.

```text id="y23ihb"
IMC = peso / altura²
```

Após o cálculo, o programa classifica o resultado como:

| Resultado      | Classificação      |
| -------------- | ------------------ |
| Menor que 18,5 | Abaixo do peso     |
| 18,5 – 24,9    | Peso normal        |
| 25,0 – 29,9    | Sobrepeso          |
| 30,0 – 34,9    | Obesidade grau I   |
| 35,0 – 39,9    | Obesidade grau II  |
| 40 ou mais     | Obesidade grau III |

> ✅ A função **5** atende ao requisito de cálculo e classificação do IMC.

---

## 🧮 6–10. Calculadora Simples

A calculadora possui cinco operações matemáticas.

|   Nº   | Operação         | Cálculo           |
| :----: | ---------------- | ----------------- |
|  **6** | ➕ Soma           | `a + b`           |
|  **7** | ➖ Subtração      | `a - b`           |
|  **8** | ✖️ Multiplicação | `a × b`           |
|  **9** | ➗ Divisão        | `a / b`           |
| **10** | 🔢 Potenciação   | `base ^ expoente` |

---

## 🌡️ 11–12. Conversão de Temperatura

### 11. Celsius para Fahrenheit

Converte uma temperatura de graus Celsius para Fahrenheit.

```text id="d4zwg5"
F = (C × 9 / 5) + 32
```

### 12. Celsius para Kelvin

Converte uma temperatura de graus Celsius para Kelvin.

```text id="8yykhv"
K = C + 273
```

---

## 🔎 13. Identificação de Número Par ou Ímpar

Verifica se um número inteiro é **par ou ímpar** utilizando o resto da divisão.

```text id="azdqma"
número % 2
```

* Se o resto for `0` → **Número par**
* Se o resto for diferente de `0` → **Número ímpar**

---

## 💰 14. Cálculo de Desconto

Calcula o valor final de um produto após a aplicação de uma porcentagem de desconto.

```text id="a43msu"
Valor final = valor do produto - (valor do produto × desconto / 100)
```

---

## ⚖️ 15. Comparação entre Valores

Compara dois números informados pelo usuário.

O programa identifica se:

* `A > B` → O primeiro valor é maior
* `A = B` → Os valores são iguais
* `A < B` → O segundo valor é maior

---

## 📏 16–20. Conversão de Unidades

O programa realiza cinco conversões a partir de um valor informado em **metros**.

|   Nº   | Conversão            | Cálculo         |
| :----: | -------------------- | --------------- |
| **16** | Metros → Milímetros  | `metros × 1000` |
| **17** | Metros → Centímetros | `metros × 100`  |
| **18** | Metros → Decímetros  | `metros × 10`   |
| **19** | Metros → Hectômetros | `metros / 100`  |
| **20** | Metros → Quilômetros | `metros / 1000` |

---

# 📊 Resumo das 20 Funções

|  Nº | Função                   | Categoria       |
| :-: | ------------------------ | --------------- |
|  01 | Área do quadrilátero     | 📐 Área         |
|  02 | Área do triângulo        | 📐 Área         |
|  03 | Área do círculo          | 📐 Área         |
|  04 | Área do losango          | 📐 Área         |
|  05 | Cálculo do IMC           | ⚖️ IMC          |
|  06 | Soma                     | ➕ Calculadora   |
|  07 | Subtração                | ➖ Calculadora   |
|  08 | Multiplicação            | ✖️ Calculadora  |
|  09 | Divisão                  | ➗ Calculadora   |
|  10 | Potenciação              | 🔢 Calculadora  |
|  11 | Celsius → Fahrenheit     | 🌡️ Temperatura |
|  12 | Celsius → Kelvin         | 🌡️ Temperatura |
|  13 | Par ou ímpar             | 🔎 Lógica       |
|  14 | Cálculo de desconto      | 💰 Porcentagem  |
|  15 | Comparação entre valores | ⚖️ Comparação   |
|  16 | Metros → Milímetros      | 📏 Conversão    |
|  17 | Metros → Centímetros     | 📏 Conversão    |
|  18 | Metros → Decímetros      | 📏 Conversão    |
|  19 | Metros → Hectômetros     | 📏 Conversão    |
|  20 | Metros → Quilômetros     | 📏 Conversão    |

### ✅ Total: 20 funções/operações

**4** funções de área + **1** cálculo de IMC + **5** operações matemáticas + **2** conversões de temperatura + **1** verificação par/ímpar + **1** cálculo de desconto + **1** comparação + **5** conversões de unidades = **20 funções**.

---

# 🖥️ Menu Principal

Ao iniciar o programa, o usuário encontra o seguinte menu:

```text id="57ozkr"
╔══════════════════════════════════════════════╗
║           CALCULADORA UNIVERSAL             ║
╠══════════════════════════════════════════════╣
║  1 - Calculadora de área                    ║
║  2 - Cálculo de IMC                         ║
║  3 - Calculadora simples                    ║
║  4 - Conversor de temperatura               ║
║  5 - Identificação de número par ou ímpar   ║
║  6 - Cálculo de desconto                    ║
║  7 - Comparador de valores                  ║
║  8 - Conversor de unidades                  ║
╚══════════════════════════════════════════════╝
```

---

## 📂 Estrutura do Projeto

```text id="gwqq7q"
calculadora-flowgorithm/
│
├── calculadora.fprg
└── README.md
```

O arquivo `calculadora.fprg` contém o fluxograma completo desenvolvido no **Flowgorithm**.

---

## 🧠 Conceitos Aplicados

Durante o desenvolvimento do projeto foram utilizados conceitos fundamentais de algoritmos e lógica de programação:

* Variáveis
* Tipos de dados
* Entrada e saída
* Operadores aritméticos
* Operadores relacionais
* Estruturas condicionais
* Cálculos matemáticos
* Fluxo de execução
* Organização lógica de algoritmos

---

## 🛠️ Tecnologia Utilizada

### Flowgorithm

O **Flowgorithm** é uma ferramenta voltada para o aprendizado de lógica de programação por meio da construção visual de fluxogramas.

Neste projeto, ele foi utilizado para estruturar toda a lógica da calculadora antes de sua implementação em uma linguagem de programação.

---

## 🔄 Evolução do Projeto

O desenvolvimento seguiu duas etapas:

```text id="f68vzx"
Flowgorithm
     │
     │  Algoritmo e lógica
     ▼
 calculadora.fprg
     │
     │  Implementação
     ▼
  Linguagem C
     │
     ▼
 calculadora.c
```

A versão desenvolvida em Flowgorithm serviu como base lógica para a posterior implementação da **Calculadora Universal em C**.

➡️ **[Ver versão em C](../calculadora-em-C)**

---

<div align="center">

### 🧮 Calculadora Universal

**Desenvolvimento de Algoritmos e Pensamento Computacional**

`Flowgorithm` • `20 funções` • `8 categorias`

🎓 **Atividade Acadêmica — 2026**

</div>
