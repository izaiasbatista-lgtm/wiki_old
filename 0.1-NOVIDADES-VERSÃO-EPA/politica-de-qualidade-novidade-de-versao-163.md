---
title: "Política de Qualidade – Novidade de Versão 163"
id: 12075
slug: "politica-de-qualidade-novidade-de-versao-163"
url: "https://wiki.simeon.com.br/politica-de-qualidade-novidade-de-versao-163/"
data: "2022-09-12T16:50:20"
modificado: "2022-10-14T10:04:59"
pasta: "0.1-NOVIDADES-VERSÃO-EPA"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
tags:
  - "analise de risco"
  - "analista da qualidade"
  - "analista de Documentos"
  - "Box da tela principal – Ocorrências"
  - "Box da tela principal – Ocorrências (Acompanhar como Gestor)"
  - "data proxima análise"
  - "modo causa"
  - "modo falha"
  - "Risco"
---

# Política de Qualidade – Novidade de Versão 163
![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/Imagens-Engracado-PNG-e-Vetor_-com-Fundo-Transparente-Para-Download-Gratis-_-Pngtree-removebg-preview-164x300.png)

**Veja as principais alterações da versão 163 no módulo Política de Qualidade.**

# **Política de Qualidade> Gestão de Riscos  
**

-   **_Novos parâmetros para habilitar ou não os campos modo falha e modo causa nas análises dos riscos:_** 

-   -   Acesse o Ambiente: Parametrização do sistema e procure pelos parâmetros:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_631f8e62dc6f0.png)

-   -   Os parâmetros habilitarão ou não a visualização e uso dos campos: Modo Causa e Modo Falha, na análise do risco. Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_631f8f1e70e0a.png)

-   **Melhorias na configuração de periodicidade das análises dos Riscos no EPA.**

-   -   Inserido um novo campo para informar a Periodicidade em meses, em que devem acontecer as análises de um risco.
    -   Quando a periodicidade for informada no Risco na edição do risco, ao realizar uma análise o EPA trará automaticamente a data da próxima análise.
        -   Insira uma primeira \*Data da análise:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_631f973c1387c.png)

-   -   Criado um parâmetro para habilitar ou não a possibilidade de informar a data de análise maior que o dia atual.
    -   Acesse o Ambiente: Parametrização do sistema e procure pelo parâmetro:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_631f98948cd11.png)

-   -   -   O parâmetro influenciará no campo \* Data da Análise, quando for realizado a análise no risco.
            -   O parâmetro com valor SIM permitirá selecionar uma data maior que o dia atual.
            -   O parâmetro com valor NÃO, não permitirá selecionar uma data maior que o dia atual.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_631f98c4b0325.png)

# **Política de Qualidade> Gestão de Documentos  
**

-   **_Usuários com permissão “Analista de Documentos”, poderão ver documentos onde as unidades gerenciais destes forem de Unidades em que ele se Comunica._**
    -   Nesta versão o analista de documentos conseguirá visualizar somente os documentos das unidades gerenciais que ele se comunica.
    -   Essa alteração foi aplicada em:
        -   _Listagem de Documentos (Tanto nas categorias do lado esquerdo quanto na própria listagem dos documentos em si),_
        -   _Foi aplicado na tela de dashboard dos documentos,_
        -   _Foi aplicado no box de acesso da tela principal e,_
        -   _Também foi aplicado nos relatórios de documentos._

-   **Melhoria para inserir e visualizar as permissões dos usuários no EPA em um documento da qualidade.**
    -   Esta versão conta com uma melhoria na aba Permissões ao editar um documento da qualidade para  conceder e listar as permissões de acesso.
    -   Nova forma de selecionar os usuários que terão acesso ao documento e conceder as permissões a eles,
    -   Apresentação dos usuários em uma listagem, que facilitará a pesquisa e visualização das informações e respectivas permissões dos usuários.
        -   Observação: Usuários que possuem permissões nos documentos vindas de perfis de usuários, estarão bloqueados para edição dentro da aba: Permissões no documento. As alterações devem ser feitas no perfil.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_632236b4b64a2.png)

# **Política de Qualidade> Gestão de Ocorrências**

-   **Em um ambiente Multi-Empresa agora a Gestão das ocorrências no EPA serão feitas pelo analista da qualidade em respectivas UENs em que ele tem acesso.**

-   -   A permissão Analista da Qualidade agora possui o vínculo a configuração de UENs no EPA,
    -   O **Analista da Qualidade** agora terá acesso a somente as ocorrências da sua “empresa”, ou seja sua UENs que estão dentro da sua Comunicação.
    -   Configuração pode ser realizada no acesso do usuário: gerenciar usuários e no perfil de usuário.

-   -   -   O conceito foi aplicado nos respectivos locais:
            -   _A Listagem de Ocorrências_
            -   _O Dashboard que vem junto da Listagem de Ocorrências_
            -   _A Exportação de Ocorrências – Relatório disponível na listagem,_
            -   _Box da tela principal – Ocorrências (Acompanhar como Gestor),_
            -   _Busca Ocorrências pelo Radar,_
            -   _Ambiente Relatório de Ocorrências,_
            -   _E-mail Inclusão de Ocorrência: E-mails são enviados para os analistas da qualidade, considerando a nova regra das UENs._

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_632877f87825b.png)

## _Observação:_

## _Box da tela principal – Ocorrências (Acompanhar como Gestor):_

## _![](https://wiki.simeon.com.br/wp-content/uploads/2022/05/7a6f195b92b281a19434c2d7f092da91-180x300.jpg)_

> O usuário Analista da Qualidade, com suas respectivas UENs selecionadas para acesso  no sistema, verá em sua caixa box as ocorrências que estiverem nas seguintes fases:

-   -   _1 – Avaliar ocorrência,_
    -   _3 – Validar a Análise de Causa e/ou Plano de Ação,_
    -   _5 – Validar Execução Ação(ões),_
    -   _5 – Validar Execução Ação(ões)> Checagem de eficácia (ocorrências concluídas)._

O que não aparecerá no respectivo box:

-   -   _– Ocorrências vinculas a outras,_
    -   _– Ocorrências canceladas ou excluídas._

#### **Aproveite essa melhoria!**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos a disposição!**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_62191d147280f.png)

---

Fonte: https://wiki.simeon.com.br/politica-de-qualidade-novidade-de-versao-163/
