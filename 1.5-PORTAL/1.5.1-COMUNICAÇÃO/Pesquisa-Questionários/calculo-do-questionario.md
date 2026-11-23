---
title: "Entendendo o Cálculo do Resultado de Pesquisa"
id: 459
slug: "calculo-do-questionario"
url: "https://wiki.simeon.com.br/calculo-do-questionario/"
data: "2018-05-29T17:51:32"
modificado: "2026-10-21T14:10:07"
pasta: "1.5-PORTAL/1.5.1-COMUNICAÇÃO/Pesquisa-Questionários"
categorias:
  - "Pesquisa/Questionários"
tags:
  - "cálculo"
  - "indice geral"
  - "média"
  - "Não Considera no Cálculo"
  - "nota"
  - "pergunta"
  - "questionario"
  - "Utilizar quantidade de pessoas que responderam como peso da resposta"
---

# Entendendo o Cálculo do Resultado de Pesquisa
![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)  
O resultado da pesquisa pode mudar a forma de cálculo conforme a sua configuração, as opções que podem interferir no cálculo são:  

1.  **Utilizar peso da pergunta no Cálculo da Nota;**
2.  **_Não Considera no Cálculo._**

Segue abaixo como o cálculo é feito, de acordo com cada uma dessas opções.  

Vamos pensar no seguinte cenário para desenvolver o cálculo:

<table style="height: 319px; width: 53.4819%; border-collapse: collapse; border-color: #000000; margin-left: 240px;" border="1"><tbody><tr style="height: 36px; background-color: #8dc6f2;"><td style="width: 18.377%; height: 36px; background-color: #aec8f2; padding-left: 40px; text-align: center;">&nbsp;</td><td style="width: 15.8359%; height: 36px; background-color: #aec8f2; text-align: center;"><strong>Qtde de respostas</strong></td><td style="width: 14.1654%; height: 36px; background-color: #aec8f2; text-align: center;"><strong>Peso</strong></td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 24px;" colspan="3"><strong>Pergunta n°1</strong></td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 24px;">Opção de resposta A</td><td style="width: 15.8359%; height: 24px; text-align: center;">1</td><td style="width: 14.1654%; height: 24px; text-align: center;">100</td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 24px;">Opção de resposta B</td><td style="width: 15.8359%; height: 24px; text-align: center;">3</td><td style="width: 14.1654%; height: 24px; text-align: center;">50</td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 24px;">Opção de resposta C</td><td style="width: 15.8359%; height: 24px; text-align: center;">2</td><td style="width: 14.1654%; height: 24px; text-align: center;">30</td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 24px; text-align: center;" colspan="3">&nbsp;</td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 24px; text-align: left;" colspan="3"><strong>Pergunta n°2</strong></td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 24px;">Opção de resposta A</td><td style="width: 15.8359%; height: 24px; text-align: center;">4</td><td style="width: 14.1654%; height: 24px; text-align: center;">100</td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 24px;">Opção de resposta B</td><td style="width: 15.8359%; height: 24px; text-align: center;">1</td><td style="width: 14.1654%; height: 24px; text-align: center;">50</td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 17px; text-align: center;" colspan="3">&nbsp;</td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 24px; text-align: left;" colspan="3"><strong>Pergunta n°3</strong></td></tr><tr style="height: 24px;"><td style="width: 18.377%; height: 24px;">Opção de resposta A</td><td style="width: 15.8359%; height: 24px; text-align: center;">2</td><td style="width: 14.1654%; height: 24px; text-align: center;">100</td></tr><tr style="height: 26px;"><td style="width: 18.377%; height: 26px;">Opção de resposta B</td><td style="width: 15.8359%; height: 26px; text-align: center;">3</td><td style="width: 14.1654%; height: 26px; text-align: center;">50</td></tr></tbody></table>

<table style="border-collapse: collapse; width: 27.2322%; height: 95px; margin-left: 400px;" border="1"><tbody><tr style="height: 22px; background-color: #aec8f2;"><td style="width: 3.31126%; height: 23px; text-align: center;"><strong>Pergunta</strong></td><td style="width: 6.15108%; height: 23px; text-align: center;"><strong>Nota da Pergunta</strong></td></tr><tr style="height: 24px;"><td style="width: 3.31126%; height: 24px;">Pergunta n°1</td><td style="width: 6.15108%; height: 24px; text-align: center;">51,67</td></tr><tr style="height: 24px;"><td style="width: 3.31126%; height: 24px;">Pergunta n°2</td><td style="width: 6.15108%; height: 24px; text-align: center;">90</td></tr><tr style="height: 24px;"><td style="width: 3.31126%; height: 24px;">Pergunta n°3</td><td style="width: 6.15108%; height: 24px; text-align: center;">70</td></tr></tbody></table>

