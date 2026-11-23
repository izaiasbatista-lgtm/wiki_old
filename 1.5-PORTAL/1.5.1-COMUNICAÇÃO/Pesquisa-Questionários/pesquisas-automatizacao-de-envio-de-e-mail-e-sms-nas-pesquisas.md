---
title: "Pesquisas – Automatização de envio de E-mail e SMS nas Pesquisas"
id: 10862
slug: "pesquisas-automatizacao-de-envio-de-e-mail-e-sms-nas-pesquisas"
url: "https://wiki.simeon.com.br/pesquisas-automatizacao-de-envio-de-e-mail-e-sms-nas-pesquisas/"
data: "2022-06-13T16:19:35"
modificado: "2023-09-04T12:30:53"
pasta: "1.5-PORTAL/1.5.1-COMUNICAÇÃO/Pesquisa-Questionários"
categorias:
  - "Pesquisa/Questionários"
tags:
  - "disparo automatico da pesquisa"
  - "email"
  - "Envio Automático"
  - "envio automatico pesquisa"
  - "extrator pesquisa"
  - "pesquisa"
  - "Preencher com a última resposta do participante"
  - "questionário envio automatico"
  - "sms"
---

# Pesquisas – Automatização de envio de E-mail e SMS nas Pesquisas
**![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/Imagens-Engracado-PNG-e-Vetor_-com-Fundo-Transparente-Para-Download-Gratis-_-Pngtree-removebg-preview-164x300.png)**

**O módulo de pesquisas ganhou a possibilidade de disparar a pesquisa aos respondentes de forma automática no EPA, via E-mail ou SMS.**

**A automatização envolve uma configuração  no Extrator, e com a configuração na pesquisa os disparos acontecem aos participantes.**

**Essa melhoria, é mais um facilitador na configuração das pesquisas do EPA e auxiliará você no controle e gestão dos questionários disparados aos seus clientes, agora sendo de forma automática!**

**1 –** Crie ou acesse uma pesquisa que deseje configurar envio automático do questionário aos participantes.

_**Siga: Portal> Pesquisas> Crie ou edite uma pesquisa.**_

**2 –** Na presente pesquisa, configure os campos das **informações básicas**, principalmente o **período entre datas** em que a pesquisa acontecerá.

_\* O preenchimento das datas do período da pesquisa são obrigatórias para a funcionalidade de envio de pesquisas automáticas aos participantes._

Atenção marque a opção:

-   **Responder com único usuário (usuário geral para evitar identificação),**  quando o participante for responder novamente o mesmo questionário no EPA, o sistema apresentará todas as respostas em branco, independentemente das respostas anteriores que ele possa ter inserido.
-   **Preencher com a última resposta do participante,** quando o participante for responder novamente o mesmo questionário no EPA, o sistema apresentará as respostas anteriores que ele já incluiu da última vez que respondeu.  
    Após o participante concluir o preenchimento das respostas neste questionário, o EPA salvará o questionário com as novas respostas.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62a791599ae1e.png)

**3 –**  Para inserir os participantes é necessário que esteja configurado a automatização de importação de clientes no extrator, verificar no passo **6**.

**4 –** Após inserir os participantes no botão de ações você poderá utilizar algumas opções para cada participante de forma manual do sistema.

Por exemplo, enviar a pesquisa de forma individual ou reenvia-la para um participante responder.

Veja as opções:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62a79660c0b9c.png)

-   -   **Enviar Pesquisa por E-mail:** Esta opção envia ao e-mail do participante a respectiva pesquisa. No Corpo do e-mail estará presente o botão/link de acesso ao formulário de respostas da pesquisa.

-   -   **Enviar Pesquisa por SMS:** Esta opção envia um SMS ao celular do participante com o link para responder a respectiva pesquisa. No SMS estará presente o link de acesso para o formulário de respostas da pesquisa.

-   -   **Gerar Link/QR code:** Esta opção gera ao usuário que está configurando a pesquisa, gerar um Qr code de acesso ou o Link de acesso direcionador que contém o formulário de respostas ao participante selecionado. Assim ele poderá compartilhar uma destas opções com o participante selecionado e o participante responder a pesquisa via dispositivos móveis.
        -   Lembrando que o link e o QR Code são individuais, cada participante deve receber referente ao seu usuário.

-   -   **Remover Participante:** Esta opção remove o participante da ação responder a pesquisa.

**5 –**Após inserir os participantes, você pode configurar o envio automático de questionários por e-mail. Isso pode ser feito de duas maneiras:

Enviando um e-mail separado para cada questionário, se o participante for responder a eles em momentos diferentes **(Seguir o passo 5.1)**;

Ou agrupando todos os questionários em um único e-mail, caso o participante precise responder a vários questionários simultaneamente **(Seguir o passo 5.2)**.

-   **5.1.** Para o questionário ser enviado um por e-mail, acesse a nova aba:![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62a79e16934a4.png) e nela insira as informações:

**5.1.1.  Hora inicio e Hora Fim:** Estes horários informarão ao sistema em qual horário que esta pesquisa será disparada aos participantes configurados.

