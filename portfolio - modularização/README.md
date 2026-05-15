# 🛒 Algoritmo de Registro de Compras

## 📝 Descrição do Projeto

Este projeto apresenta a lógica de um sistema de checkout para registro de compras, focado no acúmulo de valores e controle de fluxo por interação do usuário. O sistema permite a entrada sucessiva de preços de produtos, realizando o somatório em tempo real até que o operador decida encerrar a sessão.

Desenvolvido como parte da disciplina de **Programação (1º Período - ADS)** com o Prof. Diego, o algoritmo explora o uso de estruturas de repetição "Até que" (Do-While) e manipulação de variáveis do tipo Real e Texto.


*Figura 1: Representação do fluxo de caixa e registro de itens.*

## 🚀 Tecnologias Utilizadas

* 
**Linguagem:** Pseudocódigo (Lógica de Programação).


* 
**Variáveis:** `Total_compra` (Real), `preco_item` (Real), `continuar` (Texto).


* 
**Estrutura de Controle:** Laço de repetição `Repetir...Até que`.



## 📊 Resultados e Aprendizados

O desenvolvimento deste algoritmo focou na gestão de acumuladores e na interface básica de entrada de dados:

* 
**Acumuladores Financeiros:** Implementei a lógica `Total_compra = Total_compra + preco_item` para garantir que cada novo item seja somado ao montante final.


* 
**Controle de Interrupção:** O sistema utiliza uma validação de texto (`continuar == "N"`) para determinar o fim da operação, simulando o comportamento real de um caixa de supermercado.


* 
**Localização de Dados:** O projeto também prevê a estrutura para exibição de calendários/dias da semana (DOM a SÁB) para futura implementação de logs de vendas por data.



## 🔧 Como Executar

1. Inicie o algoritmo de Registro de Compra.


2. Insira o preço de cada produto conforme solicitado no console.


3. Digite "S" para continuar adicionando itens ou "N" para finalizar e retornar o valor total.
