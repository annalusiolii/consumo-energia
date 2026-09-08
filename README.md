# ⚡ Calculadora de Consumo de Energia

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

Este projeto foi desenvolvido como atividade prática de um programa de iniciação em tecnologia.

A proposta foi criar uma calculadora capaz de estimar o consumo mensal de energia elétrica de um aparelho eletrônico a partir de informações simples fornecidas pelo usuário.

Além de calcular o consumo em kWh, também adicionei uma funcionalidade para estimar o custo mensal da energia com base em um valor fixo por kWh.

---

## 🎯 Objetivo

O objetivo deste projeto é ajudar o usuário a entender melhor o gasto de energia dos aparelhos utilizados no dia a dia.

Também foi uma oportunidade para praticar conceitos básicos de Python, como:

- Entrada de dados
- Variáveis
- Operações matemáticas
- Saída de dados formatada
- Organização de projetos no GitHub

---

## 🐍 Linguagem Utilizada

- Python 3

---

## 📐 Fórmula Utilizada

O cálculo do consumo mensal é feito da seguinte forma:

```text
Consumo Mensal (kWh) =
(Potência × Horas de Uso por Dia × 30) / 1000
```

### Exemplo

```text
Potência: 150W
Uso diário: 10 horas

(150 × 10 × 30) / 1000

Resultado: 45 kWh/mês
```

---

## 💰 Cálculo do Custo Estimado

Para tornar o projeto mais completo, foi adicionado um cálculo de custo estimado utilizando o valor de:

```text
R$ 0,75 por kWh
```

Fórmula:

```text
Custo Estimado = Consumo Mensal × Valor do kWh
```

---

## ▶️ Como Executar o Projeto

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/consumo-energia.git
```

Acesse a pasta:

```bash
cd consumo-energia
```

Execute o programa:

```bash
python3 app.py
```

---

## 🖥️ Exemplo de Execução

```text
=== Calculadora de Consumo de Energia ===

Digite o nome do aparelho: Geladeira
Digite a potência do aparelho (W): 150
Digite o tempo médio de uso diário (horas): 10

===== Resultado =====

Aparelho: Geladeira
Consumo estimado: 45.00 kWh/mês
Custo estimado: R$ 33.75
```

---

## 📂 Estrutura do Projeto

```text
consumo-energia/
│
├── app.py
└── README.md
```

---

## ✨ O que aprendi com este projeto

Durante o desenvolvimento deste projeto pude praticar:

- Criação de programas em Python
- Coleta de dados digitados pelo usuário
- Realização de cálculos matemáticos
- Organização de arquivos
- Criação de documentação no GitHub
- Uso básico do Git para versionamento

---

## 👩‍💻 Autora

Desenvolvido por Anna Luiza Silvestre Oliveira como atividade de aprendizagem e prática em programação Python.
