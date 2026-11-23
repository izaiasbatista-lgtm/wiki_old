---
title: "Solicitações – Aprovar/Reprovar uma fase"
id: 6364
slug: "solicitacoes-2"
url: "https://wiki.simeon.com.br/solicitacoes-2/"
data: "2021-04-14T10:15:53"
modificado: "2022-08-01T11:41:40"
pasta: "1.5-PORTAL/1.5.2-PRODUTIVIDADE/Solicitações"
categorias:
  - "Solicitações"
tags:
---

# Solicitações – Aprovar/Reprovar uma fase
---

> ### **Nessa Versão o módulo de solicitações, agora conta com uma nova funcionalidade para o processo de encaminhamentos de suas solicitações.**
> 
> -   ### **Agora pode configurar a fase de uma solicitação para ser aprovada ou não por um usuário do EPA.**
>     
> -   ### **Ao chegar em uma determinada fase, você poderá aprova-la ou reprova-la, conforme a requisição solicitada para aprovação.**
>     
> 
> ### **Com esse processo você poderá aprovar demandas e outros cenários através dessa funcionalidade no módulo de solicitações!**
> 
> ### **Veja como configurar essa funcionalidade no EPA!**

## Configuração da Funcionalidade

     **1 –** Para configuração desta funcionalidade, é preciso ir até a configuração das fases dos tipos de solicitação ou tipo de serviço:               

  _Acesse o caminho: Configuração> Portal> Solicitações> Tipo Solicitações._

     **2 –** Selecione a aba de fases do tipo de fluxo que você deseja configurar:

-   Fases do **Tipo de Solicitação** ou fases do **Tipo de Serviço.**

Você irá escolher qual será **a fase ou fases** que precisarão ser aprovadas no processo de encaminhamentos da solicitação.

-    Edite a fase desejada e marque o fleg com a configuração: _**Fase de aprovação**_ e **Salve**.

![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/conf.-aprovacao-1024x452.png)

## Formulário de aprovação na solicitação

     **3 –** Após a configuração acima, **quando sua solicitação for encaminhada para uma fase de aprovação**, **_o usuário executor_** desta fase ao editar a solicitação verá um formulário na tela do EPA, para ele poder aprovar ou não a atividade descrita nessa solicitação.

No formulário há os botões de ação: **Aprovar e Reprovar** e também um campo para inserir algum comentário a respeito da ação.

Veja este exemplo de formulário de aprovação na Solicitação a seguir:

![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/aprovacao-tela-4-1024x439.png)

## Regras do Formulário de Aprovação

#### (O que acontece quando se aprova ou reprova uma fase da solicitação?)

-   Quando o usuário executor da fase de aprovação receber a SOL e aprovar:

![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_1-1-1024x434.png)

Quando você **Aprovar** a fase de uma solicitação através do formulário, o sistema irá seguir com fluxo de encaminhamento e encaminhar esta solicitação para a **próxima fase automaticamente**. Isto se, na configuração da próxima fase a ser encaminhada a solicitação houver um usuário executor _padrão_ configurado.

-   Quando o usuário executor da fase de aprovação receber a SOL e reprovar:

![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_3-1-1024x437.png)

Caso você **Reprove** uma solicitação em uma fase, o sistema **irá encaminhar a solicitação para a fase anterior configurada no EPA**, para o usuário que fez o encaminhamento para a fase de aprovação. Assim ele poderá verificar o motivo da não aprovação.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbdba05736.png)

Quando você **Aprovar** uma  solicitação através do formulário, **caso não seja possível seguir com o encaminhamento automático (por não ter usuário padrão configurado na próxima fase),** o sistema após a ação no formulário de aprovação, irá abrir para você o formulário padrão de acompanhamento/encaminhamento. _**Assim você poderá escolher a próxima fase e usuário a ser encaminhado a solicitação.**_

## Acompanhamentos Registrados no formulário de Aprovação

     **4 –** Quando você inserir um comentário no formulário de aprovação, ele será incluído como acompanhamento na solicitação.

Veja o os acompanhamentos:

-   ![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_4-1.png)
    
-   ![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_5-1.png)
    

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbdba05736.png)

#### Os comentários para o formulário de aprovação não são obrigatórios, caso você não registre nenhum texto, o EPA irá gravar no acompanhamento a ação realizada em texto: Aprovado ou Reprovado.

# Histórico das aprovações na Solicitação

     **5 –** O Epa registrará as ações realizadas durante os processos de aprovações na solicitação.

-   Na aba histórico, terá uma tabela com os registros de aprovações e reprovações ocorridas na solicitação.

Veja:

-   ![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_6-1-1024x215.png)
    
    Registro da fase aprovada!
    
-   ![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_8-1024x213.png)
    
    Registro de uma fase não aprovada!
    

-   Na trilha de auditoria você também poderá ver o registro dessas ações.

Veja:

-   ![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_9-1024x185.png)
    

Registro na trilha de auditoria.

# **Formas de acesso para aprovar uma fase na solicitação**

     **6 –** Você terá o acesso para aprovação das fases de uma solicitação quando configurado nas seguintes formas:

-   #### _Na tela principal do EPA, no Box de acesso de suas solicitações:_
    

Há o botão de acesso ao usuário executor: **para aprovar ou reprovar**

![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_10-1024x432.png)

Box de acesso as solicitações

-   #### _A partir do Email de encaminhamento:_
    

-   -   O **usuário executor/aprovador da fase**, ao receber o email de encaminhamento a respeito da solicitação, poderá aprovar a fase através dos ícones disponíveis para essa ação.

-   -   Ao clicar nos botões, uma nova janela se abrirá no navegador com o mesmo formulário de aprovação do EPA! E você poderá aprovar ou não aprovar e inserir seu comentário.

Veja:

-   ![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_11-1024x478.png)
    
    Botões de acesso ao formulário de aprovação a partir do email.
    
-   ![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_12-1024x397.png)
    
    Janela com formulário de aprovação no navegador – a partir do acesso do Email
    

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbdba05736.png)

Quando você **Aprovar** uma  solicitação através do **E-MAIL**, **caso não seja possível seguir com o encaminhamento automático (por não ter usuário padrão configurado na próxima fase),** o sistema após a ação no formulário de aprovação, irá apresentar a seguinte mensagem:

![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/Screenshot_14-1024x438.png)

Quando a aprovação da fase da solicitação acontecer através do **email** e o EPA identificar que a **próxima fase a ser encaminhada não possui um usuário executor padrão configurado** para o direcionamento do fluxo, **a fase será aprovada**, mas o usuário executor precisará logar no sistema e fazer o encaminhamento de forma manual.

> #### Aproveite essa nova funcionalidade para melhoria de seus processos em seu departamento!

> #### Qualquer dúvida ou sugestão de melhoria estamos a disposição!

![](https://wiki.simeon.com.br/wp-content/uploads/2020/08/logo-epa.png)

---

Fonte: https://wiki.simeon.com.br/solicitacoes-2/
