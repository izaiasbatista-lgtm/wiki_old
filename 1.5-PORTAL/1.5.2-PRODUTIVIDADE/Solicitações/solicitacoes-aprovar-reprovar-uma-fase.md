---
title: "Solicitações – Possibilidade de inserir vários aprovadores para direcionar o fluxo."
id: 9477
slug: "solicitacoes-aprovar-reprovar-uma-fase"
url: "https://wiki.simeon.com.br/solicitacoes-aprovar-reprovar-uma-fase/"
data: "2022-02-16T13:10:25"
modificado: "2022-03-02T11:34:32"
pasta: "1.5-PORTAL/1.5.2-PRODUTIVIDADE/Solicitações"
categorias:
  - "Solicitações"
tags:
  - "aprovadores"
  - "aprovadores solicitação"
  - "aprovar sol"
  - "aprovar solicitação"
  - "fase de aprovação"
  - "fases"
  - "Solicitações"
---

# Solicitações – Possibilidade de inserir vários aprovadores para direcionar o fluxo.
### **![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/img_60f9af23432dd-e1631299903164-213x300.png)**

**Nessa Versão, o módulo de Solicitações, conta com uma atualização, sobre a funcionalidade de APROVAÇÃO DE FASES dentro do processo de encaminhamento de solicitações.**

**Agora no módulo de Solicitações você pode definir vários Aprovadores, e direcionar o fluxo. Ao chegar em uma determinada fase, os aprovadores poderão aprovar ou reprovar, conforme a requisição solicitada para aprovação.**

## Configuração da Funcionalidade

**1 –** Para configuração desta funcionalidade, é preciso ir até a configuração das fases dos tipos de solicitações ou tipo de serviço:               

  _Acesse o caminho: Configuração> Portal> Solicitações> Tipo Solicitações._

**2 –** Selecione a aba de fases do tipo de fluxo que você deseja configurar: Fases do **Tipo de Solicitação** ou fases do **Tipo de Serviço.** Será necessário configurar algumas ações, no ambiente da fase escolhida para ser aprovada no processo:

-   Siga as instruções:

_**2.1**_ Você irá escolher qual será **a fase ou fases** que precisarão ser aprovadas no processo de encaminhamento da solicitação;

**2.2** Edite a fase desejada e marque o _fleg_ com a configuração: _Fase de Aprovação_;

**2.3** No campo: Ao reprovar, encaminhar para a fase, selecione uma ação para que o sistema faça quando acontecer uma fase não for aprovada;

**2.4** No campo: Quantidade Mínima de Aprovações: Insira a quantidade mínima de aprovações necessárias para que o sistema permita avançar com os encaminhamentos na solicitação;

**2.5** No campo: Aprovador, pesquise e selecione os aprovadores que serão notificados para aprovar a solicitação.

Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620d2da384b8a.png)

Configuração da fase de aprovação para o fluxo.

## Configuração: Ao reprovar, encaminhar para a fase

**3\.** Ainda na configuração de uma fase escolhida para funcionalidade de Aprovação da solicitação, o EPA disponibiliza 2 opções configuráveis para ser executada quando ocorrer a ação: Uma fase não for aprovada por um usuário no EPA.

-   -   A configuração ocorre na opção: Ao reprovar, encaminhar para a fase**.** Você deve escolher 1 das opções, para isso veja  a seguir o detalhamento do que cada uma das opções aplica no processo ao serem utilizadas.

**3.1** Nesta configuração quando selecionado a opção: _Fase do encaminhamento anterior_.

Caso aconteça a REPROVAÇÃO em uma fase da solicitação por um usuário, o sistema _irá encaminhar a solicitação para a fase e usuário anterior_ do encaminhamento registrado na solicitação. Assim o usuário que encaminhou a solicitação para a fase de aprovação poderá verificar o motivo da não aprovação e seguir com o processo.

Veja a configuração:  

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620e91de4786b.png)

Configuração da fase de aprovação para o fluxo.

**3.2** Quando selecionado como opção: _Uma das fases configuradas_ para esta solicitação, um campo adicional será apresentado para que _você também escolha para qual usuário_ o EPA deve encaminhar a solicitação.