**5.1.2. Tipo de Envio – E-mail, SMS, Email e SMS:**

-   -   -   -   Ao selecionar E-mail, o sistema enviará a pesquisa aos participantes via e-mail cadastrado no formulário do cliente.
            -   Se selecionado SMS, o formulário para resposta da pesquisa será enviado ao número de celular cadastrado no formulário do cliente.
            -   E ao escolher a opção E-mail e SMS, o EPA tentará enviar a pesquisa para o participante por e-mail e se não conseguir enviar por esse modo irá disparar e envia a pesquisa por SMS.

**5.1.3.** Para o envio da pesquisa aos participantes via e-mail, você poderá configurar um texto personalizado para que seja apresentado no corpo do e-mail juntamente com o link de acesso à pesquisa.

Crie um texto personalizado para acompanhar o e-mail no campo: Layout do E-mail.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62a79f2a671db.png)

Após realizar essa configuração, clique em **Salvar Configuração**.

## ![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62a0b1f846459-195x300.png)Observação

Lembrando que a configuração informada na aba: ![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62a79e16934a4.png) só irá funcionar quando:

-   -   -   -   -   Período de datas estiver configurado na aba de informações básicas na pesquisa,
                -   Configuração SQL realizada no extrator.

-   **5.2.** Para fazer o envio de um único e-mail aos participantes contendo os links de todos os questionários desejados a serem respondidos.

Quando configurado ‘N’ questionários para este tipo de envio, o respondente ao finalizar o preenchimento das  respostas de 1 pesquisa, automaticamente o sistema abrirá a próxima pesquisa configurada para que ele possa continuar a responder.

Esta funcionalidade de envio automático é ativa no EPA a partir da configuração do Extrator.

**5.2.1.** A configuração do layout é realizada no EPA a partir do caminho: **Configuração> Portal> Comunicação> Pesquisas> Envio Automático.**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_63640cc8dc292.png)

**5.2.2.** Configure um layout envio automático das pesquisas no EPA:

-   -   -   Insira **hora inicio e fim**;
        -   Insira o **texto a ser enviado no corpo do  e-mail**;
        -   **Selecione as pesquisas** desejadas a serem enviadas;
        -   Configure o respectivo SQL no Extrator para os envios automáticos.
            -   Campos utilizando e Sqls Pesquisas no EPA: (_questionario\_id, data\_envio, questionario\_usuario\_agendamento\_envio, envio\_automatico\_id, cliente\_id)_

![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_63640db254878.png)

**5.2.3.** Após a configuração do extrator e configuração do layout no EPA para envio dos E-mails, os participantes receberão os e-mails:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/11/img_636bd4a7de219.png)

# Atenção:

Observação importantes sobre essa melhoria:

-   -   -   A pesquisa deve estar ativa.
        -   A pesquisa deve ter as datas (Data Início e Data Fim) definidas.
        -   A pesquisa NÃO pode ser do tipo NPS ou Avaliação Comportamental.
        -   A pesquisa deve ao menos 1 participante vinculado.
        -   O participante NÃO pode já ter recebido um envio de pesquisa na data atual.

# EXTRATOR WEB

**6 –** O primeiro a ser feito é configurar no extrator uma consulta informando o código do questionário que será automatizado e data do envio.

-   -   **6.1.** Acesse o extrator pelo caminho: **Planejamento> Funcionalidades> Extrator EPA.**

-   -   **6.2.** Edite a página de configuração, para inserir a SQL para automatizar este processo, insira a SQL para inserção dos participantes do questionário para o disparo da pesquisa,

-   -   **6.3.** E na consulta SQL, insira a consulta correspondente, adicionando o campo: **questionario\_id e o data\_envio,**

-   -   -   Quando o usuário informar o código do questionário no extrator, o sistema irá incluir o cliente automaticamente como **participantes do questionário**.
        -   Se o questionário estiver configurado para envio automático o sistema irá disparar o email e ou SMS automaticamente.

-   -   **6.4.** Preencha os demais campos necessários nesta página de configuração para o extrator. Para saber a configuração completa a ser feita nos indicadores, acesse: [Extrator-web.](https://wiki.simeon.com.br/extrator-web/)

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62a8f14eebd5c.png)

E-mail ao participante – pesquisa EPA.

**![](https://wiki.simeon.com.br/wp-content/uploads/2022/05/a38addc0469bb9b9bb45550042634c6d-247x300.jpg)**

**Artigos Relacionados:**

> **[Papéis e permissões – Questionários/Pesquisas](https://wiki.simeon.com.br/papeis-e-permissoes-questionarios/)**
> 
> **[Portal – Pesquisa NPS: Automatização na inclusão de clientes](https://wiki.simeon.com.br/portal-automatizar-a-inclusao-de-pacientes-para-pesquisa-nps/).**

#### **Aproveite essa melhoria!**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos a disposição!**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_62191d147280f.png)

---

Fonte: https://wiki.simeon.com.br/pesquisas-automatizacao-de-envio-de-e-mail-e-sms-nas-pesquisas/
