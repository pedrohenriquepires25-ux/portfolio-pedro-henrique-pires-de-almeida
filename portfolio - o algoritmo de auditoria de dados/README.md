

# 🛡️ Sistema de Auditoria de Vendas e Detecção de Outliers

## 📝 Descrição do Projeto

Este projeto foi desenvolvido como parte da disciplina de **Programação (1º Período - ADS)** com o Prof. Diego. O objetivo é simular um sistema de monitoramento financeiro que identifica discrepâncias de dados (outliers) e aplica conceitos de margem de tolerância e auditoria para garantir a integridade de relatórios de vendas.

O sistema analisa transações, calcula médias e aplica gatilhos de segurança para colocar o sistema em "quarentena" caso valores suspeitos sejam detectados, mitigando riscos de fraudes ou erros operacionais que distorcem a realidade financeira.


*Figura 1: Representação de como valores extremos (outliers) "puxam" a média e distorcem a análise.*

## 🚀 Tecnologias Utilizadas

* **Linguagem:** Python 3.10
* **Conceitos:** Estatística Descritiva, Tratamento de Exceções, Escopo de Variáveis.
* **Ferramentas:** VS Code, Git/GitHub.

## 📊 Resultados e Aprendizados

O projeto permitiu a exploração de conceitos críticos de análise de dados e segurança de software aplicados a sistemas financeiros:

* **Média vs. Outliers:** Compreendi como um único valor (ex: R$ 5.000,00) pode inflar artificialmente uma média de vendas baixas, exigindo o uso de técnicas como a **Média Aparada** para uma visão mais fiel.
* **Engenharia de Segurança:** Aprendi que o uso de variáveis `global` em sistemas bancários é uma vulnerabilidade de exposição. Em cenários reais, os limites devem ser **encapsulados** ou buscados em serviços externos com trilha de auditoria.
* **Tratamento de Dados:** Implementação de lógica para converter entradas do usuário (substituindo vírgulas por pontos) e tratamento de erros com `try/except`.

## 🔧 Como Executar

1. Clone o repositório.
2. Certifique-se de ter o Python instalado.
3. Execute o comando: `python main.py`.

---

### 💡 Exemplo de Lógica de Auditoria (Teste de Estresse)

| Venda 1 | Venda 2 | Venda 3 | Média Calculada | Gatilho (10k) | Status |
| --- | --- | --- | --- | --- | --- |
| R$ 100 | R$ 200 | R$ 5.000 | R$ 1.766,66 | Não atingido | Liberado |

> **Nota:** Embora a venda de R$ 5.000,00 seja quase 3x a média, o sistema foi calibrado para disparar a revisão manual apenas em valores 5x superiores, demonstrando o conceito de **Margem de Tolerância**.
