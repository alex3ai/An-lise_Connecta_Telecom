# Análise e Previsão de Churn - Connecta Telecom

## 1. Contexto e Problema de Negócio

A **Connecta Telecom**, uma empresa fictícia de telecomunicações, está enfrentando uma taxa de cancelamento de serviços (churn) acima da média do setor. A perda de clientes não só impacta a receita recorrente, mas também gera custos elevados com a aquisição de novos clientes para substituir os que foram perdidos.

A diretoria precisa de respostas claras e baseadas em dados para a seguinte pergunta: **"Quais são os principais fatores que levam nossos clientes a cancelar o serviço?"**

## 2. Objetivos do Projeto

Este projeto visa utilizar a **Regressão Logística** para analisar dados de clientes e atingir os seguintes objetivos:

1.  **Identificar os Fatores-Chave:** Determinar quais variáveis (como tipo de contrato, tempo de fidelidade, valor da fatura) têm um impacto estatisticamente significativo na probabilidade de um cliente cancelar o serviço.
2.  **Quantificar o Impacto:** Medir o quão forte é a influência de cada fator no risco de churn.
3.  **Gerar Recomendações:** Traduzir os resultados da análise estatística em recomendações de negócio acionáveis para a criação de estratégias de retenção de clientes.

## 3. Tecnologias e Bibliotecas Necessárias

Para replicar esta análise, são necessárias as seguintes bibliotecas Python:

* **`pandas`** e **`numpy`**: Para manipulação e análise de dados.
* **`statsmodels`** ou **`scikit-learn`**: Para a construção do modelo de Regressão Logística.
* **`matplotlib`** e **`seaborn`**: Para visualização de dados.

# 📈 Relatório Final: Conclusões e Recomendações Estratégicas

## 📊 Conclusões

A análise estatística revelou, com alto grau de confiança, os principais impulsionadores do churn de clientes na **Connecta Telecom**. Os resultados do modelo de regressão logística confirmam que o cancelamento está fortemente associado a alguns fatores comportamentais e contratuais específicos. O perfil de cliente com **alto risco de churn** é: **cliente recente, com contrato mensal, fatura elevada e serviço de Fibra Óptica**.

Os fatores mais significativos, em ordem de impacto, são:

1.  **Tipo de Contrato:** Clientes com contrato mensal apresentam um risco de cancelamento aproximadamente **195 vezes maior** em relação aos de contratos mais longos. Contratos de dois anos são o principal fator de proteção.
2.  **Tempo de Fidelidade:** Cada mês adicional de permanência reduz a chance de churn em cerca de **5%**, mostrando que os primeiros meses são cruciais para a retenção.
3.  **Valor da Fatura Mensal:** O aumento no valor da fatura mensal eleva o risco de churn em aproximadamente **3% por unidade monetária**, sugerindo sensibilidade a preço.
4.  **Tipo de Serviço de Internet:** O serviço de **Fibra Óptica** aumenta em cerca de **4 vezes** a chance de cancelamento em comparação com o DSL, possivelmente devido a expectativas não atendidas ou à percepção de custo elevado.

## 🚀 Recomendações Acionáveis

Com base nessas conclusões, propõem-se as seguintes ações estratégicas para o time de retenção:

| Recomendação | Justificativa (Baseada nos Dados) | Ação Proposta |
| :--- | :--- | :--- |
| **1. Incentivar a Migração para Contratos de Longo Prazo** | O contrato mensal está associado a um risco **extremamente alto de churn (≈195x)**. | Criar uma campanha promocional para converter clientes mensais em anuais ou bienais, oferecendo incentivos como descontos, bônus de fidelidade ou upgrades temporários de velocidade. |
| **2. Criar um Programa de Fidelização para Novos Clientes** | Cada mês adicional reduz a chance de churn em **5%**. | Implementar um programa de acompanhamento intensivo nos seis primeiros meses, com comunicações personalizadas, suporte proativo e benefícios progressivos para reforçar a satisfação inicial. |
| **3. Revisar a Estratégia de Preços e Valor Percebido** | Faturas mais altas aumentam a chance de churn em **3%** por unidade. | Segmentar clientes com faturas elevadas e realizar uma análise de elasticidade de preço. Ajustar pacotes para melhorar o valor percebido (mais benefícios pelo mesmo preço). |
| **4. Investigar o Churn no Segmento de Fibra Óptica** | Clientes com Fibra têm **4x mais chances de cancelar**. | Conduzir uma pesquisa de satisfação e uma análise técnica detalhada sobre a qualidade do serviço e suporte. Identificar causas de insatisfação e agir sobre problemas de performance ou atendimento. |

A adoção dessas recomendações, baseadas em evidências estatísticas sólidas e profissionais, permitirá à **Connecta Telecom** reduzir substancialmente o churn, aumentar a fidelização e fortalecer sua base de receita recorrente.

