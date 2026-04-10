MVP: Análise de Dados e Boas Práticas - PUC-Rio

Este repositório contém o MVP desenvolvido para a disciplina de Análise de Dados e Boas Práticas, integrante do curso de Pós-graduação em Ciência de Dados e Analytics da PUC-Rio.

Descrição do Projeto
O trabalho consiste na análise exploratória e no pré-processamento de um conjunto de dados sobre inadimplência de clientes de cartão de crédito. O foco principal é a compreensão dos fatores de risco e a preparação da base de dados para modelagem preditiva.

Conteúdo do Repositório

    Notebook de Análise: Arquivo contendo o ciclo completo de carga, exploração, visualização estatística e tratamento de dados.
    Dataset: Base de dados original utilizada no projeto, referenciada no código via URL para garantir a reprodutibilidade.

Etapas de Desenvolvimento

    1. Análise de Dados: Verificação de tendências centrais, dispersão (desvio padrão) e distribuições via histogramas e boxplots.
    2. Validação de Hipóteses: Investigação da relação entre inadimplência e variáveis como escolaridade, limite de crédito e histórico de pagamentos.
    3. Pré-processamento:
        Divisão dos dados em conjuntos de treino e teste com estratificação.
        Normalização e Padronização de atributos numéricos.
        Tratamento de variáveis categóricas via One-Hot Encoding e criação da variável de utilização de limite.

Conclusão

A análise confirmou que o histórico de pagamentos e a taxa de utilização do limite são indicadores fundamentais para a identificação de perfis de risco, validando as suposições iniciais do projeto.
