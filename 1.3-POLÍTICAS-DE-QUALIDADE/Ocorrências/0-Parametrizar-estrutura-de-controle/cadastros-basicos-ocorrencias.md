---
title: "Ocorrências – Cadastros Básicos"
id: 229
slug: "cadastros-basicos-ocorrencias"
url: "https://wiki.simeon.com.br/cadastros-basicos-ocorrencias/"
data: "2018-05-14T10:13:19"
modificado: "2025-05-25T18:28:45"
pasta: "1.3-POLÍTICAS-DE-QUALIDADE/Ocorrências/0-Parametrizar-estrutura-de-controle"
categorias:
  - "0- Parametrizar estrutura de controle"
tags:
  - "cadastros"
  - "configuração"
  - "ocorrência"
  - "severidade"
---

# Ocorrências – Cadastros Básicos
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Nesse artigo, vamos falar sobre os cadastros básicos utilizados no módulo de Ocorrências, que garantem a organização e o controle definidos na Política da Qualidade da empresa. Esses cadastros seguem um padrão simples para inclusão, edição e exclusão de registros, facilitando a gestão das ocorrências no sistema.**

### **Cadastros Básicos no Módulo de Ocorrência**

Existem diversos cadastros básicos utilizados no módulo de Ocorrência que garantem o controle e a organização conforme a Política da Qualidade da empresa. São eles:

-   **Categoria de Ocorrências**
    
-   **Classificação/Origem**
    
-   **Grupo de Risco**
    
-   **Mensagem e-mail encerramento ação**
    
-   **Número limite de ocorrência**
    
-   **Tipo acompanhamento**
    
-   **Tipo causa**
    
-   **Tipo incidente**
    
-   **Tipo ocorrência**
    
-   **Tipo severidade/gravidade**
    
-   **Título ocorrência**
    
-   **Título ações**
    

Todos os cadastros seguem o mesmo padrão:

-   Informe o título.
    
-   Para alterar/editar um registro na listagem, clique no ícone de edição . As informações cadastradas ficarão disponíveis para edição na parte superior da tela; faça as modificações e clique em **Salvar**.
    
-   Para excluir um registro, clique no ícone de exclusão do registro desejado.
    

### **Cadastro do Tipo de Ocorrência**

1.  Acesse: **Políticas da Qualidade → Ocorrências → Tipo de Ocorrência**.
    
2.  Para incluir um novo registro, escreva o título (1) e informe:
    
    -   Dias para finalizar a ocorrência (2)
        
    -   Dias para realizar análise de causa (3)
        
3.  Marque os tipos de ações que podem ser geradas (4).
    
4.  Marque a opção **Ativo** (5) para que o título esteja disponível para escolha.
    
5.  Caso seja obrigatório incluir uma ação corretiva no plano de ação, marque a opção **Não permitir encaminhar ocorrência para análise sem ação corretiva** (6).
    
6.  Se for necessário que a área notificada registre a ação imediata realizada, marque a opção **Permitir Ação Imediata da Unidade Notificada** (7). Tanto o responsável pela ocorrência quanto o gestor da área notificada poderão registrar essa ação.
    
7.  Clique no botão **Salvar**.
    

Para alterar ou editar um registro na listagem, clique no ícone de edição. As informações cadastradas ficarão disponíveis para edição na parte superior da tela; faça as modificações e clique em **Salvar**. Para excluir um registro, clique no ícone de exclusão correspondente ao registro desejado.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5afc435b777ed.png)

### **Cadastro do Título de Ocorrências**

-   Acesse: **Parametrização → Políticas da Qualidade → Ocorrências → Título da Ocorrência**.
    
-   Informe o título da ocorrência (1), marque a opção **Ativo** (2) e clique em **Salvar**.
    
-   Os demais campos são opcionais:
    
    -   Unidade Notificada (3)
        
    -   Grupo de Risco (4)
        
    -   Severidade (Grau do dano) (5)
        
    -   Risco relacionado (6)
        

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5afc477414428.png)

Para preencher os campos **Grupo de Risco, Severidade (Grau do dano) e Risco relacionado**, é necessário cadastrá-los previamente. O campo **Unidade Notificada** apresenta as unidades com as quais o usuário se comunica, e o campo **Risco relacionado** corresponde aos riscos cadastrados no módulo de **Gestão de Riscos.**

**Grupo de Risco**

-   Acesse: **Parametização → Políticas da Qualidade → Ocorrências → Grupo de Risco**.
    
-   Informe o título do grupo de risco (1) e marque a opção **Ativo** (2).
    
-   Clique em **Salvar**.
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5afc6fa12e3e1.png)

### **Severidade (Grau do dano)**

-   Acesse: **Parametrização → Políticas da Qualidade → Ocorrências → Severidade (Grau do Dano)**.
    
-   Informe o título (1), o peso que esse grau terá (2) e marque a opção **Ativo** (3).
    
-   Clique em **Salvar**.
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5afc6ffb9c6ef.png) 

### **Categoria de Ocorrências  
**

Clique em **Parametrização →  Políticas da Qualidade → Ocorrências → Categoria de Ocorrências**, informe o título da categoria (1), marque a opção **Ativo** (2) e clique em **Salvar**.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5afc7084f1fc9.png)

### **Número limite ocorrência**

Clique em **Parametrização → Políticas da Qualidade → Ocorrências → Número limite ocorrência** para configurar a quantidade máxima de ocorrências que podem ser abertas por tipo de ocorrência, título da ocorrência e por unidade gerencial.

Quando esse limite for ultrapassado, será gerada uma nova ocorrência que agrupa todas as ocorrências já abertas com esse título e tipo (Reincidente).

Para incluir um novo limite:

1.  Selecione o título da ocorrência (1);
    
2.  Selecione o tipo da ocorrência (2);
    
3.  Informe o número máximo de ocorrências para cada unidade gerencial (3).
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5afc2eb98bb47.png)

### **Tipo de acompanhamento**  

Clique em **Parametrização → Políticas da Qualidade → Ocorrências → Tipo de acompanhamento**, informe o título do acompanhamento (1) e clique em Salvar.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5afc75a08ea0d.png)

### **Tipo de causa**

Clique em **Paramtrização → Políticas da Qualidade → Ocorrências → Tipo da causa**, informe o título da causa (1), a descrição (2) e marque a opção Ativo (3). Se desejar, marque também a opção **Adicionar a causa como padrão na listagem (Causa(s) Efeito(s))**.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5afc76c8c44ff.png)

### **Tipo incidente  
**

Clique em **Parametrização →Políticas da Qualidade → Ocorrências → Tipo incidente**, informe o título do incidente (1), marque a opção Ativo (2) e clique em Salvar.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5afc792dcb2a0.png)

## **Tipo ações**

Clique em **Políticas da Qualidade → Ocorrências → Tipo ações**, informe o título da ação e clique em Salvar.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2018/05/img_5afc7a8817996.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_683385fdabca5.png)

---

Fonte: https://wiki.simeon.com.br/cadastros-basicos-ocorrencias/
