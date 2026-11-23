---
title: "Fornecedores – Cálculo conformidade Documentos e Avaliações"
id: 17965
slug: "fornecedores-calculo-conformidade-documentos-e-avaliacoes-2"
url: "https://wiki.simeon.com.br/fornecedores-calculo-conformidade-documentos-e-avaliacoes-2/"
data: "2025-07-16T14:32:37"
modificado: "2025-12-17T05:45:35"
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
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Neste artigo, vamos explicar como o EPA calcula a conformidade dos documentos e das pesquisas de avaliação dos fornecedores. Esse processo permite acompanhar se os fornecedores estão cumprindo os critérios exigidos, tanto na entrega e validade dos documentos quanto na qualidade dos serviços prestados.** **Você verá como o sistema valida os documentos vinculados, aplica o cálculo com base nos pesos definidos e compara o resultado com a nota de conformidade configurada. Também mostraremos como são consideradas as notas das pesquisas respondidas pelos avaliadores responsáveis.**

O módulo de Fornecedores do EPA realiza, para cada fornecedor em acompanhamento, um cálculo que verifica se os **documentos vinculados** e as **avaliações recebidas** estão ou não em conformidade com os critérios definidos.

### **Conformidade dos Documentos do Armário**

Para avaliar a conformidade dos documentos publicados no **Armário Virtual**, o EPA realiza as seguintes validações iniciais:

As validações realizadas serão listadas a seguir:

-   O(s) documento(s) deste fornecedor precisam existir no EPA e estarem vinculados ao tipo de documento relacionado na configuração do tipo de fornecedor;
-   O(s) documento(s) vinculado(s) no armário virtual deste fornecedor, não podem estar vencidos e com o Status Inativo no EPA;
-   O(s) documento(s) vinculado(s) no armário virtual deste fornecedor, no campo Pessoa Física/Jurídica deve estar selecionado o nome do fornecedor;
-    O(s) documento(s) vinculado(s) no armário virtual deste fornecedor, estar com campo de data de vencimento: vazio / sem informação no EPA.
-   E o(s) documento(s) vinculado(s) no armário virtual deste fornecedor, tem que estar vinculado a Unidade gerencial que o fornecedor é avaliado.

Após essas validações, o sistema aplica um **cálculo de regra de três** para verificar o percentual de conformidade do fornecedor com base nos pesos atribuídos aos documentos.

Esse cálculo considera:

• A **soma de todos os pesos** (relevância) dos tipos de documentos vinculados no tipo de fornecedor.  
  
• A **soma dos pesos** dos documentos que o fornecedor efetivamente publicou e que estão válidos.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6879942dd29d1.png)

-   Após isso, é somado somente os pesos dos tipos de documentos vinculados no tipo de fornecedor, em que este fornecedor possui documentos publicados.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_687993ab31391.png)

Vamos somar os pesos dos tipos de documentos nos quais o fornecedor possui documentos publicados no EPA. Neste exemplo, os pesos correspondentes são 10 e 3, totalizando **13**.

Em seguida, aplicamos a Regra de 3 para calcular o percentual de conformidade:

-   **A** = Soma de todos os pesos dos tipos de documentos disponíveis. Neste caso: 10 + 4 + 3 = **17**
    
-   **B** = Soma dos pesos dos tipos de documentos nos quais o fornecedor possui publicações. Neste caso: 10 + 3 = **13**
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b4b0cf0ee6a.png)

O resultado desse cálculo gera um valor em formato percentual, que representa a conformidade documental do fornecedor naquele momento. A partir desse valor, o sistema realiza a comparação com o valor configurado como **Nota Conformidade Documentos** no Tipo de Fornecedor.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_687995bc97089.png)

**Concluindo:**

-   Se o resultado obtido for **igual ou superior** à **Nota Conformidade Documentos**, o fornecedor será considerado **em conformidade** com os documentos publicados no Armário.
    
-   Se o resultado for **inferior** à **Nota Conformidade Documentos**, o fornecedor será considerado **fora de conformidade**.
    

Neste exemplo, o resultado do cálculo foi **76,47%**. Como a **Nota Conformidade Documentos** configurada para o tipo de fornecedor é **90**, o fornecedor está **fora de conformidade** com os documentos publicados no Armário.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6879976ce6425.png)

**Importante:**  
  
Caso algum documento publicado pelo fornecedor no Armário Virtual esteja **vencido**, o EPA **desconsidera o peso** configurado para o respectivo tipo de documento no Tipo de Fornecedor. Nesse caso, o valor do peso passa a ser considerado como **“0” (zero)** no cálculo de conformidade.

### Como é calculada a conformidade das Pesquisas/Avaliações?

Para verificar se um fornecedor está **em conformidade nas avaliações recebidas**, o EPA realiza a seguinte validação:

####  **Conformidade das Pesquisas/Avaliações:**

O sistema considera a **nota geral** obtida na última vez em que o **avaliador responsável** configurado respondeu ao questionário.

Essa média geral é calculada com base nas respostas fornecidas e pode ser visualizada na área **“Visualizar Respostas Individuais”** do formulário.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b5aee720ef7.png)

Os questionários considerados nessa análise pelo EPA são **aqueles vinculados à configuração do Tipo de Fornecedor**.

Para verificar se o fornecedor está em conformidade, o sistema **compara a nota geral da última resposta recebida** com o valor definido no campo **Nota Conformidade Pesquisas**, configurado no cadastro do Tipo de Fornecedor.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6879986269658.png)

**Concluindo:**

-   Se a **Nota Geral** da última resposta da pesquisa for **igual ou superior** à **Nota Conformidade Pesquisas**, o fornecedor será considerado **em conformidade** quanto às avaliações recebidas sobre os serviços prestados à empresa.
    
-   Caso a **Nota Geral** seja **inferior** à **Nota Conformidade Pesquisas**, o fornecedor será considerado **fora de conformidade** em relação às avaliações recebidas.
    

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6879991d9f553.png)

**Importante:**

-   Se o fornecedor possuir duas ou mais pesquisas configuradas no Tipo de Fornecedor, o EPA continuará considerando a **Nota Geral** das últimas respostas recebidas pelo avaliador responsável por cada avaliação.
    
-   No entanto, para calcular a conformidade geral, o sistema fará a média das notas gerais, somando-as e dividindo pelo número total de questionários configurados.
    

**Exemplo:**  
  
Se houver três questionários configurados para avaliação do fornecedor, o cálculo será:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/img_62b5b368bf816.png)

Após esse cálculo, o sistema realiza a validação final para verificar se o fornecedor está em conformidade, comparando a média obtida com o valor da **Nota Conformidade Pesquisas** configurada no Tipo de Fornecedor.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6877b531bb54d.png)

---

Fonte: https://wiki.simeon.com.br/fornecedores-calculo-conformidade-documentos-e-avaliacoes-2/
