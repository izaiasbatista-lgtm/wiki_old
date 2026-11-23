---
title: "Planejamento – Entendendo o cálculo do Desempenho do Indicador"
id: 1897
slug: "entendendo-o-calculo-do-desempenho-do-indicador"
url: "https://wiki.simeon.com.br/entendendo-o-calculo-do-desempenho-do-indicador/"
data: "2019-03-29T10:02:10"
modificado: "2026-10-15T18:17:34"
pasta: "1.1-PLANEJAMENTO/Configurar-indicador"
categorias:
  - "Configurar indicador"
  - "Painel de indicadores"
tags:
  - "cálculo"
  - "calculo desempenho"
  - "desempenho"
  - "polaridade"
  - "quanto mais melhor"
  - "quanto menos melhor"
  - "relativo"
---

# Planejamento – Entendendo o cálculo do Desempenho do Indicador
O cálculo do desempenho dos Indicadores no EPA pode variar conforme a sua **Polaridade**, a polaridade é configurada no cadastro do Indicador na aba Informações Básicas.  
  

![](https://wiki.simeon.com.br/wp-content/uploads/2021/09/img_613bba9300734.png)

-   **Polaridades do Indicador  
      
      
    **
    
    Existem 3 polaridades permitidas, e cada uma tem a sua fórmula para calcular o desempenho do indicador:  
      
    

![](https://wiki.simeon.com.br/wp-content/uploads/2019/03/img_5c9e16e886c1a.png)  
  
  

> **Atenção:** Nos casos que o **resultado** e o **alvo** do indicador for negativo, usamos a seguinte formula:  
> **((alvo – resultado)/alvo\*100) + 100**  
> Ou seja, estamos medindo o percentual entre o alvo e o resultado em relação ao alvo.  
>   

-   Exemplo do cálculo a polaridade **Quanto menos melhor**
    

![](https://wiki.simeon.com.br/wp-content/uploads/2019/03/img_5c9e173c2d106.png)

  
Neste exemplo da imagem acima, o resultado obtido foi maior que o alvo definido. Isso significa que o desempenho ficará abaixo de 100%, pois, para essa polaridade, quanto menor o resultado, melhor será o desempenho.  
  

### ⇒Fórmula do desempenho:

Quando a polaridade é **“Quanto menos, melhor”**, o cálculo do desempenho é realizado da seguinte forma:

**Desempenho = (1 – ((Resultado – Alvo) / Alvo)) × 100  
  
**

### Exemplo prático

-   Alvo: 100.000,00
-   Resultado: 112.750,16

Substituindo os valores na fórmula:

**(1 – ((112.750,16 – 100.000,00) / 100.000,00)) × 100**

**(1 – (12.750,16 / 100.000,00)) × 100**

**(1 – 0,1275) × 100**

**0,8725 × 100 = 87,25%  
  
**

Nesse cenário:

-   Se o resultado fosse exatamente 100.000,00, o desempenho seria 100%.
-   Como o valor ficou 12,75% acima do alvo, o desempenho foi reduzido para 87,25%.  
      
    

---

###   
⇒ Quando o alvo é negativo e a polaridade é “Quanto menos, melhor”:  
  

### Cenário 1: Resultado maior ou igual a zero

Quando o alvo é negativo e o resultado informado é maior ou igual a zero, o sistema pega o valor do percentual atingido e subtrai de 100%.

Nesse caso, como o resultado já está distante do alvo negativo esperado, o desempenho tende a ficar ainda mais negativo.  
  

### Cenário 2: Resultado também negativo

Quando tanto o alvo quanto o resultado são negativos, o sistema realiza o cálculo proporcional considerando a proximidade entre o resultado e o alvo.

Nesse cenário:

-   Quanto mais próximo o resultado estiver do alvo, maior será o percentual de desempenho.
-   Quanto mais distante estiver, menor será o desempenho.  
      
      
    

---

### ⇒ Quando o alvo for igual a zero:  
  

Nos cenários em que o indicador possui a polaridade **“Quanto menos, melhor”** e o alvo é igual a zero, o cálculo padrão não pode ser utilizado, pois matematicamente não é possível realizar divisão por zero.

Nessa situação, o sistema aplica uma regra específica para calcular o desempenho.

### Cálculo do desempenho:

-   O desempenho base considerado é de 100%.
    
-   O resultado do indicador é multiplicado por (-1), e o valor obtido é somado ao desempenho base.  
      
    

### Fórmula: 

**Desempenho = (100 + (Resultado x (-1))  
  
**

---

### Cálculo do percentual atingido

O cálculo do percentual atingido será realizado da seguinte forma:

**Atingido = 100 + Valor do Indicador**

---

### Quando o resultado é zero

Quando o resultado informado é igual a zero, o cálculo do desempenho utiliza a seguinte fórmula:

**Desempenho = 100 + (100 – Percentual Atingido)**

  
  

-   Exemplo do cálculo a polaridade **Quanto Mais melhor**
    

![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/img_6074a9624b19d.png)

  
Neste exemplo da imagem acima, o lucro do mês foi maior que a meta definida no alvo. Portanto, o desempenho será superior a 100%, pois, nessa polaridade, quanto maior o resultado em relação ao alvo, melhor será o desempenho.

### Fórmula do desempenho:

Quando a polaridade é **“Quanto mais, melhor”**, o cálculo do desempenho é realizado da seguinte forma:

**Desempenho = (Resultado / Alvo) × 100  
  
  
**

### Exemplo prático:

-   Alvo: 12.895.747,37
-   Resultado: 18.996.573,33

Substituindo os valores na fórmula:

**(18.996.573,33 / 12.895.747,37) × 100 = 147,31%**

Nesse cenário:

-   O resultado ficou 6.100.825,96 acima do alvo.
-   Esse valor representa 47,31% acima da meta definida.
-   Por esse motivo, o desempenho final foi de 147,31%.  
      
    

---

###   
⇒ Quando o alvo for igual a zero:

Nos cenários em que o indicador possui a polaridade **“Quanto mais, melhor”** e o alvo é igual a zero, o cálculo padrão não pode ser utilizado, pois matematicamente não é possível realizar divisão por zero.

Nessa situação, o sistema aplica uma regra específica para calcular o desempenho.

### Fórmula aplicada:

**Desempenho = Resultado + 100**

### Exemplo

-   Resultado: 15

**Desempenho = 15 + 100 = 115%**

Nesse cenário, o valor informado no resultado será somado a 100 para compor o desempenho final do indicador.

-   Exemplo do cálculo a polaridade **Relativa**
    

![](https://wiki.simeon.com.br/wp-content/uploads/2021/04/img_6074b47bee238.png)

Neste exemplo, o resultado obtido ficou abaixo da meta definida no alvo. Por esse motivo, o desempenho será inferior a 100%.

Quando a polaridade é **“Relativa”**, o cálculo do desempenho é realizado da seguinte forma:

### Fórmula do desempenho

**Desempenho = 100 – (100 – ((Resultado / Alvo) × 100))  
  
  
**

Como a fórmula pode ser simplificada matematicamente, o resultado final equivale a:

**Desempenho = (Resultado / Alvo) × 100**

### Exemplo prático

-   Resultado: 17,04
-   Alvo: 55

Substituindo os valores na fórmula:

**100 – (100 – ((17,04 / 55) × 100))**

**100 – (100 – 30,98)**

**100 – 69,02**

**\= 30,98%**

Devido ao arredondamento das casas decimais utilizado pelo sistema, o resultado apresentado pode variar para **31,03%**, conforme exibido na tela.

Nesse cenário:

-   O resultado atingiu aproximadamente 31% da meta definida no alvo.
-   Por esse motivo, o desempenho ficou abaixo de 100%.

> **![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbdba05736.png)**
> 
> -   Quando o indicador **não possui valor alimentado, o EPA considera automaticamente o resultado como zero e realiza o cálculo do desempenh**o com base nessa informação.
> -   Quando o indicador é configurado para **alimentação manual ou via planilha** e **ainda não possui valor informado**, **o sistema não assume automaticamente o valor zero**. **Nesse cenário, o desempenho não será calculado até que o indicador seja alimentado**.  
>     Após o lançamento do valor no indicador, o EPA realiza normalmente o cálculo do desempenho conforme a configuração da polaridade e da fórmula do indicador.

> ![](https://wiki.simeon.com.br/wp-content/uploads/2023/10/img_6532c2b3485d8.jpeg)
> 
> _**  
> Acesse nossos artigos para saber mais sobre o painel de indicadores!**_
> 
> [Como navegar no painel de indicadores](https://wiki.simeon.com.br/como-navegar-no-painel-de-indicadores/)
> 
> [Parametrizar / Configurar indicador – 1 – Aba Informações Básicas](https://wiki.simeon.com.br/parametrizar-configurar-indicador-1-aba-informacoes-basicas/)
> 
> [Funcionalidades das abas no painel de indicadores](https://wiki.simeon.com.br/funcionalidades-das-abas-no-painel-de-indicadores/)

---

Fonte: https://wiki.simeon.com.br/entendendo-o-calculo-do-desempenho-do-indicador/
