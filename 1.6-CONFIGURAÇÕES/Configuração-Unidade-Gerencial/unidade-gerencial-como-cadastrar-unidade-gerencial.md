---
title: "Unidade Gerencial – Como cadastrar Unidade Gerencial"
id: 18935
slug: "unidade-gerencial-como-cadastrar-unidade-gerencial"
url: "https://wiki.simeon.com.br/unidade-gerencial-como-cadastrar-unidade-gerencial/"
data: "2026-01-08T18:52:57"
modificado: "2026-01-12T17:59:00"
pasta: "1.6-CONFIGURAÇÕES/Configuração-Unidade-Gerencial"
categorias:
  - "Configuração Unidade Gerencial"
tags:
  - "cadastrar unidade"
  - "componente de desempenho"
  - "incluir unidade"
---

# Unidade Gerencial – Como cadastrar Unidade Gerencial
Este artigo tem como objetivo orientar os usuários sobre **como realizar o cadastro de unidades no EPA**. Aqui serão apresentadas as informações necessárias, as permissões exigidas, garantindo uma configuração correta da estrutura gerencial no sistema.  
Caso tenha interesse em conhecer o **conceito de Unidade Gerencial**, acesse **[Conceito Unidade Gerencial.](https://wiki.simeon.com.br/conceito-unidade-gerencial/)**

-   **Quem pode executar essa funcionalidade**
    

A funcionalidade pode ser executada por **colaboradores das equipes de TI, Qualidade ou Planejamento**, desde que estejam designados para realizar a **parametrização de acesso ao sistema**.  
Para realizar o cadastro de unidades e liberação de acesso das unidades, o usuário deve possuir as seguintes permissões:

-   **Unidade Gerencial**
    
-   **Componente de Desempenho**
    
-   **Super Usuário**
    
-   **Gerenciar Usuário**
    
-   **Cadastrar Usuário**
    
-   **Perfil de Usuário**
    

-   **1- Como cadastrar a unidade**
    

Para cadastrar uma unidade, no menu do **EPA**, acesse **Engrenagem > Unidade Gerencial**.

![](https://wiki.simeon.com.br/wp-content/uploads/2026/01/img_695ff53b4d67d.png)

Na sessão **Cadastro de unidade gerencial**

![](https://wiki.simeon.com.br/wp-content/uploads/2026/01/img_695ffa80a8289.png)

Preencha os campos conforme descrito abaixo.

1.  **Nome da Unidade**  
    Informe o nome da área ou departamento da organização.
    
2.  **Abreviação** (opcional)  
    Informe a abreviação ou sigla utilizada para identificar a área ou departamento na organização.
    
3.  **Código Externo** (opcional)  
    Informe o código externo de identificação da Unidade Gerencial.
    
4.  **Perfil Padrão para Importação** (opcional)  
    Utilizado quando existe integração de usuários com outro sistema ou com o Active Directory (AD). Nesse caso, durante a importação, o sistema aplicará automaticamente o perfil padrão configurado para essa unidade gerencial.
    
5.  **Unidade Gerencial Pai**  
    Selecione a área ou departamento hierarquicamente superior à unidade que está sendo cadastrada.  
    Caso esta seja a primeira unidade da hierarquia, o campo pode ser deixado em branco.
    
6.  **Qual UEN pertence? (Filial)**  
    Selecione a UEN à qual a unidade gerencial pertence.
    
7.  **Ativo**  
    Marque esta opção para que a unidade fique ativa no sistema.
    
8.  **Unidade Estratégica de Negócio (Filial)** (opcional)  
    Marque esta opção caso a unidade que está sendo cadastrada seja uma filial. Essa configuração é utilizada principalmente em cenários com múltiplas empresas. Exemplo, Hospital X e Hospital Y, dessa forma cada um deles é sinalizado como unidade estratégica de negócio e a sua hierarquia pode ser separada. Facilitando no campo de buscas do sistema.
    
9.  **Moderadora Ouvidoria** (opcional)  
    Marque esta opção se a unidade for uma unidade moderadora do módulo de Ouvidoria.  
    Essa configuração é utilizada quando diferentes áreas da empresa utilizam o EPA Ouvidoria para registrar, gerenciar e acompanhar interações com seus públicos. Nesse cenário, é necessário parametrizar quais usuários poderão incluir e visualizar registros em cada unidade gerencial.  
    Para mais informações, consulte o artigo **[Configurar Unidade Moderadora – Ouvidoria](https://wiki.simeon.com.br/configurar-unidade-moderadora-ouvidoria/)**.
    
10.  **Moderadora Ocorrência** (opcional)  
     Marque esta opção se a unidade for uma unidade moderadora do módulo de Ocorrências.  
     A Unidade Moderadora é utilizada para organizar e restringir o acesso às ocorrências, especialmente em ambientes com múltiplos departamentos da Qualidade ou setores responsáveis por Não Conformidades.  
     Para mais detalhes, consulte o artigo **[Ocorrências – Utilizar Unidade Moderadora](https://wiki.simeon.com.br/utilizar-unidade-moderadora/)**.

Ao finalizar, clique em salvar.

-   **2- Vinculação ao Componente de Desempenho**
    
    Após cadastrar a unidade, caso exista **mais de um componente de desempenho** no ambiente, será necessário **vincular a nova unidade ao componente de desempenho correspondente**.  
      
    Se houver **apenas um componente de desempenho**, a unidade será vinculada automaticamente pelo sistema.  
    Para saber como realizar esse vínculo, consulte o artigo:  **[Planejamento – Componente de desempenho – Incluir/excluir e vincular unidade gerencial](https://wiki.simeon.com.br/componente-de-desempenho-incluir-excluir-e-vincular-unidade-gerencial/).** 
    

-   **3- Liberação de acesso aos usuários**
    
    Após criar a unidade e vinculá-la ao componente de desempenho, é necessário acessar o **cadastro dos usuários** ou o cadastro de **perfil de usuário**, entrar na aba **Unidades Gerenciais** e liberar as **permissões necessárias**, para que os usuários possam **visualizar e utilizar a nova unidade** no sistema.
    

![](https://wiki.simeon.com.br/wp-content/uploads/2026/01/img_6960f6996f9b7.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2026/01/img_6960f724ba7ca.png)

Na aba **Unidades Gerenciais**, cada coluna possui uma funcionalidade específica. Entenda abaixo o papel de cada uma delas:  

-   **Coluna E – Unidades Estratégicas:** Define as unidades às quais o usuário terá acesso para o **acompanhamento da execução da estratégia**.  
    Essa configuração é utilizada no módulo de Planejamento, incluindo: Painel de Indicadores, Plano de Ação, Reuniões.
    
-   **Coluna D – Unidade Estratégica Padrão****:**  Define qual será a **unidade padrão** do usuário nos filtros de Unidade Gerencial do EPA.
-   **Coluna P – Unidades que o Usuário Pertence:** Indica a **unidade de trabalho** do usuário.   
    Essa configuração é utilizada nos seguintes módulos: Solicitações, Riscos.
    
-   **Coluna C – Unidades com quem o Usuário se Comunica:** Define as unidades com as quais o usuário pode **se comunicar e atribuir responsabilidades**.  
    Permite encaminhar e receber atividades entre unidades.   
    Utilizada no Módulo Portal.
    
-   **Coluna G – Unidades que um Gestor Gerencia:** Define as unidades das quais o usuário **é gestor**, permitindo o acompanhamento das atividades dessas unidades.  
    Essa coluna é exibida apenas quando o usuário possui a permissão **Gestor de Unidades Gerenciais**.  
    Utilizada nos módulos: Ocorrências, Solicitações, Ouvidoria, Indicadores, Riscos…

#### **![](https://wiki.simeon.com.br/wp-content/uploads/2025/09/img_68da8df21910a.png)**

---

Fonte: https://wiki.simeon.com.br/unidade-gerencial-como-cadastrar-unidade-gerencial/
