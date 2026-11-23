---
title: "Plano de Ação: Como o EPA Calcula as Datas"
id: 19014
slug: "plano-de-acao-como-o-epa-calcula-as-datas"
url: "https://wiki.simeon.com.br/plano-de-acao-como-o-epa-calcula-as-datas/"
data: "2026-02-09T18:06:04"
modificado: "2026-03-12T10:28:32"
pasta: "1.1-PLANEJAMENTO/Plano-de-ação"
categorias:
  - "Plano de ação"
tags:
  - "Ação ou Tarefa alterar as datas previstas"
  - "alterar data"
  - "alterar plano de ação/ação/tarefa que o usuário tem acesso"
  - "data fim prevista"
  - "data fim real"
  - "data inicio prevista"
  - "data inicio real"
  - "data prevista"
  - "data real"
  - "Permitir incluir"
  - "Permitir o responsável do Plano de Ação"
---

# Plano de Ação: Como o EPA Calcula as Datas
Um Plano de Ação é uma forma organizada de planejar e acompanhar o que precisa ser feito para atingir um objetivo. Ele ajuda a deixar claro quais atividades serão realizadas, quem é o responsável, quando cada etapa começa e termina e como tudo será executado.

No modelo 5W2H, o Plano de Ação é estruturado a partir de sete perguntas fundamentais:

-   **O Que (What) ?:** quais ações e tarefas precisam ser executadas.
    
-   **Porque (Why) ?:** o motivo ou objetivo de cada ação.
    
-   **Onde (Where) ?:** o local ou contexto onde a ação será realizada.
    
-   **Quando (When) ?:** datas de início e fim previstas e reais.
    
-   **Quem (Who) ?:** responsável pela execução.
    
-   **Como (How) ?:** a forma ou método de execução.
    
-   **Quanto Custa (How Much) ?:** recursos ou custos envolvidos.
    

No EPA, o Plano de Ação é organizado em uma estrutura hierárquica, que define como as atividades se relacionam entre si e como as datas são controladas.  
  
A seguir, é apresentada a estrutura do Plano de Ação e a lógica de funcionamento das datas dentro dessa hierarquia:

**Plano de Ação → Ações → Tarefas**

As **Datas Início e Fim Real,** e as **Datas Início e Fim Previstas** sempre são controladas no **nível mais baixo existente** e refletidas automaticamente para os níveis acima.

