---
title: "Solicitações – Tempo Restante de Execução das Fases na Tela Principal do EPA"
id: 14009
slug: "solicitacoes-tempo-restante-de-execucao-das-fases-na-tela-principal-do-epa"
url: "https://wiki.simeon.com.br/solicitacoes-tempo-restante-de-execucao-das-fases-na-tela-principal-do-epa/"
data: "2023-04-28T08:39:53"
modificado: "2023-05-16T14:10:17"
pasta: "0.1-NOVIDADES-VERSÃO-EPA"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
tags:
  - "box sol minha unidade"
  - "box solicitações"
  - "box tela principal"
  - "Solicitações"
  - "Tempo restante fases"
---

# Solicitações – Tempo Restante de Execução das Fases na Tela Principal do EPA
![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/Imagens-Engracado-PNG-e-Vetor_-com-Fundo-Transparente-Para-Download-Gratis-_-Pngtree-removebg-preview-164x300.png)

**Possibilidade de acompanhamento sobre o tempo restante de execução por fase em solicitações no EPA.**

**Isto a partir das caixas box do módulo na tela principal.**

## _**Veja como utilizar:**_

**1 –** Acessando a tela principal do EPA, os box disponíveis para acompanhamento das solicitações: **Solicitações** e **Sol. Minha Unidade** apresentarão o **Tempo Restante para Execução da Fase Atual** das solicitações no EPA.  

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_644bc2538c38d.png)

↓

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_644bc60a234fc.png)

## _**CONFIGURAÇÃO PARA APRESENTAÇÃO DO TEMPO RESTANTE DAS FASES  
**_

**2 –** Para que a visualização do tempo restante da fase da solicitação apareça no box, é preciso realizar a configuração de horas em cada fase do fluxo da solicitação. Para assim o EPA entender e realizar o cálculo para acompanhamento do tempo restante.

-   -   Acesse o ambiente de configuração do tipo de solicitações no EPA: _**Configuração> Portal> Produtividade> Solicitações> Tipo Solicitações**_.

-    
    -   Após isso, veja se o tipo de solicitação segue o fluxo individual ou fluxo coletivo por tipo de solicitação.
        -   Caso seja fluxo individual por tipo de serviço, acesse a configuração do tipo de serviço>aba fases e defina as horas para cada fase,
        -   Caso seja fluxo coletivo por tipo de solicitação, edite o tipo de solicitação e acesse a aba: fases e defina as horas para cada fase listada.
-    
    -   Acesse a aba de fases do tipo de fluxo escolhido e edite cada fase para inserção do prazo de execução em horas:

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_644bcc461dc0d.png)

**3 –** Após configurar a **Previsão de Horas** nas fases do fluxo da solicitação, quando a solicitação for criada e estiver passado pelos encaminhamentos configurados o EPA já calculará o Tempo Restante de execução planejado para tal.

**4 –** Para apresentação das horas no box da tela principal o EPA realiza os seguintes cálculos:

-   -   **HORA DO ENCAMINHAMENTO:** Hora que a solicitação foi encaminhada para tal fase;
    -   **HORA ATUAL DO COMPUTADOR:** Horário Oficial em que se encontra o computador no momento e que será encaminhada a sol para uma nova fase,;
    -   **TEMPO DA FASE:** Previsão de Horas configuradas na fase da solicitação;
    -   **HORA DO MENOR ENCAMINHAMENTO DA FASE:** Menor tempo registrado do Horário Oficial em que a sol. foi encaminhada no fluxo para uma nova fase.

Com isso o Tempo Restante da fase se encontra na seguinte fórmula:

> Tempo Restante = (**TEMPO DA FASE** – (**HORA ATUAL DO COMPUTADOR** – **HORA DO ENCAMINHAMENTO**))

#### Veja o Exemplo:

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_644bd1e6d81a8.png)

↓

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_644bd232c13ac.png)

> **Tempo Restante** = (06:00 – (10:56 – 10:03))
> 
> **Tempo Restante** = 06:00 – 00:53
> 
> **Tempo Restante** = 05:08hrs

-   Tem se um 2.º cenário de cálculo que ocorre quando uma solicitação passou pelo encaminhamentos de algumas fases, e em algum momento e motivo ela teve que retornar a uma fase que ela já havia sido executada.

-   Quando uma sol retorna a uma fase anterior que ela já tinha sido trabalhada, o EPA não disponibilizará novamente a essa fase a previsão de horas completa que ela possui configurada. É feito um cálculo para abater o período já trabalhado antes e o tempo restante ser condizente ao fluxo de trabalho na sol.

#### Ao retornar a fase já trabalhada o Tempo Restante da fase se encontra na seguinte fórmula:

> Tempo Restante = **(TEMPO DA FASE – (HORA ATUAL DO COMPUTADOR – HORA DO MENOR ENCAMINHAMENTO DA FASE))**

#### Veja o Exemplo:

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_644bd6bd41665.png)

#### ↓

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_644bd8b16c7a2.png)

↓

![](https://wiki.simeon.com.br/wp-content/uploads/2023/04/img_644bdac2b3674.png)

> Tempo Restante = **(TEMPO DA FASE – (HORA ATUAL DO COMPUTADOR – HORA DO MENOR ENCAMINHAMENTO DA FASE))**
> 
> Tempo Restante = **(06:00 – (11:22 – 10:03))**
> 
> Tempo Restante = **06:00 – 01:19  
> **
> 
> Tempo Restante = **04:42hrs**

# ![](https://wiki.simeon.com.br/wp-content/uploads/2023/03/img_6411defcee7b8-e1682602713557.png)Observação:

-   Quando configurado na fase no campo previsão de horas um tempo **maior que 08:00hrs**, a apresentação do tempo restante no box das solicitações aparecerá em dias.

-   Porém quando configurado na fase no campo previsão de horas um tempo **menor que 08:00hrs,** a apresentação do tempo restante no box das solicitações aparecerá em horas.

#### **Aproveite essa melhoria!**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos à disposição!**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_62191d147280f.png)

---

Fonte: https://wiki.simeon.com.br/solicitacoes-tempo-restante-de-execucao-das-fases-na-tela-principal-do-epa/
