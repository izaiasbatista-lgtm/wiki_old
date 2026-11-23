---
title: "Cadastro de Pessoas – Reformulação das Funcionalidades para Fornecedores"
id: 17510
slug: "cadastro-de-pessoas-reformulacao-das-funcionalidades-para-fornecedores"
url: "https://wiki.simeon.com.br/cadastro-de-pessoas-reformulacao-das-funcionalidades-para-fornecedores/"
data: "2025-05-28T08:50:56"
modificado: "2025-08-12T10:02:08"
pasta: "1.2-PESSOAS"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
  - "1.2 -PESSOAS"
  - "Versão 192"
tags:
  - "copia controlada"
  - "copia impressa"
  - "Copias"
  - "tela principal"
---

# Cadastro de Pessoas – Reformulação das Funcionalidades para Fornecedores
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Nesse artigo, vamos falar sobre a reformulação da tela de Cadastro de Pessoas, com foco em melhorias nas funcionalidades voltadas ao gerenciamento de Fornecedores. As mudanças visam tornar os processos mais claros, ágeis e organizados, desde a parametrização inicial até o acompanhamento histórico das interações.**

#### **Aba Parametrizar Fornecedor**

**Vínculo com o Armário Virtual**

Agora é possível vincular um tipo de fornecedor a uma caixa do **Armário Virtual**. O endereço vinculado é exibido em uma nova coluna chamada **“Endereço”** na listagem de **Tipos de Fornecedor**. Abaixo, é exibida a informação sobre onde o fornecedor será avaliado.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6879c1a8ef617.png)

Na seção nomeada “Onde o Fornecedor será Avaliado”, é o campo destinado à visualização da UG parametrizada e à seleção dos avaliadores.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_6846ef655c7b8.png)

**Obrigatoriedade de vincular o Tipo de Fornecedor às Unidades Gerenciais**: agora, ao vincular um tipo de fornecedor, você deve obrigatoriamente indicar a quais unidades gerenciais ele será avaliado.

**Novas regras para inserção de avaliadores**:

-   Ao clicar em “Selecionar Avaliador” dentro da aba de uma UEN, o sistema só lista avaliadores associados àquele fornecedor, tipo de fornecedor e UEN.
    
-   Os avaliadores selecionados serão vinculados somente à unidade gerencial (UEN) correspondente à lista onde foram escolhidos.
    
-   Ao clicar em “Selecionar Unidades Gerenciais”, o sistema só mostra as unidades associadas à UEN do usuário que está fazendo a seleção.
    
-   **Importante**: Se houver avaliador configurado, na análise de conformidade de avaliações, o sistema irá considerar apenas as pesquisas respondidas por esse avaliador.
    

#### **Qualificação do Fornecedor**

Foi implementada uma nova regra no cálculo da conformidade das avaliações na aba **Qualificação do Fornecedor**. A partir de agora, as perguntas respondidas com **“N/A” (Não Avaliado)** serão desconsideradas no cálculo da porcentagem de conformidade, ou seja, não serão contabilizadas no total de questões avaliadas.

Com isso, a porcentagem de conformidade passa a ser calculada apenas com base nas perguntas efetivamente respondidas, tornando a avaliação mais justa e precisa, ao refletir apenas as respostas válidas. Além disso, a conformidade está agora segmentada por **UEN**, permitindo visualizar separadamente a conformidade de **documentos** e a conformidade das **avaliações**.

-   Se **não houver avaliador vinculado** a algum tipo de fornecedor, o sistema agora considera **todas as pesquisas associadas** a esse fornecedor para calcular a conformidade geral das avaliações.
-   As conformidades de documentos em uma UEN aparecem **somente se essa unidade estiver ativa** para aquele tipo de fornecedor na parametrização.
-   O sistema passou a permitir a **inserção de mais de um documento para o mesmo tipo de fornecedor e documento em unidades diferentes**.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_68472859926b3.png)

**Observação:** O documento, que antes era geral, agora será específico por unidade. O usuário poderá configurar quais unidades gestoras (UGs) terão acesso ao documento, acessando o Armário Virtual e marcando todas as UGs às quais o documento deverá pertencer.

