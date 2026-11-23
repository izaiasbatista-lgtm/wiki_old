---
title: "Ocorrências – Utilizar quantidades de dias por Tipo de Ocorrências"
id: 2881
slug: "como-utilizar-as-quantidades-de-dias-dos-tipos-de-ocorrencias"
url: "https://wiki.simeon.com.br/como-utilizar-as-quantidades-de-dias-dos-tipos-de-ocorrencias/"
data: "2020-04-23T15:55:58"
modificado: "2022-10-03T11:00:46"
pasta: "1.3-POLÍTICAS-DE-QUALIDADE/Ocorrências/0-Parametrizar-estrutura-de-controle"
categorias:
  - "0- Parametrizar estrutura de controle"
tags:
  - "analise de causa"
  - "dias"
  - "ocorrência"
  - "prazo"
  - "tipo"
---

# Ocorrências – Utilizar quantidades de dias por Tipo de Ocorrências
Na tela de cadastro de tipo de ocorrência, existem dois campos o **Dias para finalizar a Ocorrência (1)** e **Dias para realizar Análise de Causa(2).** Nesses campos pode ser informado a quantidade de dias padrão, para ser calculado o prazo para a ocorrência finalizar e o prazo para análise de causa.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/02/img_5e56c41ee355b.png)

-   **Dias para finalizar a Ocorrência:**
    
    Calcula a Data Prevista Finalização da ocorrência, mas será calculado apenas se o analista da qualidade fizer a avaliação da ocorrência.  
    Quando for realizar a avaliação da ocorrência quando selecionar o tipo da ocorrência, vai aparecer a mensagem**“Deseja alterar a data prevista de finalização conforme o prazo para este tipo de Ocorrência?”**  
    Se marcar como **Sim** puxa o prazo do tipo da ocorrência, e se marcar **Não** permanece a data conforme o prazo do parâmetro **“Data default para iniciar as datas de um ponto de partida (hoje) até os dias que foram selecionados”** ou o usuário pode informar manual.
    

-   **Dias para realizar Análise de Causa:**  
    Calcula a data para finalizar a ocorrência, a partir da data que a ocorrência foi encaminhada para a fase Analisar Causa e Fazer Plano de Ação. E aparecera na lista de ocorrências na coluna dias restantes, apenas quando a análise de causa estiver vencida.  
    Por exemplo:   
    No tipo de ocorrência  “Potencial não conformidade” coloquei o prazo de 10 dias para realizar a análise de causa
    
    ![](https://wiki.simeon.com.br/wp-content/uploads/2020/02/img_5e56ce347c351.png)
    
    Quer dizer que se encaminhei a minha ocorrência para realizar análise de causa hoje dia 11/02, o responsável da ocorrência tem até o dia 21/02 para realizar a análise de causa. Após essa data será sinalizado na lista de  ocorrências na coluna **dias restantes (3)** que a ocorrência está com a análise de causa vencida mostrando a **data fim para realizar a análise (4)** e vai ser contabilizado a quantidade de **dias que a análise está em atraso(5).**
    
    ![](https://wiki.simeon.com.br/wp-content/uploads/2020/02/img_5e56cf064d0f1.png)

---

Fonte: https://wiki.simeon.com.br/como-utilizar-as-quantidades-de-dias-dos-tipos-de-ocorrencias/
