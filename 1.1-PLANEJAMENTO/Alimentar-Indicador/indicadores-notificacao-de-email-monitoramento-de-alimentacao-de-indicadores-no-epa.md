---
title: "Indicadores – Notificação de e-mail / Monitoramento de alimentação de indicadores no EPA."
id: 16513
slug: "indicadores-notificacao-de-email-monitoramento-de-alimentacao-de-indicadores-no-epa"
url: "https://wiki.simeon.com.br/indicadores-notificacao-de-email-monitoramento-de-alimentacao-de-indicadores-no-epa/"
data: "2025-03-04T14:27:35"
modificado: "2025-03-20T10:21:36"
pasta: "1.1-PLANEJAMENTO/Alimentar-Indicador"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
  - "Alimentar Indicador"
  - "Painel de indicadores"
tags:
  - "automatico"
  - "data desejável"
  - "data limite"
  - "Emails"
  - "gestores"
  - "indicadores"
  - "lembrete"
---

# Indicadores – Notificação de e-mail / Monitoramento de alimentação de indicadores no EPA.
> **![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**
> 
> **Neste artigo, tratamos do envio automático de notificações por e-mail aos gestores, lembrando-os de atualizar, no prazo, os indicadores sob sua responsabilidade. Também foi implementada uma melhoria: agora, a sinalização de baixo desempenho ocorre apenas no último mês do período de apuração, evitando cobranças desnecessárias para indicadores não mensais. A medida torna o processo no EPA mais eficiente e automatizado.**

O sistema acompanhará a atualização dos indicadores e, com base na data limite configurada nos parâmetros, enviará três tipos diferentes de e-mails, dependendo do cenário identificado. Esses e-mails também serão configuráveis dentro dos parâmetros do sistema EPA, permitindo um ajuste personalizado conforme as necessidades da organização.

**Configuração dos Parâmetros:**

1.  **Acesse**: **Configuração → Parametrização do Sistema**.
    
    ![](https://wiki.simeon.com.br/wp-content/uploads/2025/03/img_67d9b78bb589e.png)
    

Dentro desse ambiente, selecione em menu a opção “Planejamento”.

**Veja:** 

![](https://wiki.simeon.com.br/wp-content/uploads/2025/03/img_67d9b7d2a158f.png)

**Configuração de E-mails**

1.  Procure pelo parâmetro: **Configurar Dia do Mês Limite para Verificar a Alimentação dos Indicadores do Mês Anterior.**
2.   Insira o dia desejado como data limite para a alimentação dos indicadores.

Este parâmetro permite que o sistema verifique e analise a alimentação dos indicadores do mês anterior, com base na data limite inserida.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/03/img_67d9b8eb92439.png)

**Configuração do Texto de Alerta para Vencimento do Prazo de Alimentação dos Indicadores**

**Procure pelo parâmetro:** _Texto padrão para alerta de vencimento do prazo para alimentar o indicador._

Neste parâmetro, você pode configurar o texto que será enviado como lembrete por e-mail ao gestor, alertando-o sobre a necessidade de alimentar os indicadores dentro do prazo.

**Veja:** 

![](https://wiki.simeon.com.br/wp-content/uploads/2025/03/img_67d9b9ef779c4.png)

Caso, ao atingir a data limite configurada no parâmetro anterior, o sistema identifique que os indicadores do mês anterior não foram alimentados, será disparado um e-mail com o texto de lembrete configurado nesse parâmetro.

**Exemplo de trecho de texto para o e-mail que pode ser configurado no parâmetro:**

“Prezado Gestor,

Gostaríamos de lembrá-lo de que hoje é o último dia para a alimentação dos seus indicadores referentes ao mês anterior na Plataforma de Gestão – EPA. A atualização dos dados é fundamental para que possamos analisar e fornecer o suporte necessário para as melhorias contínuas.”

**Configurar Texto Padrão para Alerta de Indicadores Não Alimentados**

Procure pelo parâmetro: **Texto Padrão para Alerta de Indicadores Não Alimentados.**

Neste parâmetro, você pode configurar um texto que será enviado ao gestor por e-mail, informando que ele ainda não alimentou os indicadores.

Se, após a data limite configurada no parâmetro anterior, o sistema verificar que a alimentação dos indicadores do mês anterior não foi realizada ou está incompleta, um e-mail diário será enviado ao gestor responsável, informando o cenário, até que a alimentação seja concluída.

Exemplo de trecho de texto para o e-mail:

_“Prezado Gestor,_

_Alguns indicadores do mês anterior ainda não estão atualizados na Plataforma de Gestão de Indicadores – EPA. Como mencionado anteriormente, é de extrema importância a alimentação dos dados na Plataforma para que possamos realizar a análise necessária e apoiar nas melhorias contínuas”._

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/03/img_67d9bad167290.png)

**Texto Padrão para Parabenizar pela Alimentação dos Indicadores**

Procure pelo parâmetro: **Texto Padrão Alerta para Parabenizar pelos Indicadores Alimentados.**

Neste parâmetro, você pode configurar um texto que será enviado ao gestor por e-mail, parabenizando-o pela alimentação dos indicadores.

Quando o sistema identificar que os indicadores do mês anterior foram devidamente alimentados, um e-mail será automaticamente enviado ao gestor responsável como forma de reconhecimento pela ação.

Exemplo de trecho de texto para o e-mail:

_“Prezado Gestor,_

_Gostaríamos de parabenizá-lo por manter seu painel de indicadores atualizado na Plataforma de Gestão – EPA”._

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/03/img_67d9c0400cfb4.png)

**Observações**

Para garantir uma sinalização mais precisa e evitar cobranças indevidas, a regra de indicação de mau desempenho nos e-mails do Diário de Bordo e na Tela Principal foi ajustada para considerar a frequência de alimentação dos indicadores. 

Com a nova regra, a sinalização de indicadores não alimentados ocorrerá apenas no último mês do período correspondente, assegurando que os responsáveis sejam alertados no momento adequado. Além disso, os indicadores serão sinalizados cinco dias antes do vencimento da frequência, permitindo um melhor acompanhamento e tomada de decisão. Essa atualização visa aprimorar a usabilidade do sistema e tornar as notificações mais eficientes e alinhadas à realidade dos diferentes tipos de indicadores.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/03/img_67c737fe160eb.png)

---

Fonte: https://wiki.simeon.com.br/indicadores-notificacao-de-email-monitoramento-de-alimentacao-de-indicadores-no-epa/
