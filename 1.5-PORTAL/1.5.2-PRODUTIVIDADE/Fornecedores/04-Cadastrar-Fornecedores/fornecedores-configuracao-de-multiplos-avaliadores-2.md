---
title: "Fornecedores – Configuração de Múltiplos Avaliadores"
id: 17901
slug: "fornecedores-configuracao-de-multiplos-avaliadores-2"
url: "https://wiki.simeon.com.br/fornecedores-configuracao-de-multiplos-avaliadores-2/"
data: "2025-07-15T15:45:18"
modificado: "2025-08-12T10:01:49"
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
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Neste artigo, você vai aprender como configurar múltiplos avaliadores no módulo de Fornecedores do EPA. Mostramos como definir os avaliadores, programar a data da próxima avaliação e entender o cálculo da conformidade quando há mais de um avaliador envolvido. Tudo isso para garantir avaliações mais completas e alinhadas com a periodicidade definida.**

**Como configurar múltiplos avaliadores para participarem de um ciclo de avaliação do fornecedor**

Acesse a aba **Parametrização** Fornecedor e no ambiente **Avaliações do Fornecedor**, configure os avaliadores que irão participar do processo de avaliação.

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_68769d11417b4.png)

**Cálculo da Data da Próxima Avaliação**

Para cada avaliador, configure uma data de referência. A partir dela, o EPA programará automaticamente o início da avaliação.

Se o avaliador ainda não tiver realizado nenhuma avaliação, a data da próxima será calculada como:  
  
**Data de Referência + Intervalo.**

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_68769cbc4b400.png)

Se o avaliador já tiver realizado uma avaliação para o fornecedor, a data de referência não precisa ser ajustada. O EPA calculará automaticamente a próxima avaliação como: **Data da Última Avaliação + Intervalo.**

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_68769daa0e4cd.png)

**Importante:**  
  
Se **não houver Data de Referência nem Data da Próxima Avaliação** configuradas, mas o fornecedor **já tiver sido avaliado**, o EPA usará como base a **data em que a última avaliação foi respondida**, somando o intervalo definido para calcular automaticamente a próxima avaliação.

Nas datas programadas, o **box de acesso à avaliação** ficará visível na **tela principal dos Avaliadores**, além de estar disponível para usuários com a permissão de **Analista de Fornecedores.**

**  
Notas na Lista de Fornecedores**

A coluna **Conformidade Pesquisas** exibe diferentes status de acordo com a situação de avaliação do fornecedor:

-   **Nota numérica** (ex: `75,00`, `33,33`): indica que o fornecedor foi avaliado e mostra a média obtida nas pesquisas, conforme o cálculo realizado pelo EPA.
    
-   **Avaliação Expirou**: apresentado quando o fornecedor já foi avaliado anteriormente, mas entrou em um novo ciclo de avaliação (de acordo com a periodicidade definida) sem que a nova avaliação tenha sido respondida.
    
-   **Não avaliado**: exibido quando o fornecedor ainda **não possui nenhuma avaliação registrada** no sistema.
    

Esses indicadores permitem uma visualização rápida do status de cada fornecedor, facilitando o acompanhamento e a gestão dos ciclos avaliativos.

#### Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6876a04b73815.png)

**Cálculo da Conformidade para Múltiplos Avaliadores**

No módulo de fornecedores do EPA, o cálculo da conformidade (avaliação) foi adaptado para contemplar a participação de múltiplos avaliadores para um mesmo fornecedor.

Quando um fornecedor é avaliado por diversos avaliadores, o EPA realiza o seguinte procedimento:

-   Calcula a média aritmética das últimas notas recebidas nas pesquisas ou avaliações, respeitando a periodicidade vigente.
    
-   Compara essa média com a nota esperada, configurada no Tipo de Fornecedor.
    

**Exemplo:**

Para a Pesquisa X, com três avaliadores:

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6876a0bf26ba8.png)

Se o Tipo de Fornecedor possui mais de um questionário para avaliação, o EPA:

-   Calcula a média aritmética das últimas notas de cada pesquisa, conforme a periodicidade.
    
-   Depois, faz uma média aritmética entre as médias obtidas em cada pesquisa.
    
-   Por fim, compara essa média geral com a nota esperada, conforme configuração do Tipo de Fornecedor.
    

**Exemplo:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6876a0fa3f69f.png)

**Observação importante**

No cálculo para múltiplos avaliadores, são consideradas apenas as notas dos avaliadores que já responderam à pesquisa.

Por exemplo, se 5 avaliadores estão configurados para avaliar um fornecedor, mas apenas 3 já responderam, o cálculo será feito apenas com essas 3 notas:

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6876a137d99a8.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2025/07/img_6876a16adf5e1.png)

---

Fonte: https://wiki.simeon.com.br/fornecedores-configuracao-de-multiplos-avaliadores-2/