Você poderá escolher 1 usuário para que o sistema encaminhe a solicitação, as opções são:

-   -   -   -   _Usuário do encaminhamento anterior realizado na solicitação;_
            -   _Usuários solicitante ou;_
            -   _Usuário responsável._

Assim, caso aconteça a REPROVAÇÃO na fase em uma solicitação, o sistema _irá encaminhar a solicitação para a fase e usuário configurado na fase do EPA, a_ssim o usuário selecionado nesta configuração receberá a solicitação e poderá verificar o motivo da não aprovação.

Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620e932ac2c1e.png)

Configuração da fase de aprovação para o fluxo.

## Formulário de Aprovação na Solicitação

**4\.** Após as configurações realizadas na respectiva fase de aprovação, quando sua solicitação for encaminhada para a fase de aprovação, os aprovadores configurados ao acessar a tela principal do EPA, encontrarão uma caixa BOX chamada: Solicitações para aprovar.

A partir deste acesso o aprovador, poderá ver as solicitações que estão aguardando a aprovação dele neste momento.

Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620e8eb1af0ad.png)

Box Solicitações para aprovar

**4.1** Para aprovar 1 (uma) solicitação, acesse a caixa box indicada e clique em Aprovar/Reprovar:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620e9756a6638.png)

Botão para acessar a tela de aprovação

⇓

O EPA apresentará para você o formulário de aprovação. No formulário há os botões de ação: _Aprovar e Reprovar_ e também um campo para inserir algum comentário a respeito da ação.

Veja este exemplo de formulário de aprovação na Solicitação a seguir:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620facdf34414.png)

Formulário para ação de Aprovação da Solicitação.

## Regras do Formulário de Aprovação

**5.** A seguir veja o que acontece quando se Aprova ou Reprova uma solicitação:

**5.1.** Quando a quantidade mínima de APROVAÇÃO da solicitação for atingida, pelos aprovadores configurados, o sistema irá seguir com fluxo de encaminhamento e encaminhar esta solicitação para a próxima fase automaticamente.

Obs.: Isto se, na configuração da próxima fase a ser encaminhada a solicitação houver um usuário executor _padrão_ configurado.

Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620e9e6d543dd.png)

Processo fase aprovada na solicitação.

## Observações:

-   Quando você _Aprovar_ uma  solicitação através do formulário, caso não seja possível seguir com o encaminhamento automático (por não ter![](https://wiki.simeon.com.br/wp-content/uploads/2021/09/img_613f69408257e.png) usuário padrão configurado na próxima fase do encaminhamento)**,** o sistema após a ação no formulário de aprovação, irá abrir para você o formulário padrão de acompanhamento/encaminhamento. Assim você poderá escolher a próxima fase e usuário a ser encaminhado a solicitação.

-   Caso o LIMITE MÍNIMO DE APROVAÇÕES ainda não tenha sido atingido no processo de aprovação de uma solicitação, o EPA apresentará uma mensagem informando que ainda não poderá ser encaminhada para a próxima fase.
-   Enquanto o limite mínimo de aprovações configurada não for comprido, o EPA não listará a próxima fase na solicitação para o encaminhamento.

Veja a mensagem apresentada no momento de encaminhar a solicitação:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620f9d65eb5a8.png)

Alerta ao usuário quando o limite de aprovação mínima ainda não estiver sido alcançado no momento.

**5.2** Quando algum dos aprovadores configurados na fase de aprovação, NÃO APROVAR a solicitação.

O EPA faz a verificação da configuração inserida (na fase): Ao reprovar encaminhar para a fase**,** conforme apresentado nos itens 3.1 e 3.2 deste artigo.

-   -   -   Se a configuração na fase “Ao reprovar, encaminhar para a fase**”** estiver selecionada: _Fase do encaminhamento anterior_****_,_**** o sistema irá encaminhar a solicitação para a fase anterior configurada no EPA, para o usuário que fez o encaminhamento para a fase de aprovação.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_6213c319634f7.png)

A imagem a seguir demonstra o que acontece no fluxo quando ocorre a reprovação de uma fase:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620ea776dd0c1.png)

Processo fase não aprovada na solicitação.

