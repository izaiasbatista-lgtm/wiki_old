---
title: "Portal – Novidade de Versão"
id: 12222
slug: "portal-novidade-de-versao-163"
url: "https://wiki.simeon.com.br/portal-novidade-de-versao-163/"
data: "2022-09-19T11:54:50"
modificado: "2023-02-24T16:27:52"
pasta: "1.5-PORTAL/1.5.2-PRODUTIVIDADE/Fornecedores/02-Criar-e-configurar-um-questionário-de-Fornecedores"
categorias:
  - "02- Criar e configurar um questionário de Fornecedores"
  - "06- Melhorias do Módulo"
  - "Fornecedores"
  - "Reunião"
tags:
  - "ata"
  - "BLOQUEIO DE FORNECEDORES"
  - "calculo conformidade"
  - "CÁLCULO CONFORMIDADE PARA MÚLTIPLOS AVALIADORES"
  - "cálculo fornecedor"
  - "fornecedores"
  - "gestor de fornecedor"
  - "multiplos avaliadores"
  - "MÚLTIPLOS AVALIADORES E DATA REFERÊNCIA"
  - "reunião"
---

# Portal – Novidade de Versão
![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/Imagens-Engracado-PNG-e-Vetor_-com-Fundo-Transparente-Para-Download-Gratis-_-Pngtree-removebg-preview-164x300.png)

**Veja as principais alterações da versão na configuração do módulo Portal.**

Falaremos nesse artigo os seguintes **_tópicos_**: 

-   **POSSIBILIDADES DE ENVIAR ATA DAS REUNIÕES,**
-   **BLOQUEIO DE FORNECEDORES,**
-   **MÚLTIPLOS AVALIADORES E DATA REFERÊNCIA,**
-   **CÁLCULO CONFORMIDADE PARA MÚLTIPLOS AVALIADORES.**

# **Portal> Comunicação> Reuniões  
**

**Esta versão conta com a possibilidade de enviar Ata de uma Reunião no EPA aos participantes que não compareceram à Reunião.**

-    O envio é realizado aos participantes via **E-mail,**
-   Participantes logins do EPA (Recebe o e-mail com o link para assinar a ata),
-   Clientes (Recebe o e-mail, SEM o link para assinar a ata),
-   Convidados (Recebe o e-mail, SEM o link para assinar a ata).

Edite uma reunião e realize a configuração:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6328828c472e2.png)

# **Portal > Produtividade > Fornecedores**

Esta versão conta com algumas melhorias para o Módulo de Fornecedores no EPA.

## **BLOQUEIO DE FORNECEDORES**

**Possibilidade de categorizar um Fornecedor como Bloqueado,**

1.  Acesse a aba![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6328c94f8d82a.png) em formulário Pessoa do fornecedor,
2.  Cadastre um bloqueio,
3.  No Painel de Fornecedores aparecerá uma sinalização que XX Fornecedor está Bloqueado,
4.  E assim também **os avaliadores não serão notificados no Box** da tela principal para realizar avaliações deste Fornecedor.

Para desfazer a ação de bloqueio é só acessar a aba Bloqueio Fornecedor e criar a ação de desbloquear.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6328cad595ef1.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6328c9f4027fb.png)

⇓

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6328ca5211e3d.png)

## **MÚLTIPLOS AVALIADORES E DATA REFERÊNCIA**

 **Possibilidade de configurar múltiplos avaliadores para participarem de um ciclo de avaliação do Fornecedor:**

-   Acesse a aba ![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6328cd633c777.png)  em formulário Pessoa do fornecedor,
-   No ambiente Avaliações do Fornecedor configure os avaliadores que participarão do processo,

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6329b9937eff8.png)

-   Para cada avaliador configure uma data referência, para que o início da avaliação seja programada no EPA,
-   Configurado um avaliador, caso ele não tenha realizado ainda avaliação sobre o fornecedor, a data da próxima avaliação será o cálculo de (data **referência+Periodicidade**):

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6328cfe5d39bb.png)

-   Quando o avaliador ter realizado um ciclo de avaliação sobre tal fornecedor, a data referência não precisará ser alterada e o EPA calculará automaticamente a data da próxima avaliação (data da resposta da última **avaliação+Periodicidade**):

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6329b7390993b.png)

-   A cada data programada o box de acesso a avaliação dos fornecedores aparecerão na tela principal dos Avaliadores no EPA. E também no acesso de usuários que possuem a permissão: Gestor de Fornecedores.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6329b398e4036.png)

## **OBSERVAÇÃO**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6329bdd9cd6e2.png)

## **CÁLCULO CONFORMIDADE PARA MÚLTIPLOS AVALIADORES**

 No Epa no módulo de fornecedores adequamos o cálculo da conformidade (avaliação) para a possibilidade da avaliação de múltiplos avaliadores à um fornecedor!

-   **Quando acontecer de 1 Fornecedor ser avaliado por ‘N’ avaliadores o EPA fará:**
-   Média aritmética sobre as últimas notas recebidas nas pesquisas/avaliação, respeitando a periodicidade do momento. E após isso comparará com a nota esperada, configurada dentro do Tipo de Fornecedor.

EX:

Pesquisa X:    ((Avaliador 1 + Avaliador 2 + Avaliador 3) / 3 ) = Média Nota Obtida Pesquisa X. 

-   **Caso o tipo de fornecedor possua ‘N’ questionários configurados para avaliação do fornecedor, o EPA fará:**
-   Média aritmética sobre as últimas notas recebidas em cada pesquisas/avaliação, respeitando a periodicidade do momento.
-   E após isso, fará uma média aritmética com os valores das médias gerais obtidas em cada pesquisa.
-   Ao gerar uma média geral, o sistema comparará este valor com a nota esperada, configurada dentro do Tipo de Fornecedor.

EX:

Pesquisa X:    ((Avaliador 1 + Avaliador 2 + Avaliador 3) / 3 ) = Média Nota Obtida Pesquisa X.

Pesquisa Y:    ((Avaliador 1 + Avaliador 2 + Avaliador 3) / 3 ) = Média Nota Obtida Pesquisa Y.

Media Final:  ((Pesquisa X + Pesquisa Y) / 2 )= Média Final Nota Obtida.

## **OBSERVAÇÃO**

Nos Cenários de utilização de múltiplos avaliadores para um fornecedor, é considerado no cálculo de média aritmética somente as notas dos avaliadores que já responderam a pesquisa.

> **EX:**

-   5 avaliadores estão configurados para avaliar um Fornecedor.
-   onde 3 responderam,
-   2 ainda não,

O cálculo aritmético será sobre as notas dos 3 avaliadores que já responderam a avaliação.**R: (nota1+ nota2+ nota3)/ 3 = nota**

#### **Aproveite essa melhoria!**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos a disposição!**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_62191d147280f.png)

---

Fonte: https://wiki.simeon.com.br/portal-novidade-de-versao-163/