-   O sistema foi ajustado para **funcionar mesmo se nenhum avaliador estiver vinculado** ao fornecedor.
-   Se pelo menos um avaliador estiver vinculado, o sistema continua funcionando normalmente, considerando o tipo de fornecedor, tipo de documento e unidade gerencial (UEN).

#### **Análise do Fornecedor**

Na aba **Análise do Fornecedor**, você poderá realizar uma análise detalhada a partir de três novos recursos:

-   **Unidade Gerencial**: é possível selecionar uma ou mais unidades gerenciais que devem ser consideradas na geração da análise. Esse campo permite filtrar os dados que serão processados pela inteligência artificial.
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_6841e3e1b28fa.png)

-   **Análise com IA**: ao gerar uma análise com base nos filtros escolhidos, o sistema exibirá automaticamente um texto com as considerações da IA. Esse campo é editável, então você poderá complementar ou ajustar as informações antes de enviar o feedback. Com o **“Histórico de IA abaixo”**.
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_6841e461ef78f.png)

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_6841e5a82404c.png)

Além disso, a aba conta com o botão **“Enviar E-mail”**, que permite encaminhar o feedback diretamente para os e-mails cadastrados nas configurações do fornecedor. Você poderá selecionar múltiplos e-mails de diferentes origens, como o e-mail cadastrado nas informações básicas, o e-mail vinculado à avaliação ou os e-mails configurados na seção “Parametrizar Envio de Email Fornecedor”.

-   **Anexos**: também é possível adicionar documentos ou evidências que serão enviados junto ao feedback. O limite total de anexos por envio é de **25 MB**.

#### **Histórico de Feedback** 

A nova aba **“Histórico de Feedbacks”** que tem como objetivo centralizar e facilitar o acompanhamento dos feedbacks enviados aos fornecedores. Nessa aba, o usuário poderá visualizar uma **tabela com os feedbacks registrados**, contendo as seguintes colunas: **Ações**, **Código**, **Data do Feedback**, **Unidade Gerencial** e **Tipo de Envio de Feedback.** 

A coluna **Ações** oferece a opção **“Editar”**, que direciona o usuário para uma tela com os detalhes completos do feedback selecionado.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_6841d76a75d1a.png)

Ao acessar a tela do feedback, o usuário terá à disposição três abas:

-   **Feedback**: exibe as informações principais e os anexos enviados.
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_6841d89d342ff.png)

-   **Ações**: permite cadastrar e gerenciar ações vinculadas ao feedback.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_6841d92c4e0fa.png)

-   **Acompanhamentos**: apresenta um histórico de interações, com possibilidade de incluir comentários e anexos.
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_6841d97c33c38.png)

#### **Histórico de Notificações**

Na aba **Histórico de Notificações**, você pode consultar todas as notificações que já foram enviadas aos fornecedores ou incluir uma nova notificação. A tela apresenta uma **tabela com os seguintes dados**: **Código,** **Data do Feedback e** **Unidade Gerencial.** 

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_6841ddf8a60ed.png)

Ao clicar em **“Editar”** em **Ações**, você será direcionado para a tela da notificação, que é composta por três abas **estrutura semelhante à utilizada na tela de Feedback**:

-   **Notificação**: exibe as informações principais da notificação e os anexos enviados.
    
-   **Ações**: permite incluir ações corretivas/preventivas vinculadas à notificação. Cada ação possui campos como **Código**, **O que?**, **Status**, **Responsável**, **Início Previsto** e **Fim Previsto**. A edição e exclusão dessas ações é controlada por perfil, apenas quem criou a ação ou o **Analista de Fornecedores** pode realizar alterações.
    
-   **Acompanhamentos**: exibe o histórico de acompanhamentos realizados, com opção de adicionar novos registros com **texto** e **anexos**. Assim como nas ações, a edição e exclusão dos acompanhamentos é restrita ao autor ou ao Analista de Fornecedores.
    

![](https://wiki.simeon.com.br/wp-content/uploads/2025/03/img_67c87b79c4bf5.png)

---

Fonte: https://wiki.simeon.com.br/cadastro-de-pessoas-reformulacao-das-funcionalidades-para-fornecedores/
