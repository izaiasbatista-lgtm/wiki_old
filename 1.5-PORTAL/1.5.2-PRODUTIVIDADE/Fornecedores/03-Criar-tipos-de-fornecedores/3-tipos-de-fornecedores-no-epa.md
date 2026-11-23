---
title: "3- Como cadastrar Tipos de Fornecedores no EPA"
id: 17937
slug: "3-tipos-de-fornecedores-no-epa"
url: "https://wiki.simeon.com.br/3-tipos-de-fornecedores-no-epa/"
data: "2025-07-16T10:54:19"
modificado: "2025-11-13T17:57:38"
pasta: "1.5-PORTAL/1.5.2-PRODUTIVIDADE/Fornecedores/03-Criar-tipos-de-fornecedores"
categorias:
  - "03- Criar tipos de fornecedores"
tags:
  - "Criar tipo de fornecedor"
  - "fornecedores"
---

# 3- Como cadastrar Tipos de Fornecedores no EPA
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Nesse artigo, vamos mostrar como liberar a permissão e configurar os Tipos de Fornecedores no EPA. Você aprenderá a cadastrar um tipo, definir critérios de conformidade, vincular documentos, pesquisas e responsáveis, além de associar fornecedores já existentes a esses tipos.**

### 

⇒ Permissão para cadastrar os Tipos de Fornecedores

Veja como utilizar esse novo módulo no EPA: O primeiro passo é liberar a permissão no seu usuário para acessar a configuração do ambiente Tipos de Fornecedores no EPA. Para isso, acesse o caminho: **Configuração → Usuários → Gerenciar Usuários.**

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_68770a1cefd90.png)

Dentro desse ambiente, vá até a aba **Permissões Gerais** e habilite as seguintes permissões:  
  
**Parametrização → Portal → Produtividade → Fornecedores → Tipos de Fornecedores.**

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_68770afc0cc2a.png)

### ⇒ Cadastro dos Tipos de Fornecedores

Após conceder a permissão, você terá acesso à página de configuração dos Tipos de Fornecedores. Para acessar esse ambiente, siga o caminho: **Parametrização → Política de Qualidade → Fornecedores → Tipos de Fornecedores.**

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_68770bf228a5c.png)

Clique no botão de **“+”** azul para incluir um novo Tipo de Fornecedor no sistema. Ao acessar o ambiente, preencha os campos obrigatórios conforme descrito a seguir:

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_68771eb695aaf.png)

-   **Título:** Informe o nome do tipo de fornecedor, como por exemplo: _Infraestruturas_, _Serviços Elétricos_, entre outros. Esse é um campo obrigatório.
-   **Ativo:** Selecione se o tipo de fornecedor estará ativo ou não no sistema. Esse é um campo obrigatório.
-   **Nota de Conformidade dos Documentos:** Defina a nota mínima de conformidade esperada nos documentos do Armário Virtual para os fornecedores vinculados a esse tipo. Esse é um campo obrigatório.
-   **Nota de Conformidade de Pesquisas:** Defina a nota mínima de conformidade esperada nas avaliações/pesquisas realizadas com os fornecedores vinculados a esse tipo. Esse é um campo obrigatório.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_68771ef105421.png)

Após a configuração inicial, selecione quais serão os documentos exigidos para analisar a conformidade dos fornecedores. Para isso, selecione os tipos de documentos que deverão ser apresentados por esse tipo de fornecedor. Em seguida, vincule cada documento e defina os pesos correspondentes conforme sua importância na análise.

Após o preenchimento, clique em **Adicionar** para registrar a configuração.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_68772000a185f.png)

Após salvar essa configuração, o EPA exibirá a lista com os **tipos de documentos que foram vinculados** a esse tipo de fornecedor, permitindo a visualização e edição sempre que necessário.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_68772071176d7.png)

Em seguida, selecione quais pesquisas já cadastradas no EPA serão utilizadas para avaliar esse tipo de fornecedor. Escolha a(s) pesquisa(s) que deseja vincular e defina a **periodicidade**, ou seja, o intervalo (em meses) entre as avaliações. Esse período determina com que frequência o avaliador responsável será notificado na tela principal do EPA.

Após configurar, clique em **Adicionar** para registrar as definições e  EPA irá exibir a lista das **pesquisas de avaliação que foram vinculadas** a esse tipo de fornecedor, permitindo a visualização e o gerenciamento das configurações aplicadas.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6877217e43577.png)

### ⇒ **Gestor do Tipo de Fornecedor**

Nesta versão, somente o **gestor do tipo de fornecedor** poderá realizar a parametrização de um fornecedor no formulário do cliente.

Acesse os tipos de fornecedores cadastrados no EPA e defina quem serão os **Analistas por tipo**.  
  
Assim, quando o gestor responsável acessar o formulário Pessoa do fornecedor, poderá visualizar e configurar as seguintes abas:

-   Parametrizar Fornecedor
-   Qualificação de Fornecedor
-   Bloqueio de Fornecedor

O analista, ao acessar o formulário Pessoa do fornecedor, verá apenas os tipos de fornecedor e demais informações dos tipos para os quais ele é gestor.

> **Importante:** Caso você tenha as permissões de **Super Usuário** ou **Analista de Fornecedores**, terá acesso a todas as opções (todos os tipos de fornecedores) nas abas de configuração do fornecedor no formulário cliente.

### 

⇒ **Cadastro do responsável pela avaliação do fornecedor.**

Quando uma pesquisa é disponibilizada, o gestor de fornecedores (avaliador ou usuário com permissão) receberá uma notificação em seu painel inicial para realizar a avaliação do fornecedor.

**Observação:** Não é necessário configurar nada dentro da avaliação. O avaliador já configurado poderá responder normalmente, e o sistema calculará automaticamente a nota final, comparando-a com o parâmetro de conformidade definido para o tipo de fornecedor.

Agora, é necessário vincular os fornecedores já cadastrados no EPA (pessoa física, jurídica ou funcionário) a um tipo de fornecedor previamente configurado no sistema.

Para isso, acesse o formulário de edição do fornecedor, vá até a aba **Parametrizar Fornecedor**, selecione o tipo desejado e clique em **Salvar**.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6877ae2534d70.png)

No formulário de edição de um fornecedor/cliente no EPA, acesse a aba **Parametrizar Fornecedor** e selecione o **tipo de fornecedor** ao qual este cliente será vinculado. Após a seleção, clique em **Salvar** para concluir o vínculo.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6877aebc9ac56.png)

Após seguir todos os passos deste artigo, o **tipo de fornecedor** com seus respectivos **fornecedores vinculados** estará totalmente configurado. A partir disso, você poderá organizar e criar novos tipos de fornecedores sempre que necessário, conforme as demandas do seu departamento ou empresa.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6877222fea0e0.png)

---

Fonte: https://wiki.simeon.com.br/3-tipos-de-fornecedores-no-epa/
