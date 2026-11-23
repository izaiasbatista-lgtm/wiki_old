---
title: "Fornecedores – Configuração de Múltiplos Avaliadores"
id: 15905
slug: "fornecedores-configuracao-de-multiplos-avaliadores"
url: "https://wiki.simeon.com.br/fornecedores-configuracao-de-multiplos-avaliadores/"
data: "2024-07-24T17:46:39"
modificado: "2024-07-24T17:52:11"
pasta: "1.5-PORTAL/1.5.2-PRODUTIVIDADE/Fornecedores/04-Cadastrar-Fornecedores"
categorias:
  - "04- Cadastrar Fornecedores"
  - "Fornecedores"
tags:
  - "Avaliação Expirou"
  - "Data da Próxima Avaliação"
  - "data referencia"
  - "Expirou"
  - "nao avaliado"
  - "Periodicidade"
---

# Fornecedores – Configuração de Múltiplos Avaliadores
-    **Como configurar múltiplos avaliadores para participarem de um ciclo de avaliação do Fornecedor:**
    
    Acesse a aba ![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6328cd633c777.png)  em formulário Pessoa do fornecedor. No ambiente Avaliações do Fornecedor configure os avaliadores que participarão do processo.
    

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6329b9937eff8.png)

-    **Cálculo da Data da Próxima Avaliação:**
    
      
    Para cada avaliador configure uma data referência, para que o início da avaliação seja programada no EPA.  
    Configurado um avaliador, caso ele não tenha realizado ainda avaliação sobre o fornecedor, a data da próxima avaliação será o cálculo de (data **referência+Periodicidade**):
    

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6328cfe5d39bb.png)

Quando o avaliador ter realizado um ciclo de avaliação sobre tal fornecedor, a data referência não precisará ser alterada e o EPA calculará automaticamente a data da próxima avaliação ( **DatadaPróximaAvaliaçãoanterior+Periodicidade**):

![](https://wiki.simeon.com.br/wp-content/uploads/2024/07/Sem-titulo.png)

**  
Obs.:** Caso não tenha **Data Referência** configurada e nem **Data da Próxima Avaliação**, e o fornecedor já foi avaliado, o EPA vai considerar a data em que a avaliação foi respondida para calcular a data da próxima avaliação

A cada data programada o box de acesso à avaliação dos fornecedores aparecerão na tela principal dos Avaliadores no EPA. E também no acesso de usuários que possuem a permissão: Gestor de Fornecedores.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6329b398e4036.png)

## **  
Importante:**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/09/img_6329bdd9cd6e2.png)

-   **Cálculo da Conformidade para múltiplos Avaliadores:**

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

## **Observação:**

Nos Cenários de utilização de múltiplos avaliadores para um fornecedor, é considerado no cálculo de média aritmética somente as notas dos avaliadores que já responderam à pesquisa.

> **EX:**

-   5 avaliadores estão configurados para avaliar um Fornecedor.
-   onde 3 responderam,
-   2 ainda não,

O cálculo aritmético será sobre as notas dos 3 avaliadores que já responderam à avaliação.**R: (nota1+ nota2+ nota3)/ 3 = nota**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos a disposição!**

---

Fonte: https://wiki.simeon.com.br/fornecedores-configuracao-de-multiplos-avaliadores/
