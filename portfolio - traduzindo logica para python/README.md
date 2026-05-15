## 📝 Descrição do Projeto

Este conjunto de atividades faz parte do desenvolvimento prático na disciplina de **Programação (1º Período - ADS)**. O objetivo é consolidar o domínio sobre estruturas de controle, tratamento de erros (exceções) e lógica de negócios aplicada a diferentes cenários do cotidiano, como finanças, meteorologia e educação.

O foco principal destas atividades é a criação de algoritmos robustos em Python que validam entradas do usuário e processam dados para gerar relatórios precisos.


*Figura 1: Visualização lógica de fluxos de decisão e loops de processamento.*

## 🚀 Tecnologias e Conceitos Utilizados

* **Linguagem:** Python 3.10
* **Tratamento de Exceções:** Uso de blocos `try/except` para evitar travamentos por entradas inválidas.
* **Estruturas de Repetição:** Utilização de `for` e `range()` para processamento de lotes de dados.
* **Lógica Condicional:** Aplicação de `if/elif/else` para tomada de decisão baseada em faixas de valores.

## 📊 Detalhamento das Atividades

### 1. Processamento de Vendas com Desconto Progressivo

Sistema que calcula o total de uma compra com base em múltiplos produtos e aplica descontos automáticos:

* **Regra:** 10% de desconto para compras acima de R$ 500,00 e 5% para compras acima de R$ 200,00.
* **Segurança:** Filtro que ignora preços ou quantidades negativas ou zeradas.

### 2. Analisador de Clima e Alertas Extremos

Algoritmo de monitoramento ambiental que processa a temperatura de uma semana:

* **Métrica:** Calcula a média semanal e conta dias com calor excessivo (> 35°C).
* **Segurança Operacional:** Dispara um **Alerta Extremo** se detectar temperaturas fora da faixa de -5°C a 45°C.

### 3. Gestão Acadêmica: Sistema de Notas

Ferramenta para automação de diários de classe:

* **Fluxo:** Coleta notas de múltiplos alunos e calcula a média aritmética simples.
* **Critérios de Aprovação:** Aprovado (>= 7.0), Recuperação (>= 5.0) ou Reprovado (< 5.0).

### 4. Simulador de Poupança e Investimentos

Algoritmo de projeção financeira com juros compostos e aportes mensais:

* **Destaque:** Identifica o mês exato em que o usuário atinge a meta financeira de **R$ 10.000,00**.
* **Interatividade:** Permite depósitos variáveis a cada mês da simulação.

## 🔧 Como Executar

1. Escolha a atividade desejada no repositório.
2. Certifique-se de ter o Python 3 instalado em sua máquina.
3. Execute o arquivo via terminal: `python nome_da_atividade.py`.