-   -   -   Se a configuração na fase “**Ao reprovar, encaminhar para a fase”** estiver selecionada: **Uma _Fase e Usuário para o Encaminhamento na solicitação__,_** o sistema irá realizar esse direcionamento no encaminhamento conforme o que foi configurado.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620eb485cdc64.png)

A imagem a seguir demonstra o que acontece no fluxo quando ocorre a reprovação de uma fase:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620eadca43451.png)

Processo fase não aprovada na solicitação.

## Acompanhamentos Registrados no formulário de Aprovação

**6\.** Quando você inserir um comentário no formulário de aprovação, ele será incluído como acompanhamento na solicitação.

Veja os acompanhamentos:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620eb7e376f71.png)

Acompanhamento registrado pelo aprovador na solicitação.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620eb87176818.png)

Acompanhamento registrado pelo aprovador na solicitação.

![](https://wiki.simeon.com.br/wp-content/uploads/2021/09/img_613f69451330c.png)

Os comentários para o formulário de aprovação **não são obrigatórios**, caso você não registre nenhum texto, o EPA irá gravar no acompanhamento a ação realizada em texto: **Aprovado** ou **Reprovado**.

## Histórico das aprovações na Solicitação

**7\.** O EPA registrará as ações realizadas durante os processos de aprovações na solicitação.

-   -   -   Na aba histórico, terá uma tabela com os registros de aprovações e reprovações ocorridas na solicitação.

Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620f9fa59778e.png)

Registro da fase aprovada!

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620f9f374cfbd.png)

Registro de uma fase não aprovada.

-   -   Na trilha de auditoria você também poderá ver o registro dessas ações.

Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620fa19cdc4f3.png)

Registro na trilha de auditoria.

## Formas de acesso para aprovar uma fase na solicitação

**8\.** Você terá o acesso para aprovação das fases de uma solicitação quando configurado nas seguintes formas:

**8.1** Para os aprovadores configurados, na tela principal do EPA, no Box de acesso: Solicitações para aprovar. Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620fa3ade2c60.png)

Caixa box Solicitações para aprovar em que o usuário é executor.

**8.2** Na tela principal do EPA no Box de acesso de suas solicitações em que você é o executor no momento, caso você também seja o aprovador nesta fase, no botão de ações haverá o acesso para direcionar para o formulário: para aprovar ou reprovar. Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620fa605a8bcb.png)

Caixa box Solicitações em que o usuário é executor.

**9\.** No processo de aprovações de uma fase em uma solicitação, alguns e-mails de notificações são enviados para os envolvidos neste processo.

**9.1** Quando a solicitação é encaminhada para a fase de aprovação, os aprovadores configurados para este processo recebem um e-mail avisando sobre esta ação. Veja um exemplo como seria este e-mail.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620fa74e4c854.png)

E-mail informativo para os Aprovadores.

**9.2** Quando a solicitação estiver em uma fase de aprovação, o usuário executor do presente encaminhamento receberá o e-mails de notificação informando sobre as aprovações e não aprovações já realizadas pelos usuários aprovadores. Veja o e-mail que é recebido pelos usuário executor na fase de aprovação:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620faa3e859ce.png)

E-mail da solicitação Fase Aprovada.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_620fab432cee8.png)

E-mail da solicitação Fase Reprovada.

**![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/istockphoto-921459570-612x612-1-e1626985188707-167x300.jpg)**

> **Artigos Relacionados:**

> [Papéis e permissões – Solicitações](https://wiki.simeon.com.br/7328-2/)
> 
> [Formulários módulo de solicitações](https://wiki.simeon.com.br/formularios-no-modulo-de-solicitacoes/)
> 
> [Solicitações – Base de conhecimento](https://wiki.simeon.com.br/solicitacoes-novo-formulario-base-de-conhecimento/)
> 
> [Solicitação: Assinatura digital nos documentos em anexo](https://wiki.simeon.com.br/portal-assinatura-digital-nos-documentos-em-anexo-de-uma-solicitacao/)

#### **Aproveite essa melhoria!**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos a disposição!**

#### ![](https://wiki.simeon.com.br/wp-content/uploads/2020/08/logo-epa.png)

---

Fonte: https://wiki.simeon.com.br/solicitacoes-aprovar-reprovar-uma-fase/
