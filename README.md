# ⚡ Calculadora de Consumo de Energia

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
ttps://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=ergy](https://img.shields.io/badge/Energia-Ellow?style=for-the-badge
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

 o Projeto

A **Calculadora de Consumo de Energia** é uma aplicação desenvolvida em Python para estimar o consumo mensal de energia elétrica de um aparelho eletrônico.

O usuário informa:

- Nome do aparelho
- Potência em Watts (W)
- Tempo médio de uso diário (horas)

O sistema calcula automaticamente o consumo mensal em **kWh** e apresenta uma estimativa de custo baseada em um valor fixo por kWh.

---

## 🚀 Tecnologias Utilizadas

- 🐍 Python
- 🌐 GitHub
- ⚡ Cálculo de Consumo Elétrico

---

## 📐 Fórmula Utilizada

Para calcular o consumo mensal:

```text
Consumo Mensal (kWh) =
(Potência × Horas por Dia × 30) / 1000
```

Exemplo:

```text
(150 × 10 × 30) / 1000
= 45 kWh/mês
```

---

## 💰 Cálculo do Custo Estimado

```text
Custo = Consumo Mensal × Valor do kWh
```

Valor utilizado no projeto:

```text
R$ 0,75 por kWh
```

---

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/consumo-energia.git
```

### 2. Acesse a pasta

```bash
cd consumo-energia
```

### 3. Execute o programa

```bash
python app.py
```

---

## 📌 Exemplo de Saída

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

## 👨‍💻 Autor

Projeto desenvolvido para fins educacionais em um programa de iniciação à tecnologia.