![](https://wiki.simeon.com.br/wp-content/uploads/2026/02/img_698a3da36cd5a-e1770667464864.jpeg)

---

**⇒ Exemplo 1 – Plano de Ação com Ações (sem tarefas)**

**Cenário**

O plano de ação possui **2 ações** cadastradas:

-   **Ação 1**  
      
    Data de início real: 05/01/2026  
      
    Data de fim real: 10/01/2026
    
-   **Ação 2**  
      
    Data de início real: 08/01/2026  
      
    Data de fim real: 20/01/2026
    

**  
Como o sistema se comporta**

-   As datas do **Plano de Ação ficam bloqueadas para edição**.
    
-   O sistema calcula automaticamente as datas do plano com base nas ações.
    

**  
Resultado no Plano de Ação**

-   **Data de início real do plano**: 05/01/2026  
      
    (data em que a primeira ação foi iniciada)
    
-   **Data de fim real do plano**: 20/01/2026  
      
    (data em que a última ação foi concluída)
    

📌 O usuário não precisa informar as datas no plano, pois elas são calculadas automaticamente.

---

**⇒ Exemplo 2 – Plano de Ação com Ações e Tarefas**

**Cenário**

O plano possui **1 ação**, e essa ação possui **3 tarefas**:

-   **Tarefa 1**  
      
    Início real: 01/02/2026  
      
    Fim real: 03/02/2026
    
-   **Tarefa 2**  
      
    Início real: 04/02/2026  
      
    Fim real: 06/02/2026
    
-   **Tarefa 3**  
      
    Início real: 07/02/2026  
      
    Fim real: 10/02/2026
    

**  
Como o sistema se comporta**

-   As datas do **Plano de Ação e das Ações ficam bloqueadas**.
    
-   As datas são controladas apenas no nível das **tarefas**.
    
-   O sistema reflete automaticamente as datas:
    
    -   Das tarefas para a ação
        
    -   Da ação para o plano
        

**  
Resultado na Ação**

-   **Data de início real da ação**: 01/02/2026  
      
    (início da primeira tarefa)
    
-   **Data de fim real da ação**: 10/02/2026  
      
    (fim da última tarefa)
    

**Resultado no Plano de Ação**

-   **Data de início real do plano**: 01/02/2026
    
-   **Data de fim real do plano**: 10/02/2026
    

📌 Todas as datas são calculadas automaticamente a partir das tarefas.

---

## **⇒ Exemplo 3 – Plano de Ação sem Ações e sem Tarefas**

**Cenário**

O plano de ação **não possui ações nem tarefas**.

**Como o sistema se comporta**

-   As datas de **início e fim prevista** e **início e fim real** ficam **liberadas para edição diretamente no plano**.
    
-   O usuário informa manualmente as datas.
    

📌 Esse é o único cenário em que as datas podem ser editadas diretamente no Plano de Ação.

---

-   **Quem pode alterar a Data Inicio Prevista e a Data fim Prevista?**
    

Além da atualização automática das datas previstas conforme a **hierarquia do Plano de Ação**, para que o usuário consiga **alterar manualmente as datas previstas** do **Plano de Ação**, **Ação** ou **Tarefa**, é necessário atender a **pelo menos uma** das condições abaixo:

-   Possuir a permissão **Super usuário**.
    
-   Possuir a permissão **“Permitir o responsável do Plano de Ação, Ação ou Tarefa alterar as datas previstas”**.
    
-   Ser o **usuário que realizou a inclusão** do Plano de Ação, da Ação ou da Tarefa. Nesse caso, a alteração das datas previstas é permitida **somente até 1 dia após a criação**. Após esse prazo, a edição não será mais permitida, exceto se o usuário possuir uma das permissões citadas acima.
    

-   **Quem pode alterar a Data Início Real e Data Fim Real?**

Além da atualização automática das datas de **Início Real** e **Fim Real**, realizada pelo sistema conforme a hierarquia do **Plano de Ação**, o usuário também pode alterar esses campos manualmente no **Plano de Ação**, **Ação** ou **Tarefa**, desde que atenda a pelo menos uma das condições abaixo:

-   Possuir permissão **Super Usuário**.
    
-   Possuir a permissão **“Permitir incluir, alterar plano de ação/ação/tarefa que o usuário tem acesso”** .
    
-   Ser o **usuário inclusão do plano de ação/ação/tarefa.**
    
-   Ser o **responsável do plano de ação/ação/tarefa.**
    
-   Ser o **gestor da unidade gerencial responsável do plano de ação/ação/tarefa.**
    
-   Ser **usuário de inclusão ou responsável por iniciativas pai**, em níveis superiores à iniciativa em questão. Nesse caso, o usuário pode editar as informações das iniciativas subordinadas.  
    Por exemplo, um responsável por uma **ação** pode editar os campos das **tarefas** vinculadas a ação.  
    Ou se o usuário é responsável do **plano de ação** então ele pode editar os campos das **ações** e **tarefas** vinculadas ao plano.
    

**

Acesse nossos artigos para saber mais sobre o modulo de Plano de Ação!

**

**[Papéis e Permissões – Plano de Ação](https://wiki.simeon.com.br/planejamento-papeis-e-permissoes-plano-de-acao/)**  
**[Confirmação ao Alterar o Tipo de Ação em Planos](https://wiki.simeon.com.br/planejamento-confirmacao-ao-alterar-o-tipo-de-acao-em-planos/)**  
**[Planos de Ação no painel de indicadores](https://wiki.simeon.com.br/planos-de-acao-no-painel-de-indicadores/)**  
[**Dashboard- Plano de Ação**](https://wiki.simeon.com.br/planejamento-nova-aba-dashboard-nos-planos-de-acao/)

**![](https://wiki.simeon.com.br/wp-content/uploads/2025/09/img_68da8df21910a.png)**

---

Fonte: https://wiki.simeon.com.br/plano-de-acao-como-o-epa-calcula-as-datas/
