---
title: "Fornecedores – Cálculo conformidade Documentos e Avaliações"
id: 11152
slug: "fornecedores-calculo-conformidade-documentos-e-avaliacoes"
url: "https://wiki.simeon.com.br/fornecedores-calculo-conformidade-documentos-e-avaliacoes/"
data: "2022-06-23T11:23:23"
modificado: "2025-09-17T15:47:25"
pasta: "1.5-PORTAL/1.5.2-PRODUTIVIDADE/Fornecedores/03-Criar-tipos-de-fornecedores"
categorias:
  - "03- Criar tipos de fornecedores"
  - "08 -Qualificação de Fornecedores"
tags:
  - "calculo conformidade"
  - "Como é calculado a conformidade das Pesquisas/Avaliações?"
  - "Como é calculado a conformidade dos Documentos e Avaliações?"
  - "concluir fornecedores"
  - "desconsidera o valor"
  - "fornecedor"
  - "Gerenciar fornecedores"
  - "peso fornecedores"
---

# Fornecedores – Cálculo conformidade Documentos e Avaliações
![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/Conformidade-Fornecedores-247x300.png)![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/banner_fornecedores-1-300x75.png)

## **Como é calculado a conformidade dos Documentos ?** 

**1** **–** O módulo de fornecedores realiza para cada fornecedor em acompanhamento um cálculo, para validar se os documentos vinculados e as avaliações realizadas deste estão em conformidade ou não.

**1.2 Conformidade dos Documentos do Armário:**

Para avaliar se um fornecedor está em conformidade com seus documentos publicados no armário, o EPA realiza algumas validações.

As validações realizadas serão listadas a seguir:

-   -   -   O(s) documento(s) deste fornecedor precisam existir no EPA e estarem vinculados ao **tipo de documento** relacionado na configuração do **tipo de fornecedor**;
            
    -    
        -   O(s) documento(s) vinculado(s) no armário virtual deste fornecedor, **não podem estar vencidos** e com o **Status Inativo** no EPA;
            
        -   O(s) documento(s) vinculado(s) no armário virtual deste fornecedor, no campo **Pessoa Física/Jurídica** deve estar preenchido com o nome do fornecedor;
            
    -    
        -   O(s) documento(s) vinculado(s) no armário virtual deste fornecedor, estar com campo de data de vencimento: vazio / sem informação no EPA.
        -   Ou o(s) documento(s) vinculado(s) no armário virtual deste fornecedor, tem que estar vinculado a **Unidade gerencial que o fornecedor é avaliado**.
    

Após essa validação inicial:

_O cálculo regra de três é realizado para analisar se os documentos do fornecedor estão em conformidade com o percentual esperado ou não. Para o cálculo analisa-se:_

-   -   _Primeiramente é realizado a soma de todos os Pesos (relevância do documento) informados nos tipos de documento vinculados na configuração do tipo de fornecedor. Veja:_
        

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b4b04c2afe1.png)

-   -   Após isso, é somado somente os pesos dos tipos de documentos vinculados no tipo de fornecedor, em que este fornecedor possui documentos publicados. Veja:
        

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b4b0aa73b3d.png)

O próximo passo é realizar o cálculo Regra de 3:

**A =** Soma de todos os pesos dos tipos de documentos;

**B =** Soma dos pesos dos tipos de documentos em que o fornecedor possui documentos publicados.

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b4b0cf0ee6a.png)

Com o resultado deste cálculo gera um valor no formado percentual, onde o sistema apresenta o resultado em porcentagem da conformidade dos documentos deste fornecedor neste momento.

-   A partir deste resultado obtido, o sistema realiza uma comparação deste com o valor da **Nota conformidade Documentos,** no tipo de fornecedor:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b4b0f608936.png)

**Concluindo**:

-   Se o resultado obtido for igual ou maior a Nota Conformidade Documentos, o fornecedor estará em conformidade com os seus documentos publicados no armário.

-   Se o resultado obtido for Menor que a Nota Conformidade Documentos, o fornecedor não estará em conformidade com os seus documentos publicados no armário.

Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b4b35a185b0.png)

**Importante:**![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62a0a54017951-226x300.png)

Caso algum documento do fornecedor do armário virtual esteja vencido, o EPA desconsidera o valor inserido no peso do tipo de documento deste, informado na configuração do tipo de fornecedor.

O valor do peso passa a ser: “0”, zero.

Veja onde os pesos são desconsiderados quando o documento relacionado está vencido:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b4c3da93952.png)

## **Como é calculado a conformidade das Pesquisas/Avaliações?**

**2 –** Para verificar se um fornecedor está em conformidade nas avaliações recebidas pelo avaliador responsável na empresa, o EPA realiza a seguinte validação:

**2.1 Conformidade** **das Pesquisas/Avaliações****:**

-   -   O EPA verifica qual foi a **NOTA geral** obtida nas respostas recebidas na **última vez** em que o avaliador responsável configurado respondeu este questionário. Esta média geral obtida pode ser verificada na visualização das respostas do questionário, veja como acessar em: [Visualizar Respostas Individuais.](https://wiki.simeon.com.br/visualizar-resposta-individual/)

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b5aee720ef7.png)

-   -   O(s) questionário(s) em que o EPA realiza essa análise são as pesquisas vinculadas à configuração do Tipo de Fornecedor.

-   -   Para verificar se o fornecedor está em conformidade ou não, o EPA compara a nota geral da última resposta recebida com o valor inserido no campo **Nota Conformidade Pesquisas**, configurado no cadastro do **Tipo de Fornecedor.**

![](https://wiki.simeon.com.br/wp-content/uploads/2024/10/img_6707bebf21528.png)

**Concluindo**:

-   Se o resultado obtido na Nota Geral da resposta da pesquisa for igual ou maior a Nota Conformidade Pesquisas, o fornecedor estará em conformidade em relação às avaliações recebidas sobre seus serviços prestados na empresa.

-   Ou caso o resultado obtido na Nota Geral da resposta da pesquisa for menor que Nota Conformidade Pesquisas, o fornecedor não estará em conformidade em relação às avaliações recebidas sobre seus serviços prestados na empresa.

Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b5b45f868b8.png)

**Importante:**![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62a0a54017951-226x300.png)

→ Só será **considerado no cálculo da conformidade,** a resposta da pesquisa alimentada pelo **Avaliador** configurado no cadastro do fornecedor. Caso não seja, o EPA não vai trazer a nota da pesquisa para o cálculo da conformidade do fornecedor.

→ Caso o fornecedor tenha duas ou mais pesquisas para sua avaliação, configuradas no tipo de fornecedor, o EPA ainda continuará considerando a Nota Geral das últimas respostas recebidas pelo avaliador responsável por estas avaliações.  
Porém, o cálculo para avaliar a média das conformidades será a soma das notas gerais das últimas respostas recebidas, dividido pela quantidade de questionários.

Ex: Se houver três questionários configurados para avaliação do fornecedor, o cálculo será assim:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b5b368bf816.png)

E após isso a validação é realizada, a fim de verificar a conformidade ou não comparando com o valor da nota configurada no tipo de fornecedor: ![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b5b40da7c7b.png).

#### **Aproveite essa melhoria!**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos a disposição!**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_62191d147280f.png)

---

Fonte: https://wiki.simeon.com.br/fornecedores-calculo-conformidade-documentos-e-avaliacoes/
