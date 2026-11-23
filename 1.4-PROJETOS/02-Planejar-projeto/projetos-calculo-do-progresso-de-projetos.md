---
title: "Projetos – Cálculo do Progresso de Projetos"
id: 17307
slug: "projetos-calculo-do-progresso-de-projetos"
url: "https://wiki.simeon.com.br/projetos-calculo-do-progresso-de-projetos/"
data: "2025-05-04T19:35:01"
modificado: "2025-09-19T15:27:03"
pasta: "1.4-PROJETOS/02-Planejar-projeto"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
  - "02- Planejar projeto"
tags:
---

# Projetos – Cálculo do Progresso de Projetos
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Nesse artigo, vamos falar sobre como o sistema realiza automaticamente o cálculo do progresso de um projeto. Acompanhar o progresso é essencial para garantir que o projeto seja concluído dentro do prazo e atenda aos padrões de qualidade estabelecidos. Uma medição precisa permite identificar desvios, promover ajustes necessários e manter o projeto alinhado aos seus objetivos.**

#### **Progresso Previsto**

O **progresso previsto** **da tarefa** representa quanto de uma tarefa _deveria_ estar concluída em um determinado momento, com base nas datas de início e fim.

-   O sistema verifica a data de início e a data de término de cada tarefa para calcular o período total da tarefa.
-   Em seguida, compara esse período com a data atual.
-   Se a data atual estiver dentro do intervalo da tarefa, o sistema calcula automaticamente o percentual proporcional do tempo previsto que já passou.

Exemplo de cálculo do previsto de cada tarefa:

<table style="border-collapse: collapse; width: 100%;" border="1"><tbody><tr><td style="width: 25%;"><span style="font-family: arial, helvetica, sans-serif;"><strong>Tarefa</strong></span></td><td style="width: 25%;"><span style="font-family: arial, helvetica, sans-serif;"><strong>Data Inicio&nbsp;</strong></span></td><td style="width: 25%;"><span style="font-family: arial, helvetica, sans-serif;"><strong>Data Fim&nbsp;</strong></span></td><td style="width: 25%;"><span style="font-family: arial, helvetica, sans-serif;"><strong>Dias</strong></span></td></tr><tr><td style="width: 25%;"><span style="font-family: arial, helvetica, sans-serif;">Tarefa Exemplo</span></td><td style="width: 25%;"><span style="font-family: arial, helvetica, sans-serif;">01/05/2025</span></td><td style="width: 25%;"><span style="font-family: arial, helvetica, sans-serif;">10/05/2025</span></td><td style="width: 25%;"><span style="font-family: arial, helvetica, sans-serif;">10 dias</span></td></tr></tbody></table>

Se hoje for **05/05/2025**, significa que já se passaram **5 dias** desde a data de início.

Nesse caso, o sistema entende que a tarefa deveria estar **50% concluída**, pois:

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_681e422dcf6a1.png)

Regras adicionais:

-   Se **a data atual for maior que a Data Fim**, o previsto será **100%**.
    
-   Se **a data atual for menor que a Data Início**, o previsto será **0%**.
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_6821fa1b70ecd.png)

Para calcular o **percentual previsto do projeto**, o sistema utiliza a **média ponderada** do previsto de cada tarefa, considerando os pesos atribuídos a elas.

Existem três diferentes tipos de peso, que podem ser vinculados a uma tarefa, são eles:

Tipos de peso possíveis para uma tarefa:

-   **Baixo** → Peso **1**
    
-   **Médio** → Peso **2**
    
-   **Alto** → Peso **3**
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_6821f283defcc.png)

O sistema aplica a seguinte fórmula:

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_681e446797e6c.png)

Onde:

-   **% Previsto da Tarefa**: é o percentual calculado com base no tempo decorrido (como explicado anteriormente).
    
-   **Peso da Tarefa**: é o valor atribuído conforme a importância da tarefa (baixo, médio ou alto).
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_6821fbe230565.png)

**Progresso Executado**

O progresso executado mostra quanto do projeto já foi **efetivamente concluído**, com base nas tarefas realizadas. Esse cálculo também leva em conta a o **peso** **de cada tarefa**, utilizando os percentuais de conclusão informados pelo usuário ou os percentuais de conclusão atribuídos automaticamente pelo sistema de acordo com o status da tarefa.

-   Primeiro multiplica-se o percentual de conclusão de cada tarefa pelo seu peso.
    
-   Em seguida, soma-se o resultado de todas as tarefas.
    
-   E depois, divide-se essa soma pela soma total dos pesos.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_6821f1eb314f8.png)

O sistema aplica a seguinte fórmula:

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_681e4591eaf4b.png)

Onde:

-   **% Concluído da Tarefa**: valor que representa o andamento da tarefa. Esse valor pode ser:
    
    -   Informado manualmente pelo usuário.
        
    -   Atribuído automaticamente pelo sistema, com base no status atual da tarefa.
        
-   **Peso da Tarefa**: grau de importância atribuído à tarefa (1 = baixo, 2 = médio, 3 = alto).
    

**Desvio**

O desvio mostra a **diferença entre o que era previsto e o que foi executado** no projeto até o momento. Ele serve para identificar o andamento do projeto.

-   **Desvio positivo** → o projeto está **adiantado**.
    
-   **Desvio igual a zero** → o projeto está **no prazo**.
    
-   **Desvio negativo** → o projeto está **atrasado**.
    

O sistema aplica a seguinte fórmula:

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_681e482f88a17.png)

Onde:

-   **% Executado do Projeto**: resultado do cálculo com base no andamento real das tarefas (informado pelo usuário ou pelo sistema).
    
-   **% Previsto do Projeto**: valor calculado automaticamente com base no tempo decorrido de cada tarefa e seus pesos.
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_6817eb7e9f6ee.png)

#### **Considerações Importantes**

No cálculo do **progresso previsto** e **executado**, **somente as seguintes tarefas são consideradas**:

-   Tarefas **em andamento**
    
-   Tarefas **planejadas** (_será considerado no calculo somente se o parâmetro do sistema **Considerar as tarefas que estão com status de Planejado, no cálculo da Criticidade e do Realizado do projeto?** estiver como **Sim**_)
    
-   Tarefas **suspensas**
    
-   Tarefas **concluídas**
    

As tarefas com status **em planejamento** e **canceladas** **não são consideradas** no cálculo.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/03/img_67c87b79c4bf5.png)

---

Fonte: https://wiki.simeon.com.br/projetos-calculo-do-progresso-de-projetos/
