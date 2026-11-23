---
title: "Solicitações – Notificações por SMS nos encaminhamentos."
id: 3869
slug: "disparo-de-sms-encaminhamento-de-fases"
url: "https://wiki.simeon.com.br/disparo-de-sms-encaminhamento-de-fases/"
data: "2020-06-19T08:38:47"
modificado: "2020-10-06T08:20:30"
pasta: "1.5-PORTAL/1.5.2-PRODUTIVIDADE/Solicitações"
categorias:
  - "Solicitações"
tags:
---

# Solicitações – Notificações por SMS nos encaminhamentos.
> _\* Essa funcionalidade só estará disponível aos clientes que aderirem ao Pacote de envio de SMS. Para saber mais, consulte nossa equipe comercial._

>      **Agora você pode _receber notificações via SMS_ em seu celular, no momento em que uma determinada solicitação for encaminhada para uma fase específica!**
> 
> **Você receberá uma mensagem e ficará atento as movimentações que estão acontecendo nas suas solicitações.**
> 
> **Esta nova funcionalidade, poderá ser utilizada também como processo para que Clientes possam dar o feedback e _concluir solicitações_ com uma ação simples através do próprio celular!**

Usuários que poderão ser configurados para receber SMS de notificações:

-   _Usuários com login de Painel do Cliente, (Pessoa física e jurídica),_
-   _Gestores, (gestor do executor e gestor do responsável),_
-   _Solicitante,_
-   _Responsável._

**Vamos as configurações para uso desta funcionalidade:**

-   **Configurando número do celular para receber SMS do sistema.**

1 – As  pessoas que irão receber os SMS a partir do módulo de solicitações precisam ter o número de celular configurados no módulo de cadastro de pessoas. O número precisa estar configurado corretamente com DDD+número de celular no **campo: Celular**, tanto para pessoas físicas ou jurídicas no EPA.

_Caminho: Configuração>Usuários>gerenciar usuários> editar o cadastro de pessoa._

Observação: Número do celular deve conter os 11 dígitos.

Segue a imagem:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecba3514299.png)

-   **Configurando nova parametrização do sistema**

2 – Vá até parametrização do sistema, e no menu selecione: solicitações, encontre o parâmetro:

-   **Ativa o envio de SMS’s para o encaminhamento da solicitação.**

E altere o valor para SIM.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbae7a126e.png)

-   **Configurando fase para receber a nova funcionalidade do SMS**

3 – Agora você precisa configurar a fase (em configurações de tipo de solicitação ou serviço) que você deseja que o destinatário configurado  receba notificação via SMS.

Caminho: Configuração> Portal > Solicitações > Tipo de solicitações.

-   Acesse um tipo de solicitação,
-   Escolha o tipo de fluxo que deseja configurar a fase: individual (tipo de serviço) ou fluxo do tipo de solicitação,
-   Escolha a fase que deseja configurar para receber a funcionalidade:
-   Edite a fase -> Ao editar a fase, na aba de _INFORMAÇÕES BÁSICAS_,  você encontrará um fleg: _Fase de Finalização._ Marque ele  e clique em _SALVAR._

Segue a imagem com a configuração:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbb3d5169b.png)

4 – Ainda na edição da fase em questão, há uma nova Aba chamada: Envio de SMS, clique nela e prossiga com a configuração:

-   Selecione o fleg: Enviar SMS quando solicitação for encaminhada para esta fase.
-   Selecione o Destinatário que irá receber o SMS! Observação: você poderá marcar mais de um destinatário.
-   No campo de texto abaixo, elabore o texto que você deseja que seja entregue no SMS ao destinatário.

Segue o exemplo:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbc6354ff0.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbdb9dee0c.png)_Dica: Você pode utilizar duas variáveis disponíveis neste campo que levará ao SMS o nome do cliente e o link para acesso ao feedback da solicitação._ 

_Para inserir essas variáveis no texto, digite # (jogo da velha), o sistema mostrará as opções para você inserir._

#NomeCliente:  nome do cliente na mensagem,

_#LinkFeedback :    link com o feedback para acesso no celular._

Após estas configurações e clique em salvar.

Configurado a fase desejada, no momento em que a solicitação for encaminhada para a fase em questão, o SMS será disparado para os destinatários configurados.

-   **Solicitação**

5 – Quando o SMS for disparado em uma solicitação, o histórico dessa ação será gravada na _aba histórico na solicitação_ e também ficará registrado no _relatório de solicitação._

Segue a imagem:

**Histórico na solicitação**

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecce0f1dac4.png)

**Histórico Relatório de solicitações**

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecce8586a57.png)

Quando você configurar a fase para que esta seja uma fase de finalização e no SMS  conter o link de acesso ao feedback para o destinatário, uma tela de interação será aberta no navegador do celular, no momento em que o usuário clicar no link.

> Os Clientes poderão concluir e dar o seu feedback em uma solicitação acessando o link de acesso que será enviado junto com o texto SMS para o seu número de celular.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eeccad843390.png)

**Imagem ilustrativa**

Nessa tela em seu navegador ele poderá registrar seu feedback, podendo inserir também comentários, finalizando a ação a solicitação será concluída no EPA.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecca9dc8c16.png)**Imagens ilustrativa**

Qualquer dúvida estamos a disposição!

---

Fonte: https://wiki.simeon.com.br/disparo-de-sms-encaminhamento-de-fases/
