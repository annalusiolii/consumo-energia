# ⚡ Calculadora de Consumo de Energia

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

## 📌 Sobre o Projeto

A **Calculadora de Consumo de Energia** é uma aplicação simples desenvolvida em **Python** como parte de uma atividade prática de Iniciação em Tecnologia. 

O objetivo do programa é ajudar os usuários a estimarem o gasto energético de seus aparelhos eletrônicos em casa de forma rápida e prática, além de exibir o valor estimado da conta ao final do mês.

---

## 💡 Como funciona?

O sistema solicita 3 informações simples do usuário:
1. 🏷️ **Nome do aparelho** (ex: Geladeira)
2. ⚡ **Potência em Watts** (ex: 150W)
3. ⏱️ **Tempo de uso diário em horas** (ex: 10 horas)

Com esses dados, o programa gera o consumo mensal estimado em **kWh** e calcula o custo financeiro em Reais.

---

## 🧮 Fórmulas Utilizadas

Para calcular o **Consumo Mensal (kWh)**:
$$\text{Consumo Mensal} = \frac{\text{Potência (W)} \times \text{Horas/Dia} \times 30}{1000}$$

Para calcular o **Custo Estimado (R$)**:
$$\text{Custo Estimado} = \text{Consumo Mensal (kWh)} \times \text{Tarifa (R\$ 0,75)}$$

> *Nota: Foi considerada uma taxa média fixa de R$ 0,75 por kWh.*

---

## 💻 Como Executar o Programa

Se quiser testar o projeto no seu computador, siga os passos abaixo no terminal:

```bash
# 1. Clone este repositório
git clone [https://github.com/annalusiolii/consumo-energia.git](https://github.com/annalusiolii/consumo-energia.git)

# 2. Acesse a pasta do projeto
cd consumo-energia

# 3. Execute o script em Python
python3 app.py=== CALCULADORA DE CONSUMO DE ENERGIA ===


## Exibição

Aparelho: Geladeira
Potência (W): 150
Uso diário (horas): 10

----------------------------------------
Aparelho: Geladeira
Consumo estimado: 45.00 kWh/mês
Custo estimado: R$ 33.75
----------------------------------------

---

### Como atualizar no terminal do seu Mac:

Depois de substituir o conteúdo no arquivo `README.md` (no VS Code ou no seu editor de texto), envie a atualização para o GitHub rodando estes 3 comandos no terminal:

```bash
git add README.md
git commit -m "docs: atualiza README.md com informacoes da autora e badges"
git push
