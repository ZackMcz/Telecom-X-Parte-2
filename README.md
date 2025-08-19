# Telecom-X-Parte-2
Prevendo Churn com Machine Learning

# A análise e modelagem preditiva da evasão de clientes em serviços de telecomunicações permitiram identificar fatores críticos que influenciam a decisão dos clientes em cancelar seus serviços. 
# Modelos como Regressão Logística, Árvore de Decisão, KNN, SVM Linear e XGBoost foram avaliados, e a análise de importância das variáveis revelou padrões consistentes.

Os **principais fatores de risco** identificados incluem:
*   **Contratos Mensais:** Clientes com este tipo de contrato são significativamente mais propensos a evadir.
*   **Tempo de Contrato Curto:** Clientes com menor tempo de relacionamento com a empresa apresentam maior risco.
*   **Serviço de Internet Fibra Óptica:** Clientes que utilizam este serviço parecem ter maior propensão à evasão (necessita de investigação adicional para entender os motivos).
*   **Altos Gastos:** Clientes com maiores gastos totais ou mensais também estão em maior risco.
*   **Falta de Serviços Adicionais:** A ausência de Suporte Técnico e Segurança Online está associada a uma maior chance de evasão.
*   **Método de Pagamento Cheque Eletrônico:** Este método de pagamento também foi correlacionado com maior evasão.

Em termos de desempenho do modelo, enquanto a acurácia geral foi razoável para a maioria dos modelos, o **Recall para a classe Churn (evasão)** se destacou como a métrica mais importante devido ao desequilíbrio de classes. O modelo de **Regressão Logística com SMOTE** demonstrou a melhor capacidade de identificar corretamente os clientes em risco (maior Recall), embora com uma Precisão menor. A escolha do modelo ideal dependerá do equilíbrio desejado entre identificar o máximo de clientes em risco (Recall) e minimizar abordagens desnecessárias (Precisão).

Com base nestes insights, as **estratégias de retenção propostas** visam abordar proativamente os segmentos de clientes de maior risco, oferecendo incentivos para contratos de longo prazo, melhorando a experiência do cliente (especialmente para usuários de fibra óptica e aqueles sem serviços adicionais), e monitorando clientes com altos gastos ou que utilizam métodos de pagamento de maior risco.

A implementação de um sistema de pontuação de risco de churn baseado nos modelos preditivos pode capacitar a empresa a direcionar seus esforços de retenção de forma mais eficiente e eficaz, transformando a gestão de churn de uma abordagem reativa para proativa, e contribuindo para a sustentabilidade e crescimento do negócio.

