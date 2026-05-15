# 🌊 Sistema de Monitoramento de Irrigação Automatizado

## 📝 Descrição do Projeto

Este projeto consiste em um sistema lógico de automação agrícola desenvolvido para monitorar a umidade do solo e o fluxo de água em tempo real. O objetivo principal é garantir que o solo mantenha uma umidade ideal, prevenindo o uso excessivo de recursos hídricos através da detecção precoce de anomalias.

Desenvolvido como parte da disciplina de **Programação (1º Período - ADS)** com o Prof. Diego, o algoritmo processa leituras de sensores para decidir entre ativar a irrigação ou interrompê-la imediatamente em caso de suspeita de vazamentos.


*Figura 1: Dashboard de monitoramento exibindo níveis de umidade e alertas de fluxo.*

## 🚀 Tecnologias Utilizadas

* 
**Linguagem:** Pseudocódigo (Lógica de Programação) 


* 
**Conceitos:** Estruturas de Repetição (ENQUANTO), Condicionais Compostas e Monitoramento Contínuo 


* 
**Ferramentas:** Lógica de sensores de Fluxo e Umidade 



## 📊 Resultados e Aprendizados

O projeto aplicou conceitos de controle de fluxo e segurança operacional em sistemas automatizados:

* 
**Controle de Variáveis:** Implementei uma constante de segurança onde o `LIMITE_FLUXO` é definido em 60 para evitar sobrecarga.


* 
**Detecção de Falhas:** O sistema foi programado para identificar desperdício ou vazamento caso o fluxo de água ultrapasse o limite estabelecido durante a irrigação ativa.


* 
**Automação Inteligente:** A lógica de decisão desliga automaticamente a irrigação assim que a umidade ideal é atingida ou quando uma irregularidade é detectada.



## 🔧 Como Executar

1. Analise o fluxo lógico no arquivo de pseudocódigo.


2. Defina os parâmetros de `Umidade_IDEAL` e `LIMITE_FLUXO`.


3. Inicie o loop de monitoramento contínuo para processar as leituras dos sensores.
