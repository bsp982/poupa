# 💰 Poupa+ - Controle Financeiro Pessoal

## 🎯 Objetivo
Centralizar e organizar **gastos, receitas e investimentos** de forma simples e eficiente, oferecendo **painéis de visualização (dashboards)** com informações úteis sobre o patrimônio e saúde financeira do usuário.

---

## 🧩 Funcionalidades Principais

### 1. 📊 Dashboard Financeiro
- **Patrimônio total**
- **Receita mensal**
- **Despesas mensais**
- **Investimentos ativos**
- **Resumo do mês**: saldo final (positivo/negativo)
- **Comparativo mês a mês**

### 2. 💵 Receitas
- Cadastro de receitas fixas e variáveis
- Histórico de entradas por categoria e data
- Origem da receita (salário, freelancer, outros)

### 3. 🧾 Despesas
- Cadastro de despesas categorizadas
- Filtros por tipo: fixa, variável, parcelada
- Acompanhamento por categoria: alimentação, transporte, lazer, etc.
- Lançamento de despesas por cartão de crédito, débito ou dinheiro

### 4. 💳 Cartão de Crédito
- Cadastro de múltiplos cartões
- Lançamento de faturas e gastos por cartão
- Identificação de gastos por categoria (ex: alimentação, transporte)
- Detecção de gastos parcelados

### 5. 📈 Investimentos
- Cadastro de ativos (ações, fundos, criptos, etc.)
- Atualização de valor de mercado
- Projeção de crescimento
- Total investido e rentabilidade

---

## 📐 Regras de Negócio

### Lançamentos
- Todo lançamento (receita, despesa, investimento) deve ter:
  - **Categoria**
  - **Data**
  - **Valor**
  - **Forma de pagamento** (cartão, débito, pix, boleto, etc.)
  - **Observações** (opcional)

### Fechamento Mensal
- Cada mês possui um **fechamento automático** com:
  - Receita total
  - Despesa total
  - Saldo final
  - Indicação se o mês fechou **no azul** ou **no vermelho**

### Cartão de Crédito
- Gastos lançados no cartão devem ser agrupados por fatura
- Parcelamentos devem impactar os próximos meses corretamente
- Pagamento da fatura impacta o saldo do mês correspondente

### Investimentos
- Devem atualizar valor de mercado periodicamente
- O valor investido compõe o **patrimônio total**
- Devem ser categorizados por tipo (renda fixa, variável, cripto, etc.)


---

> **Poupa+** é o seu assistente pessoal para tomar o controle das finanças, investir com consciência e alcançar seus objetivos com inteligência financeira.
