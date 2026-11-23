---
title: "Ocorrências – Dashboard Ocorrências"
id: 1912
slug: "dashboard-ocorrencias"
url: "https://wiki.simeon.com.br/dashboard-ocorrencias/"
data: "2019-04-08T17:17:18"
modificado: "2025-08-06T14:16:02"
pasta: "1.3-POLÍTICAS-DE-QUALIDADE/Ocorrências/08-Monitorar-Relatório"
categorias:
  - "08- Monitorar/Relatório"
tags:
  - "dashboard"
  - "Frequência Absolut"
  - "gráfico de linha"
  - "Gráfico de Pareto"
  - "graficos"
  - "o dashboard"
  - "ocorrências"
  - "versao129"
---

# Ocorrências – Dashboard Ocorrências
![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_6439ade81e929.png)

No Dashboard Ocorrência são apresentadas algumas caixinhas mostrando a quantidade de ocorrências em andamento, ações em andamento, ocorrências em avaliação de eficácia, ocorrências atrasadas. Nas demais caixinhas mostra o tempo médio.

O dashboard irá apresentar:

![](https://wiki.simeon.com.br/wp-content/uploads/2019/04/img_5cabaa4161224.png)

**Cada box considera um cálculo:**

-   **Tempo Médio para Alterar Descrição =** data encaminhamento para Alterar Descrição- data do próximo encaminhamento;
-   **Tempo Médio para Revisar Análise de Causa e Plano de Ação =** data encaminhamento para revisão – data do próximo encaminhamento;
-   **Tempo Médio para Validar Análise de Causa e Plano de Ação =** data Avaliar Ocorrência – data do próximo encaminhamento;
-   **Tempo médio para Registrar Ação Imediata notificada =** Data da Ação da Unidade Notificada – data de inclusão da ocorrência;
-   **Tempo Médio para Executar Ações =** data encaminhamento para Execução – data do próximo encaminhamento;
-   **Tempo Médio para Revisar Execução das Ações =** data encaminhamento para Revisão- data do próximo encaminhamento.

**A Nuvem de Palavras:**

E seguido da nuvem de palavras e os gráficos pré-definidos para acompanhar o desenvolvimento das ocorrências registradas, os gráficos são **por Ocorrências por Tipo, Ocorrências por categoria, Ocorrências por Severidade, Ocorrências por Unidade, Ocorrências por Unidade Notificadora, Tipo de Incidente, Grupo de Risco e Ocorrências por Classificação.**

![](https://wiki.simeon.com.br/wp-content/uploads/2019/04/img_5cabab942aa1a-e1681936664132.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2019/04/img_5cababb373df0.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2019/04/img_5cababd85512a.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2019/04/img_5cababfa6d1c3-e1681936696257.png)

**Gráfico de Pareto:**

Também conhecido como regra do 80/20.  
Prega a teoria de que aproximadamente 80% dos problemas vem somente de 20% das causas possíveis.

-   **Uso:**

Ele ordena as frequências das ocorrências (Colunas), da maior para a menor. Em sobreposição é criada um gráfico de linha que apresenta a porcentagem acumulada, somatório o atual com o anterior.

-   **Construção do Gráfico:**

Uma vez que as ocorrências mais frequentes são identificadas, e ordenadas em decrescente.

-   **Criasse a tabela de análise:**

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_64404f35202ac.png)

Em seguida são calculados os valores de porcentagem individual:

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_64405027759f9.png)

São calculados os valores de porcentagem acumulada:

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_6440509e96c58.png)

-   **Criando o Gráfico:**

A “Frequência Absoluta” é usada para o gráfico de barras  
A “% Acumul.” é usada para o gráfico de linha  
A “% Indiv.” é mostrada somente na caixa de informações do hoverEvent.

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_644050ccd5dd6-e1681936609532.png)

**Atenção:** O gráfico de **Ocorrências por Título** irá pegar os 20 primeiros títulos com os maiores valores em quantidade de ocorrências, considerando os filtros aplicados.

![](https://wiki.simeon.com.br/wp-content/uploads/2021/10/cropped-img_615eeaf4e896e.png)

---

Fonte: https://wiki.simeon.com.br/dashboard-ocorrencias/
