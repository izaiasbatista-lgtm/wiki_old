---
title: "Configurar pesquisa externa para cliente"
id: 5207
slug: "configurar-pesquisa-externa-para-cliente"
url: "https://wiki.simeon.com.br/configurar-pesquisa-externa-para-cliente/"
data: "2020-11-05T19:16:08"
modificado: "2025-04-30T11:19:07"
pasta: "1.5-PORTAL/1.5.1-COMUNICAÇÃO/Pesquisa-Questionários"
categorias:
  - "Pesquisa/Questionários"
tags:
  - "cliente"
  - "externa"
  - "pesquisa"
---

# Configurar pesquisa externa para cliente
Para configurar a pesquisa acesse em Portal > Pesquisas e clique no botão ![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5aea24cf2a133.png) na próxima tela informe o **Titulo(1)** da pesquisa, **Ativo(2)** Sim, **Descrição(3)**, **Categoria(4)**, **Data início e Data Fim(5)**  e marque as opções**(6)**:

-   **Responder com único usuário _(usuário geral para evitar identificação)_****:** essa opção de usar um único usuário serve para o sistema identificar que, a cada novo acesso com o mesmo usuário, link ou QR code, será gerado um novo formulário de resposta. As respostas são gravadas normalmente, mesmo que diferentes colaboradores utilizem o mesmo acesso.

-   **Ao clicar na opção de resposta passar para próxima pergunta automaticamente**: Quando respondo uma pergunta o EPA pula para a próxima pergunta automático

**Obs:** Para saber mais informações sobre as funcionalidades das opções, e o que elas influenciam no calculo ou na configuração do questionário acesse o artigo [Criar questionário.](https://wiki.simeon.com.br/criar-questionario/)

Selecione no campo **Etapa(7)** para fixar o mês que a data das respostas devem ser lançadas.   
Essa funcionalidade esta disponível apenas para as pesquisas que as respostas forem lançadas no EPA, por exemplo uma pesquisa que tem formulários físicos e depois a equipe interna lança essas respostas no EPA. Mais adiante explicaremos detalhadamente como funciona esse processo.  
**Obs.:** A regra desse campo Etapa se aplica apenas quando o questionário é respondido por meio do botão “Responder” na listagem das pesquisas.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/11/img_5fa5a372a35aa.png)

Crie as classificações das perguntas, caso queria dividir as perguntas por classificação. Informe a **ordem** **(8)**, o nome da **classificação** **(9)** e clique em salvar.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/11/img_5fa5a3ec1ec49.png)

Caso deseje criar uma subclassificação para a classificação clique em ![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5b03269006ed1.png), informe o titulo da **SubClassificação (10)** e a **Descrição/Orientação da Subcompetência (11)** e clique em salvar.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/11/img_5fa5a4084b60b.png)

Caso as perguntas tenham categoria, crie e Categoria das perguntas informando o **nome da categoria** **(12)** e clique em salvar.

> **Observação:** A categoria é usada para estabelecer uma ordem de perguntas diferente da estrutura de classificação/subclassificação que o usuário visualiza. Serve para estruturar uma pesquisa em que o respondente não seja guiado ou consiga verificar a relação entre as perguntas.  
> Utiliza-se para estruturar uma pesquisa de clima de um cliente por exemplo, as perguntas que o usuário veria estavam em uma ordem diferente em que a gestora do RH(psicóloga) avaliaria as respostas dadas.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/11/img_5fa5a42a62553.png)

Para criar as perguntas acesse a aba Perguntas e clique no botão ![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5b032abb5b206.png),  informe a descrição da **pergunta (13)**, selecione a **classificação(14)** da pergunta, a **ordem(15),** o **peso(16).**Selecione se:  
**Mostrar opção de resposta na horizontal(17)** essa opção selecionada mostra as opções de resposta na horizontal;  
**Permitir mais de uma** **resposta(18)** essa opção permite que o usuário marque mais de uma opção de resposta;  
**Ocultar o campo de Comentário (Essa opção inabilita requerer comentário nas opções de resposta)(19);**  
**Responder pergunta obrigatoriamente(20)** essa opção torna a pergunta obrigatória, ou seja enquanto o usuário não responder ele não pode responder as outras perguntas.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/11/img_5fa5a48fb6521.png)

> **Atenção:** Se a pergunta estiver marcada que é obrigatória, ao responder a pesquisa o EPA permite que o respondente passe para a próxima pergunta para responder. Porem ao clicar para finalizar o a pesquisa, ele irá solicitar ao respondente que responda as perguntas que estão sem respostas. Caso o respondente feche a aba do navegador sem responder as perguntas que estão sem resposta, o EPA vai gravar apenas o que foi respondido.

Ao clicar em  salvar será habilitado o botão  para incluir as opções de resposta, clique no botão ![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5b032aff438e3.png).  
Informe a **opção de resposta(21)**, o **peso(22)** , a **ordem(23)**, selecione se a pergunta **Exigir Comentário/Justificativa** **(24).** Na opção  **Levar para Pergunta(25)** selecione a pergunta que o participante deve direcionado caso ele marque essa resposta, caso não queira deixe selecionado a opção **Segue Ordem Natural.**

