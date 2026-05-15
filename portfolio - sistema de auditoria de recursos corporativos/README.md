
# 📊 Sistema de Auditoria de Orçamento Multinacional

## 📝 Descrição do Projeto

Este projeto consiste em um sistema de processamento financeiro desenvolvido para lidar com estruturas organizacionais complexas e dinâmicas. O motor do sistema utiliza **recursão profunda** para navegar em árvores de dados (dicionários aninhados) que representam departamentos, sub-departamentos e equipes de uma multinacional.

Desenvolvido como parte da disciplina de **Análise e Desenvolvimento de Sistemas (2024.1)**, o script automatiza o cálculo de orçamentos consolidados, permitindo a exclusão seletiva de setores e a conversão monetária em tempo real, tudo isso sob um rigoroso protocolo de auditoria implementado via **Decorators**.

## 🎯 Requisitos da Missão

O sistema foi construído para atender aos seguintes critérios técnicos:

* **Processamento Recursivo:** Navegação em profundidade arbitrária em estruturas de dados aninhadas.
* **Flexibilidade com `*args`:** Capacidade de ignorar departamentos específicos e toda a sua hierarquia durante a soma.
* **Parametrização via `kwargs`:** Suporte a conversões financeiras dinâmicas (taxa de câmbio e moeda de destino).
* **Auditoria via Decorators:** Interceptação de chamadas para monitoramento de performance, log de parâmetros e tempo de execução.

## 🚀 Tecnologias Utilizadas

* **Linguagem:** Python 3.10+
* **Recursos Avançados:** Decorators (`@wraps`), Recursão, Empacotamento/Desempacotamento de argumentos (`*args`, `kwargs`).
* **Bibliotecas Nativas:** `time`, `functools`.

## 📊 Arquitetura e Resultados

O sistema demonstra como padrões de projeto e recursos avançados de Python podem ser aplicados em cenários reais de backend:

* **Desempenho:** Monitoramento de tempo de processamento com precisão de microssegundos.
* **Abstração:** O algoritmo de soma é independente da profundidade da árvore de entrada.
* **Interface Limpa:** Saída formatada em console simulando um relatório de auditoria financeira profissional.

## 🔧 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git

```


2. Navegue até a pasta:
```bash
cd nome-do-repositorio

```


3. Execute o script principal:
```bash
python main.py

```



---

### 💡 Exemplo de Saída do Sistema

```text
╔──────────────────────────────────────────────────────╗
║                 AUDITORIA FINANCEIRA                 ║
╠──────────────────────────────────────────────────────╣
║  Função          : calcular_orcamento                ║
║  Moeda destino   : BRL                               ║
║  Taxa de câmbio  : 5.25                              ║
║  Ignorados       : Marketing, Filial_RJ              ║
╠──────────────────────────────────────────────────────╣
   Base (USD)    : $     722,000.00
   Convertido    : R$  3,790,500.00  [BRL]
╠──────────────────────────────────────────────────────╣
║  Tempo Proc.     : 0.000045s                         ║
╚──────────────────────────────────────────────────────╝

```
