Sistema de Automação Agrícola
Descrição do Projeto
Este projeto consiste em um algoritmo de controle inteligente focado em eficiência hídrica e preservação de recursos.
Desenvolvido para a disciplina do professor Diego no primeiro período do curso de Análise e Desenvolvimento de Sistemas, o software monitora variáveis ambientais em tempo real para decidir de forma autônoma o momento exato de irrigar.
O sistema utiliza feedback contínuo para manter a saúde da plantação dentro dos parâmetros ideais e interrompe o processo imediatamente em caso de anomalias, como desperdícios ou vazamentos nas linhas de distribuição.
Lógica do Sistema
O algoritmo opera em um loop contínuo baseado em três pilares fundamentais:
Monitoramento: Leitura constante da umidade do solo, clima e fluxo de água
Tomada de Decisão: Desliga a irrigação se a umidade atingir o nível ideal (60%).
Segurança Operacional: Interrompe as bombas se o fluxo de água ultrapassar o limite seguro.
 Definições Técnicas
 Variáveis de Controle
 UMIDADE_IDEAL: 60%
 LIMITE_FLUXO: 60 unidades
 Entradas de Sensores
 Umidade do solo
 Condições climáticas
 Fluxo de vazão
 Estrutura do Algoritmo
 Inicialização: Configuração dos parâmetros de umidade e fluxo.
 Loop Principal: Leitura de sensores e verificação de condições ambientais.
 Subprocesso de Irrigação: Monitoramento intensivo contra falhas mecânicas ou hidráulicas
 Resultados Obtidos
 Sistemas de Malha Fechada: Controle automatizado baseado no feedback dos sensores em tempo real.
 Gestão de Riscos: Mitigação de danos através de gatilhos automáticos de segurança e alertas de vazamento.
 Otimização de Recursos: Redução imediata de custos operacionais com base em dados ambientais reais.
 