![](https://wiki.simeon.com.br/wp-content/uploads/2020/11/img_5fa5a4e668778.png)

Existem algumas formas diferentes de disponibilizar a pesquisa para que o cliente externo responda:

**1 –**  Algumas empresas que ainda utilizam formulários físicos para pesquisa externa, e depois a equipe interna lança as respostas desses formulários no EPA.  
Para usuário consiga lançar as respostas do formulário na pesquisa do EPA, ele precisa ter a permissão “_Responder Pesquisa Como Outro Usuário_“. Para que o EPA permita que ele informe o nome do cliente no momento em que for incluir  a resposta.

Ao acessar a listagem das pesquisas será habilitado o botão ![](https://wiki.simeon.com.br/wp-content/uploads/2020/11/img_5fa5ab22ea785.png).

![](https://wiki.simeon.com.br/wp-content/uploads/2020/11/img_5fa5ab12db75b.png)

Ao clicar no botão o EPA vai carregar a tela para preencher os dados para lançar a resposta da pesquisa, antes de responder e necessário preencher algumas informações. Informe a **Data da avaliação(26)**, nome do **Cliente(27)** que vai ser lançada a resposta, **Unidade gerencial(28)**, caso o cliente não esteja cadastrado no EPA clique no botão **Novo cliente(29),** após selecionar as opções clique em **Responder(30)**.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/11/img_5faad851c848c.png)

Se na configuração da pesquisa o campo **Etapa** tiver uma etapa informada, e o campo **Validar N° Atendimento** estiver marcado. Quando clicar para responder no filtro de **Data Avaliação(31)** vai ficar bloqueado, trazendo fixo o ultimo dia do mês selecionado no campo etapa. E o campo **N° Atendimento(32)**  vai estar habilitado,  para conseguir responder a pesquisa e preciso informar o número do atendimento.

> Lembrando essa configuração da data fixa da Data da Avaliação funciona apenas para as respostas lançadas no EPA pela opção Responder, se caso a pesquisa interna ou externa for respondida de outra forma a Data da Avaliação será a data que o usuário ou o cliente externo respondeu a pesquisa.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/11/img_5faadbf9dfd51.png)

**2**– Pode ser enviado o questionário para o cliente atraves do email marketing,  é possível configurar nesse email um texto ou uma imagem para trazer no seu email e o link da pesquisa que foi selecionada.  
Para saber mais informações de como configurar um email marketing e vincular o questionário para enviar para os clientes externos, acesse o artigo **[Cadastro campanha E-mail Marketing](https://wiki.simeon.com.br/cadastro-campanha-e-mail-marketing/)** .

**3 –** Pode ser disponibilizado um **QR Code geral** para **cliente externo** responder a pesquisa, esse QR Code pode ser disponibilizado para os clientes em um cartaz, folders ou ate ser enviado por email.  
Mas para utilizar esta funcionalidade você deverá ter um usuário com a permissão **_“Usuário específico para responder pesquisas (checklist, NPS, tablet)”_** , caso tenha duvidas de como realizar a configuração acesse o artigo [QRCode para os questionários no EPA](https://wiki.simeon.com.br/pesquisas-qrcode-para-os-questionarios-no-epa/).

Depois acesse a tela de edição da pesquisa, e acesse a nova Aba: **QRcode para link público(32),** para ter acesso aos QRcodes disponíveis. Nesta Aba, selecione a opção: **Utilização Externa: Solicitar Identificação da Pessoa no final do Questionário(33)**, o respondente ao ler o QRcode a partir do seu aparelho, será direcionado para um link em seu navegador que iniciará o questionário com suas perguntas disponíveis.

Quando ele terminar de responder todas as perguntas, uma janela irá aparecer com algumas informações para que o usuário informe sua identificação se quiser. Caso não queira se identificar é só clicar em finalizar.

![](https://wiki.simeon.com.br/wp-content/uploads/2021/03/img_60587337173a7.png)

Veja como é o direcionamento após a leitura do QRCode do dispositivo:

 ![](https://wiki.simeon.com.br/wp-content/uploads/2020/10/simeon.sysepa.com_.br_epavalidacao_responder.php_actionquestionarioid82uuid0e843be7-0d55-11eb-901b-0242ac120013identificatetruelogouttrueMoto-G4-1-194x300.png)![](https://wiki.simeon.com.br/wp-content/uploads/2020/10/simeon.sysepa.com_.br_epavalidacao_responder.php_actionquestionarioid82uuid0e843be7-0d55-11eb-901b-0242ac120013identificatetruelogouttrueMoto-G4-2-194x300.png)

Terminando de responder o questionário o sistema perguntará se o respondente deseja se identificar.  Veja :

![](https://wiki.simeon.com.br/wp-content/uploads/2020/10/simeon.sysepa.com_.br_epavalidacao_responder.php_actionquestionarioid82uuid0e843be7-0d55-11eb-901b-0242ac120013identificatetruelogouttrueMoto-G4-3-194x300.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbdba05736.png)

\*Se o respondente se identificar as respostas ficam gravadas com o nome informado por ele no fim do questionário.

\*ou se o respondente não se identificar, as respostas serão  gravadas no usuário específico cadastrado na pesquisa para direcionamento no QrCode.

---

Fonte: https://wiki.simeon.com.br/configurar-pesquisa-externa-para-cliente/