**1\. Calculo do percentual das opções de resposta:  
**O cálculo do **percentual das opções de resposta**, será o mesmo independente da configuração. Para o cálculo do percentual de cada opção de resposta, a fórmula é a seguinte:

**_Formula: (Qtde participantes que responderam à opção de resposta X / total da qtde de todas as respostas) \* 100._**

Considerando os dados da pergunta n°1 e aplicando a fórmula, o cálculo dos percentuais ficaria da seguinte forma:

**_A_ ⇒ (1/ 6)\* 100 = 16,66%**  
**_B_ ⇒ (3/ 6) \* 100 = 50,00%  
_C_ ⇒ (2/ 6) \* 100 = 33,33%**

---

**2.** **Calculo da nota da pergunta se a opção “Utilizar peso da pergunta no Cálculo da Nota” estiver marcada:**   
Se na configuração da pesquisa estiver marcada a opção **Utilizar peso da pergunta no Cálculo da Nota**, essa configuração afeta no **cálculo da nota da pergunta** e na **nota geral da pesquisa.  
**

![](https://wiki.simeon.com.br/wp-content/uploads/2023/02/img_63ef7a364ce25.png)

**2.1.** Para o cálculo da **nota da pergunta:  
**Se a **pergunta** tiver um p**eso igual a 0, a nota será zerada**, independentemente das respostas.  
Se a **pergunta** tiver um **peso maior que 0, a nota será calculada como a média ponderada das respostas**, usando a seguinte fórmula:  
**  
Formula: (qtde de respostas A \* peso A) + (qtde de respostas B\* peso B) + (qtde de respostas C\* peso C_…_) / qtde total de respondentes**

Considerando os dados da pergunta n°1, e aplicando a fórmula, o cálculo ficaria da seguinte forma:

**⇒ ((100\*1)+(50\*3)+(30\*2))/(1+3 + 2) = 51,67**

**2.2** Para o cálculo da **nota geral**, é obtido somando a multiplicação da nota de cada pergunta pelo seu peso e, em seguida, dividindo pela soma dos pesos das perguntas. A fórmula é a seguinte:

**_Formula: ((NotaPerguntaA \* PesoPerguntaA) + (NotaPerguntaB \* PesoPerguntaB) + (NotaPerguntaC \* PesoPerguntaC…)) / (PesoPerguntaA + PesoPerguntaB + PesoPerguntaC)_**

Considerando os dados das perguntas n°1, n°2 e n°3 que você forneceu e aplicando a fórmula, o cálculo da nota fica da seguinte forma:

  
**⇒  ((67,57 \* 0) + (90 \* 1) + (92 \* 2)) / (0 + 1 + 2) =  91,33**

---

**3.** **Calculo da nota da pergunta se a opção “Utilizar peso da pergunta no Cálculo da Nota” não estiver marcada:**   
Se na configuração da pesquisa **Utilizar peso da pergunta no Cálculo da Nota** não estiver marcada, o cálculo da nota da pergunta será realizado da seguinte forma:

_**  
Formula: (qtde de respostas A \* peso A) + (qtde de respostas B\* peso B) + (qtde de respostas C\* peso C…) / qtde total de respondentes**_

Considerando os dados da pergunta n°1, e aplicando a fórmula o cálculo ficaria da seguinte forma:

**⇒ ((100\*1)+(50\*3)+(30\*2))/(1+3 + 2) = 51,67**

---

**4\.** Para o cálculo do **resultado do Índice Geral (IG)**, , a fórmula é a soma das notas das perguntas dividida pela quantidade de perguntas.  
A fórmula é a seguinte:

**_Formula: (NotaPerguntaA + NotaPerguntaB + NotaPerguntaC…) / Quantidade de perguntas._**

Considerando as notas das perguntas n°1, n°2 e n°3, e aplicando a fórmula o cálculo ficaria da seguinte forma:

**⇒  (51,67 + 90 + 70) / 3 = 70,56**

---

**![](https://wiki.simeon.com.br/wp-content/uploads/2021/06/atention-300x158.png)**

**Atenção:** . Se na pesquisa há alguma opção de resposta marcada como **Não Considera no Cálculo**, o EPA não levará em consideração essa opção de resposta ao calcular a nota da pergunta. Isso significa que o peso ou contribuição dessa opção específica será excluído do cálculo da nota da pergunta.

---

Fonte: https://wiki.simeon.com.br/calculo-do-questionario/
