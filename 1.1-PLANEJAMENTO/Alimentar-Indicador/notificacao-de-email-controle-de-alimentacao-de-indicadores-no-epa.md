---
title: "Indicadores – Notificação de email / Monitoramento de alimentação de indicadores no EPA."
id: 3946
slug: "notificacao-de-email-controle-de-alimentacao-de-indicadores-no-epa"
url: "https://wiki.simeon.com.br/notificacao-de-email-controle-de-alimentacao-de-indicadores-no-epa/"
data: "2020-06-23T17:57:11"
modificado: "2021-09-10T17:04:28"
pasta: "1.1-PLANEJAMENTO/Alimentar-Indicador"
categorias:
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

# Indicadores – Notificação de email / Monitoramento de alimentação de indicadores no EPA.
> **Agora nessa versão novos parâmetros foram implementados para que notificação via email sejam disparados ao gestores para que eles alimentem no prazo correto os indicadores de sua responsabilidade.**
> 
> **Essa melhoria ajudará a fazer com que esse processo ocorra de forma mais pontual e de forma automática no EPA.**

O sistema observará a alimentação dos seus indicadores e através de uma data limite que estiver configurada nos parâmetros do sistema, irá disparar três tipos de emails conforme o cenário que o sistema identificar.

Os emails também serão configurados nos parâmetros do sistema do EPA.

**Vamos a configuração dos parâmetros:**

1 – Vá até: **Configuração> parametrização do sistema.**

Neste ambiente selecione:

Menu: Planejamento

Segue a imagem:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5ef2684293467.png)

**Os três tipos de emails que poderão ser configurados para envio são:**

2 – Procure pelo parâmetro: **Configurar Dia do mês limite para verificar a alimentação dos indicadores do mês anterior.**

⇒Insira o dia que você deseja que seja a data limite para a alimentação dos indicadores.

Neste parâmetro o sistema irá verificar essa data e analisar a alimentação dos indicadores do mês anterior a ele.

Segue a imagem:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5ef33ff0720cb.png)

 3 – Procure pelo parâmetro: **Texto padrão para alerta de vencimento do prazo para alimentar o indicador.**

Neste parâmetro você pode configurar um texto que será em forma de lembrete a ser enviado ao gestor por email o lembrando que ele precisa alimentar os indicadores dele.

Se ao chegar na data limite configurada no parâmetro anterior, o sistema ao verificar a alimentação dos indicadores do mês anterior e caso identifique  que há ainda indicadores não alimentados,  será disparado este email com texto lembrete configurado no parâmetro.

> Exemplo de um pequeno trecho de um texto para o Email que você pode colocar no parâmetro:
> 
> _Prezado Gestor, Passando para lembrá-los de que é o último dia para alimentação de seus indicadores referentes ao mês anterior na Plataforma de Gestão – EPA. É de grande importância o preenchimento dos dados para que a possamos analisar e auxiliar nas melhorias necessárias._

Segue a imagem:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5ef33fdb797df.png)

4 – Procure pelo parâmetro: **Texto padrão para alerta de indicadores não alimentados.**

Neste parâmetro você pode configurar um texto que será enviado ao gestor por email o informando que ele ainda não alimentou os indicadores dele.

Ao passar da data limite configurada no parâmetro, se o sistema  verificar que a alimentação dos indicadores do mês anterior não foi realizada ou não está completa, um **e-mail diário** será encaminhado ao gestor responsável informando o cenário, até que ele realize a alimentação.

> Exemplo de um pequeno trecho de um texto para o Email que você pode colocar no parâmetro:
> 
> _Prezado Gestor, Alguns indicadores do mês anterior ainda não estão atualizados na Plataforma de Gestão de Indicadores – EPA. Como informado é de grande importância a alimentação dos dados na Plataforma para que possamos analisar e auxiliar nas melhorias necessárias._

Segue a imagem:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5ef340db14438.png)

5 – Procure pelo parâmetro: **Texto padrão alerta para Parabenizar pelos indicadores alimentados.**

Neste parâmetro você pode configurar um texto que será enviado ao gestor por email o parabenizando pela alimentação dos indicadores dele.

O sistema  verificando que a alimentação dos indicadores do mês anterior foi realizada, um e-mail  será encaminhado ao gestor responsável dando parabéns a ele pela ação.

> Exemplo de um pequeno trecho de um texto para o Email que você pode colocar no parâmetro:
> 
> _Prezado Gestor, Gostaríamos de parabeniza-lo para manter seu painel de indicadores alimentado._

Segue a imagem:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5ef33fcdbc9e0.png)

Qualquer dúvida ou sugestão de melhoria estamos a disposição.

---

Fonte: https://wiki.simeon.com.br/notificacao-de-email-controle-de-alimentacao-de-indicadores-no-epa/
