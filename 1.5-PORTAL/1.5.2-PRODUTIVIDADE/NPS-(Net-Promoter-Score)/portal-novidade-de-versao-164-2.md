---
title: "Portal – Novidade de Versão 164"
id: 12583
slug: "portal-novidade-de-versao-164-2"
url: "https://wiki.simeon.com.br/portal-novidade-de-versao-164-2/"
data: "2022-11-03T16:37:24"
modificado: "2022-11-23T09:50:16"
pasta: "1.5-PORTAL/1.5.2-PRODUTIVIDADE/NPS-(Net-Promoter-Score)"
categorias:
  - "NPS (Net Promoter Score)"
  - "Pesquisa/Questionários"
tags:
  - "Configure um layout envio automático das pesquisas no EPA:"
  - "Envio de um único e-mail aos participantes contendo os links de todos os questionários desejados a serem respondidos."
  - "Envio Questionários automáticos no EPA"
  - "pesquisas"
  - "Preencher o questionário com a última resposta do participante"
  - "respostas pesquisas"
---

# Portal – Novidade de Versão 164
![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/Imagens-Engracado-PNG-e-Vetor_-com-Fundo-Transparente-Para-Download-Gratis-_-Pngtree-removebg-preview-164x300.png)

**Veja as principais alterações da versão 164 em Portal.**

**Portal > Pesquisas** 

-   _**Nova funcionalidade Envio Questionários automáticos no EPA:** Envio de um único e-mail aos participantes contendo os links de todos os questionários desejados a serem respondidos._

-   -   Nesta versão será possível configurar um layout e selecionar os questionários a serem enviados juntos aos participantes via E-mail,
-    
    -   Quando configurado ‘N’ questionários para este tipo de envio, o respondente ao finalizar o preenchimento das  respostas de 1 pesquisa, automaticamente o sistema abrirá a próxima pesquisa configurada para que ele possa continuar a responder.
-    
    -   Esta funcionalidade de envio automático é ativa no EPA a partir da configuração do Extrator,
-    
    -   A configuração do layout é realizada no EPA a partir do caminho: **Configuração> Portal> Comunicação> Pesquisas> Envio Automático:**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_63640cc8dc292.png)

**Configure um layout envio automático das pesquisas no EPA:**

1.  1.  Insira hora inicio e fim,

1.  1.  Insira o texto a ser enviado no corpo do  e-mail,
    2.  Selecione as pesquisas desejadas a serem enviadas,
    3.  Configure o respectivo SQL no Extrator para os envios automáticos.
        1.  Campos utilizando e Sqls Pesquisas no EPA: (_questionario\_id, data\_envio, questionario\_usuario\_agendamento\_envio, envio\_automatico\_id, cliente\_id)_

![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_63640db254878.png)

-   Após a configuração do extrator e configuração do layout no EPA para envio dos E-mails, os participantes receberão os e-mails:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_636bd4a7de219.png)

# Atenção:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/08/rodeo-e1662764238671-254x300.png)Observação importantes sobre essa melhoria:

-   A pesquisa deve estar ativa.
-   A pesquisa deve ter as datas (Data Início e Data Fim) definidas.
-   A pesquisa NÃO pode ser do tipo NPS ou Avaliação Comportamental.
-   A pesquisa deve ao menos 1 participante vinculado.
-   O participante NÃO pode já ter recebido um envio de pesquisa na data atual.

-   __**Nova funcionalidade: Preencher o questionário com a última resposta do participante.**__

-   -   _Com esta nova funcionalidade quando o participante for solicitado novamente a responder um mesmo questionário no EPA, ao abrir o formulário do respectivo questionário, o sistema apresentará as respostas anteriores que ele já incluiu da última vez que respondeu._

-   -   _Quando o participante finalizar o preenchimento das respostas deste questionário o EPA salvará o questionário como um formulário com novas respostas._
-    
    -   Edite um questionário e selecione o check para ativar a funcionalidade:

**Preencher com a última resposta do participante.**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_63642628130c6.png)

# Atenção:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/08/rodeo-e1662764238671-254x300.png)Esta funcionalidade não será aplicada nos questionários quando:

-   Se em Informações Básicas, Opções, o checkbox “_Preencher com a última resposta do participante_” não estiver marcado,
-   Se em Informações Básicas, Opções, o checkbox “_Responder com único usuário_” estiver marcado,
-   Se na aba de Participantes, tabela, o checkbox da opção “_Responder Novamente_” estiver marcada,
-    Se o questionário for do tipo “_Avaliação Comportamental_“,
-    Se estiver editando a resposta de outro participante dentro do ambiente: Resultados,
-   Se não houverem respostas anteriores na pesquisa.

# **Portal > NPS**

-   _**Melhoria na Listagem dos comentários de uma pesquisa NPS.**_

Nesta Versão a listagem dos comentários recebidas na campanha NPS ganhou a apresentação de algumas informações adicionais.

-    
    -   -   Você poderá acompanhar as notificações sobre os registros de atendimento e gols ou bola fora que foram vinculados aos comentários.
        -   Caso queira acessar o registro de atendimento, é só clicar no código apresentado na listagem.
        -   Caso queira acessar o gol ou o bola fora é só clicar na notificação apresentada na listagem.
        -   No botão ações, você conseguirá acessar o formulário pessoa do participante.

-   -   Veja em: _Portal> Produtividade> NPS> Campanhas> Resultados da Campanha NPS:_

![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_63651af765223.png)

# **Portal > Solicitação**

_**Nova forma de direcionamento, 1° encaminhamento automático ao Gestor no EPA.**_

-   -   Nesta versão o EPA ganhou uma nova opção para que quando uma solicitação seja criada no EPA, ela possa ser encaminhada  automaticamente para o Gestor do Solicitante.
    -   Assim, o gestor receberá a solicitação, analisará e dará andamento ao executor para seguir com o tratamento, após avaliada. 

**Configuração:**

-   -   -   Para ativar esta funcionalidade acesse o ambiente de configuração: Tipo de Solicitação.

-   -   -   -   _1 – Configuração> produtividade> solicitações> tipos de solicitações> Edite **a primeira fase** do tipo de solicitação ou serviço._
            -   2 – Na primeira fase, edite a aba ![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_6369566e1a42f.png) e na respectiva unidade gerencial inserida para encaminhamento, selecione a opção:  ![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_636956aba17bb.png).
        -    
            -   Após isso, as novas solicitações criadas no EPA com esse tipo, serão encaminhadas automaticamente aos gestores dos solicitantes.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_63695cda7adac.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_63695d249f12f.png)

# Atenção:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/08/rodeo-e1662764238671-254x300.png)Esta funcionalidade não será aplicada quando:

-   Para o 1° encaminhamento automático da solicitação ao gestor, o EPA filtra os gestores configurados para a Unidade Gerencial do Solicitante e seleciona o 1° a partir do seu nome por Ordem Alfabética.

-   O Encaminhamento automático ao Gestor só funcionará na primeira fase da solicitação.
    -   As demais fases não serão impactadas.

#### **Aproveite essa melhoria!**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos à disposição!**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_62191d147280f.png)

---

Fonte: https://wiki.simeon.com.br/portal-novidade-de-versao-164-2/
