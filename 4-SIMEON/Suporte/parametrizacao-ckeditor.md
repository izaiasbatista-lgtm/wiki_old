---
title: "Parametrização – CKEditor"
id: 18408
slug: "parametrizacao-ckeditor"
url: "https://wiki.simeon.com.br/parametrizacao-ckeditor/"
data: "2025-09-30T19:45:06"
modificado: "2025-10-29T09:44:42"
pasta: "4-SIMEON/Suporte"
categorias:
  - "Suporte"
  - "Versão 194"
tags:
---

# Parametrização – CKEditor
![](https://wiki.simeon.com.br/wp-content/uploads/2025/10/img_68e2dceaefbf9.png)

**Nesse artigo, apresentamos a criação e evolução do tipo de parametrização CKEditor no EPA. O objetivo é permitir que campos estratégicos passem a oferecer suporte a formatação rica (HTML), garantindo maior flexibilidade na edição de textos, sem perder o padrão visual, de permissões e de armazenamento já estabelecidos no sistema.**

> O **CKEditor** é um editor de texto avançado que permite a criação e formatação de conteúdo com recursos semelhantes aos de editores de texto comuns (como negrito, itálico, listas e links). Ele converte automaticamente a formatação aplicada em código **HTML**, garantindo que o texto mantenha o estilo definido e possa ser exibido corretamente em diferentes partes do sistema.

### Criação do Tipo de Parametrização CKEditor

A Inclusão de um novo tipo de parametrização denominado **CKEditor**. Estrutura composta por:

-   **Campo de texto bloqueado** para edição manual.
    
-   **Botão “Editar”** que abre um modal com o CKEditor.
    
-   Persistência do conteúdo em **HTML**, refletido no campo bloqueado.
    
-   Modal seguindo o **padrão visual do EPA**.
    

Para acessar, clique em **Parametrização → Parametrização do Sistema.**

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/09/img_68dc5ceabe608.png)

###  Inclusão do CKEditor em Campos Existentes

O tipo **CKEditor** foi aplicado nos seguintes campos:

-   Texto exibido após as informações de expiração de documento no armário virtual (notificação por e-mail).
    
-   Ajuda do campo **Parecer da Análise de Risco**.
    
-   1ª e 2ª mensagens de e-mail da ouvidoria.
    
-   Texto padrão de alerta para **parabenização por indicadores alimentados**.
    
-   Texto padrão de e-mail para responsáveis que não registraram análises nas etapas selecionadas.
    
-   Texto padrão de alerta para **indicadores não alimentados**.
    
-   Texto padrão de alerta de **vencimento de prazo para alimentação de indicador**.
    
-   Mensagem para usuários que não acessam o EPA.
    
-   Ajuda do campo **evidência objetiva** ao incluir nova ocorrência.
    
-   Texto padrão de **notificação de abertura** de atendimento para cliente.
    
-   Texto do e-mail padrão de **boas-vindas ao usuário**.
    

Esses campos são editáveis apenas via modal CKEditor, com conteúdo salvo em HTML, exibido em modo somente leitura no campo bloqueado, e respeitando as regras de permissão e armazenamento do sistema.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/09/img_68dc5d37a3868.png)

A implementação do tipo de parametrização **CKEditor** trouxe maior flexibilidade e usabilidade para a edição de textos no EPA, permitindo o uso de formatação rica e mantendo a segurança e padronização do sistema. Com as melhorias já concluídas e os ajustes em andamento, espera-se aprimorar a experiência do usuário e otimizar a manutenção de conteúdos em diferentes áreas do sistema.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/10/img_68e2dcb3f0f6b.png)

---

Fonte: https://wiki.simeon.com.br/parametrizacao-ckeditor/
